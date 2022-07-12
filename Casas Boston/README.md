# Casas Boston

- Dados - O dataset contém informações de 1460 casas vendidas entre 2006 e 2010, onde estão presentes 79 características de cada casa, contendo informações numéricas e categóricas. Essa base de dados é bem famosa e muito utilizada para a prática de modelos de regressão linear por apresentar uma quantidade significativa de características.

Link para acesso ao dado https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

# Plano de análise
Autor: Alcides Coutinho
Contado: Presente na página inicial do GitHub
Objetivo: Melhor modelo de previsão com os modelos propostos
- <b/> Engenharia de Atributo </b>
  - Quais dados são qualitativos e quantitativos?
  - Quais dados quantitativos apresentam um coeficiente de variação maior que 100%?
  - Quais dados apresentam um viés alto para uma característica?
  - Possível aproveitar esses dados sem descartar?
  - Há dados redundantes?
  - Aplicar o encoder melhora o resultado?
  
- <b/> Machine Learning </b>
  - <i/> Voting </i>
    - Quais modelos se encaixam para o voting?
    - Quais as features que mais apresentam importância?
    - Qual o melhor resultado obtido?
  - <i/> Rede Neural </i>
    - Quais parâmetros se enquadram mais para a rede neural?
    - Qual o melhor resultado obtido?

# Informações sobre as técnicas utilizadas
- ## Engenharia de Atributos
  - Normalização das dispersões
  - Redução de dimensionalidade 
  - Binning
  - Target Encoder
  - Imputer de vazios
- ## Machine Learning
  - ### Voting
    - Voting
    - Modelos Ensembles
    - Auto ML (Otimização Bayesiana)
    - Feature Selection
  - ### Rede Neural
    - Feature Selection
    - Usando Tensorflow Keras
    
