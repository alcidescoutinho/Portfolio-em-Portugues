<h1> WEB SCRAPING: Exploração da Oportunidade</h1>

- Autor: Alcides Gabriel
- Contato: alcidesgabriel.ds@gmail.com

<h2> Dados </h2>

  O web scraping (raspagem de rede, em tradução livre), também conhecido como extração de dados da web, é o nome dado ao processo de coleta de dados estruturados 
da web de maneira automatizada, podendo ou não usar uma API para a coleta. Para a realização desse trabalho a coleta foi toda estruturada e realizada usando biblioteca selenium que coletou os dados da página glassdoor(O intuito desse trabalho é meramente de estudo em relação aos dados disponíveis no site), sendo essa página conhecida mundialmente por não somente publicar vagas de emprego mas como também por permitir que funcionários das empresas possam avalia-las mantendo-se no anonimato. 

  Sendo assim é possível fazer uma avaliação mais requintada da vaga de emprego, visto que os dados de avaliação dessas empresas também foram coletados.
Sobre os dados coletados das informações disponíveis, podem ser divididos em 2 tópicos: Informações da Vaga e Informações da Empresa.

<h2> Objetivos </h2>

- Realizar a coleta dos dados em tempo real utilizando o google colab (jupyter)
- Extrair Informações desses dados (Feature Generation)
- Analisar as ofertas de trabalho com base em:
  - Trabalho Remoto
  - Experiência 
  - Descrição da Vaga

<h2> Organização dos arquivos </h2>

Ao todo são 4 arquivos postados nesse repositório
- **web_scraping_vagas.ipynb** : O primeiro arquivo que contém justamente a programação e explicação para a coleta dos dados usando o selenium.
- **Tratamento_de_dados_vagas.ipynb** : Arquivo contendo o tratamento realizado nesse dataset colhido.
- **Análise_Vagas_Power_Bi.pptx** :  Contém a análise de dados feita usando o power bi, mas como é impossível postar o arquivo aqui no GitHub, segue em formato de power point contendo o link do relatório.
- **Análise_Vagas_Power_Bi.pdf** : Contém a análise de dados feita usando o power bi em formato em PDF para não ter a necessidade de baixar o arquivo em power point.(Qualidade de conversão foi baixa, infelizmente)

<h2>Plano de análise</h2>

O plano de análise, segundo as autoras: Emily Robinson e Jacqueline Nolis, é uma ferramenta essencial para o cientista de dados pois a finalidade é escrever tudo que você pretende fazer com os dados, sendo muito útil para o cientista se manter focado em um caminho e não acabar se perdendo durante a análise. Outro ponto importante é que o trabalho do cientista de dados é responder perguntas e essas perguntas também devem estar presentes no plano de análise. Sendo assim, segue o plano a seguir:

- **Análise Geral das Ofertas de Trabalho coletadas**:
  - Quantas Vagas?
  - Quais os Cargos?
  - Quais os Locais de trabalho?
  - Quais os setores que essas empresas se concentram?
- **Análise para Trabalho Remoto**
  - Quantas Vagas?
  - Quais Cargos?
  - Quais Setores mais contratam nesse formato de trabalho?
  - Quais são os tipos de empresa?
- **Análise individual**:
  - Com as respostas anteriores, demostrar uma interação que seja possível:
    - Ver descrição da vaga;
    - Ver as avaliações sobre a empresa em relação a mediana do total de vagas:
    - Disponibilizar o link de acesso a vaga.
  
<h2> Informações Técnicas </h2>

- **Bibliotecas Utilizadas** 
  - Pandas
  - Numpy
  - Selenium 
  - BeautifulSoup
  - Regex
  - Time
  - Unidecode
  
  Diversas técnicas foram utilizadas durante a coleta e o tratamento de dados, todas sendo bem explicadas. 
