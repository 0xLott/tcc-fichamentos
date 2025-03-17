# Analyzing Developer Use of ChatGPT Generated Code in Open Source GitHub Projects

B. Grewal, W. Lu, S. Nadi, and C.-P. Bezemer, "Analyzing Developer Use of ChatGPT Generated Code in Open Source GitHub Projects," in _Proc. 21st Int. Conf. Mining Softw. Repos._, Lisbon, Portugal, 2024, pp. 157–161. doi: 10.1145/3643991.3645072.

## 1. Fichamento de Conteúdo

O artigo apresenta uma análise empírica sobre como os desenvolvedores utilizam trechos de código gerados pelo ChatGPT em projetos de código aberto no GitHub. Para tanto, utilizou-se a ferramenta Pydriller, por meio da qual se analisou alterações de código em repositórios minerados do GitHub. Foram analisados 3.044 trechos de código, e observou-se que, em média, 54% do código gerado foi incorporado aos projetos, com poucas alterações posteriores. Quando mudanças ocorreram, elas foram realizadas geralmente em menos de um dia e consistiram principalmente em ajustes pequenos de funcionalidade ou em reorganização do código.

## 2. Fichamento Bibliográfico

- **GitHub**: Plataforma de hospedagem de código-fonte onde desenvolvedores podem colaborar em projetos de software, usar _commits_ e _pull requests_, e versionar seu código. O estudo analisou como os trechos gerados pelo _ChatGPT_ são integrados aos repositórios do _GitHub_. _[pg. 1]_
- **_Commit_**: Registro de alterações no código em um repositório de controle de versão, permitindo rastrear a evolução do código. _[pg. 2]_
- **Pydriller**: Ferramenta usada para extrair e comparar alterações no código entre _commits_ no GitHub. O estudo utilizou o _Pydriller_ para identificar as linhas de código geradas pelo _ChatGPT_ e integradas nos projetos. _[pg. 2]_

## 3. Fichamento de Citações

- "_We find that a median of 54% of ChatGPT’s generated code is added to GitHub and it is uncommon for this code to be changed again._"
- "_A ChatGPT-generated code snippet remains in a project for a median of 89 days, and if changed, it typically happens within a day._"
- "_Of the 76 code snippets that changed in a subsequent commit, the changes mostly involved minor functionality adjustments, name refinements, and code reorganization._"
