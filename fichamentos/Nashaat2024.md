# Towards Efficient Fine-Tuning of Language Models With Organizational Data for Automated Software Review

M. Nashaat and J. Miller, "Towards Efficient Fine-Tuning of Language Models With Organizational Data for Automated Software Review," in _IEEE Transactions on Software Engineering_, vol. 50, no. 9, pp. 2240-2253, 2024, doi: 10.1109/TSE.2024.3428324.

## 1. Fichamento de Conteúdo

O artigo apresenta o **CodeMentor**, um framework de aprendizado com poucos exemplos (_few-shot learning_) que utiliza modelos de linguagem de grande escala para automatizar tarefas de revisão de código. A proposta visa resolver o desafio da alucinação, em que Modelos de Linguagem em Grande Escala (LLMs, do inglês _Large Language Models_) geram código sem embasamento nas fontes oferecidas. O estudo utiliza técnicas como regras heurísticas, supervisão fraca, e aprendizado por reforço com feedback humano para melhorar a geração de _reviews_ (revisões) de código e refinar a sua qualidade final. A avaliação experimental mostra que o CodeMentor supera modelos já existentes, com melhorias de até 43,4% em tarefas de geração de resenhas e até 22,3% em estimativas de qualidade do código.

## 2. Fichamento Bibliográfico

- **_Few-shot learning_ (Aprendizado com poucos exemplos)**: Técnica de aprendizado de máquina onde o modelo é treinado com um número muito pequeno de exemplos, o que é essencial para o treinamento de modelos de linguagem em contextos específicos, como revisão de código. _[pg. 1]_
- **_Code review_ (Revisão de código)**: Processo no qual os desenvolvedores revisam contribuições de código para garantir a qualidade, aderência aos padrões e identificar problemas. _[pg. 1]_
- **Reforço com feedback humano**: Método de aprendizado de máquina no qual o modelo recebe feedback direto de seres humanos para melhorar seu desempenho, aplicando-se ao contexto de revisão de código gerado pelo CodeMentor. _[pg. 2]_
- **BLEU Score**: Métrica para avaliar a qualidade de textos gerados por IA, comparando palavras ou grupos de palavras gerados com os de um texto de referência. _[pg. 9]_

## 3. Fichamento de Citações

- "_CodeMentor outperforms all other models in terms of accuracy, precision, recall, and F1 score for code quality evaluation._"
- "_Compared to the baseline Transformer model, CodeMentor improved the precision and recall scores by about 6% and 35%, respectively._"
- "_CodeMentor significantly reduces the computational cost and time, with reductions of 53.7% for quality estimation and 34% for code review generation._"
- "_The framework generates new data samples from the initial organizational data, representing a novel approach to data augmentation._"
