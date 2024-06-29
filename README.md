# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.

✔🚀🌍
Incrivel esse lab, O bootcamp começou com uma visão geral do SageMaker. Aprendi sobre suas funcionalidades, como treinamento de modelos e implantação de endpoints.
A interface do SageMaker Studio é intuitiva e facilita o desenvolvimento de modelos,A etapa inicial envolveu a preparação dos dados. Aprendi a carregar dados do Amazon S3, o SageMaker oferece recursos para transformação de dados, como pré-processamento e engenharia de recursos. Em resumo, o bootcamp de Amazon SageMaker foi uma experiência enriquecedora. Aprendi a usar essa poderosa ferramenta para resolver problemas de ML e estou ansioso para aplicar esse conhecimento em projetos futuros. 

Esses foram as metricas do meu "Analyze"

Model status

Avg. wQL - 0.086  # O Avg. wQL é uma métrica usada para avaliar a qualidade de modelos de previsão, especialmente em problemas de regressão. Ele mede a diferença entre os valores previstos e os valores reais, ponderando os erros com base em quantis específicos (por exemplo, 10%, 50% ou 90%). Quanto menor o Avg. wQL, melhor o desempenho do modelo.

MAPE - 0.290  # O MAPE é uma métrica comum para avaliar a precisão de previsões em termos percentuais. Ele calcula a média das porcentagens de erro absoluto entre as previsões e os valores reais. Valores mais baixos indicam maior precisão.

WAPE -0.152 # O WAPE é semelhante ao MAPE, mas pondera os erros com base na importância de cada observação. É útil quando diferentes pontos de dados têm diferentes relevâncias. Novamente, valores menores são desejáveis.

RMSE - 1.535 # O RMSE é uma métrica de erro que mede a raiz quadrada da média dos erros quadrados entre as previsões e os valores reais. É amplamente usado em problemas de regressão. Quanto menor o RMSE, melhor o ajuste do modelo aos dados.

MASE - 0.180 #O MASE é uma métrica que compara o erro absoluto médio do modelo com o erro absoluto médio de um modelo ingênuo (como a média histórica). Ele é útil para séries temporais e permite avaliar a capacidade de generalização do modelo. Valores próximos a 1 indicam que o modelo é tão bom quanto o modelo ingênuo.
