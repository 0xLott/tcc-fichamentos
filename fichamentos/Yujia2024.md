# Security Weaknesses of Copilot-Generated Code in GitHub Projects: An Empirical Study

Yujia Fu, Peng Liang, Amjed Tahir, Zengyang Li, Mojtaba Shahin, Jiaxin Yu, e Jinfu Chen. 2025. _Security Weaknesses of Copilot-Generated Code in GitHub Projects: An Empirical Study_. _ACM Transactions on Software Engineering and Methodology_ (_ACM Trans. Softw. Eng. Methodol._). https://doi.org/10.1145/3716848.

## 1. Fichamento de Conteúdo

O artigo aborda os desafios de segurança associados ao uso de ferramentas de geração de código baseadas em Modelos de Linguagem em Grande Escala (LLMs, do inglês _Large Language Models_), como o GitHub Copilot, CodeWhisperer e Codeium. O experimento realizado analisou 733 trechos de código gerados por essas ferramentas em projetos do _GitHub_, identificando que 29,5% dos trechos em Python e 24,2% em JavaScript possuem vulnerabilidades de segurança. Essas vulnerabilidades abrangem 43 categorias da CWE (Enumeração de Vulnerabilidades Comuns, do inglês _Common Weakness Enumeration_), incluindo problemas graves como CWE-330 (_Uso de valores aleatórios insuficientes_) e CWE-94 (Controle impróprio de geração de código). O estudo também explorou o uso do Copilot para corrigir problemas de segurança no código gerado pelo Copilot, mostrando que até 55,5% das vulnerabilidades podem ser corrigidas quando o Copilot é fornecido com mensagens de alerta originadas de ferramentas de análise estática.

## 2. Fichamento Bibliográfico

- **_Common Weakness Enumeration_ (CWE)**: Lista de vulnerabilidades de software conhecidas e comuns, usada no estudo para classificar e identificar fraquezas de segurança. _[pg. 2]_
- **_Code Injection_ (_Injeção de Código_)**: Vulnerabilidade em que código malicioso é injetado e executado em um sistema, frequentemente devido à falta de validação de entrada. _[pg. 2]_
- **_Cross-site Scripting_ (XSS)**: Vulnerabilidade de segurança que permite a injeção de scripts maliciosos em páginas _web_ visualizadas por outros usuários. _[pg. 2]_

## 3. Fichamento de Citações

- "_[...] AI models like Large Language Models (LLMs) have gained increased popularity due to their ability to produce functional code. However, their usage presents security challenges, often resulting in insecure code merging into the code base._"
- "_Around 30% of code snippets have security weaknesses._"
- "_It is possible to use Copilot Chat to fix security issues in Copilot-generated code._"
