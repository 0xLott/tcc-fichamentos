# Local Explanations and Self-Explanations for Assessing Faithfulness in black-box LLMs

C. Fragkathoulas and O. S. Chlapanis, "Local Explanations and Self-Explanations for Assessing Faithfulness in black-box LLMs," in _Proceedings of the 13th Hellenic Conference on Artificial Intelligence_, 2024. doi: 10.1145/3688671.3688775.

## 1. Fichamento de Conteúdo

O estudo propõe uma nova abordagem para avaliar a fidelidade (do inglês _faithfulness_) de Modelos de Linguagem de Grande Porte (LLM, do inglês _Large Language Models_) em cenários de caixa preta (do inglês _black-box_), onde o acesso à arquitetura interna do modelo é limitado. Os autores introduzem uma técnica de explicabilidade (do inglês _explainability_) baseada em perturbações locais e autoexplicações (do inglês _self-explanations_) para identificar as partes do contexto que são suficientes e necessárias para que o modelo gere respostas corretas.

A metodologia proposta é inspirada na abordagem de validação cruzada (LOO, do inglês _leave-one-out_), que omite partes do contexto para determinar quais palavras ou trechos são essenciais para a geração de respostas corretas. A fidelidade (do inglês _faithfulness_) do modelo é avaliada comparando essas partes críticas com as autoexplicações (do inglês _self-explanations_) geradas pelo próprio modelo.

O experimento é validado usando o conjunto de dados Conjunto de Perguntas Naturais (do inglês _Natural Questions Dataset_), que contém perguntas de usuários reais e trechos de artigos da Wikipedia como contexto. Os resultados mostram que a técnica proposta é eficaz para explicar decisões do modelo e avaliar sua fidelidade (do inglês _faithfulness_), atribuindo a ela uma pontuação (do inglês _score_). O GPT-4, com a pontuação de 0.653, desempenhou melhor em comparação ao GPT-3.5, que obteve a pontuação de 0.691.

## 2. Fichamento Bibliográfico

- **_Explainability_ (explicabilidade)**: Capacidade de um modelo de descrever seu processo de decisão de forma compreensível para humanos, crucial para aumentar a confiança e a transparência em sistemas de _Artificial Intelligence_ (IA - Inteligência Artificial). Exemplo: _DeepThink_, do modelo _DeepSeek_. _[pg. 1]_
- **_Faithfulness_ (fidelidade)** : A medida de quão bem as explicações geradas por um modelo refletem seu processo real de tomada de decisão. _[pg. 2]_
- **_Leave-One-Out_ (LOO)**: Técnica de perturbação que omite partes do contexto para identificar elementos essenciais para a geração de respostas corretas. _[pg. 4]_
- **_Natural Questions Dataset_**: Conjunto de dados usado para avaliar sistemas de _Question Answering_ (Perguntas e Respostas), contendo perguntas reais e trechos de contexto da Wikipedia. _[pg. 2]_

## 3. Fichamento de Citações

- "_Explainable AI is crucial in helping users trust and effectively utilize AI systems, enabling developers to debug and improve models, ensuring compliance with regulatory standards, and mitigating biases within models._"
- "_By systematically omitting parts of the provided context, we can determine specific important words that, without them, the model is unable to respond correctly._"
- "_Unlike previous work, who are using only the exact-match accuracy metric for evaluation, we have designed a hybrid metric that combines the results of exact-match, normalized exact-match, fuzzy exact-match, [...] date transformations [...]. Exact match often fails due to natural language variability, such as different formatting of names or dates._"
