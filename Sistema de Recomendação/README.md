<h1> Sistema de recomendação: Livros da Amazon</h1>

O sistema de recomendação pode ser considerado como um dos modelos de Machine Learning mais utilizados ao redor do mundo, visto que todas as grandes e-commerces, como a amazon, e empresas de streaming como Netflix a utilizam.
O grande objetivo do sistema de recomendação é oferecer ao usuário diversos produtos que sejam de desejo do usuário e isso é geralmente feito de 4 formas:
- **Colaborativo**: Considera a experiência de todos os usuários.
- **Conteúdo**: Considera a experiência do usuário.
- **Conhecimento**: Utiliza modelos de classificação de machine learning para oferecer um produto.
- **Híbrido**: Utilizar 2 ou 3 modelos simultaneamente.

<h2>Base de dados</h2>

Os dados são constituídos de 3 datasets:
- **Base de dados de livros**: Onde contém informações sobre o livro como o código ISBN, author, título e outras infos.
- **Base de dados de usuário**: Contendo idade, localização e ID. 
- **Avaliações**: Avaliações que os usuários deram para os livros.


<h2>Objetivos do modelo</h2> 
  
 Criar um sistema de recomendação de livros eficiênte, no qual será implementado um sistema híbrido dos modelos Colaborativos e de Conteúdo.


<h2>Plano de análise</h2>

- Manipulação e Tratamento dos dados:
- Modelo baseado em Colaboração:
  - Utilizar baseado na compra dos mesmo livros.
- Modelo baseado em Conteúdo:
  - Um sistema de redução de dimensionalidade, como o PCA, pode trazer uma avaliação satisfatória de recomendação?
  - Um Cluster aplicado no PCA e na base de dados original, mantém certa equivalência de eficiência?
- Avaliação do resultado:
  - Quais dados podem ser esperados?
  - Como as recomendações se comportaram se comparadas entre si?
  - O resultado final foi satisfatório?


<h2>Informações</h2>

Autor: Alcides Gabriel

Contato: alcidesgabriel.ds@gmail.com



