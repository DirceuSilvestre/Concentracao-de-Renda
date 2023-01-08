<h1 align="center">
Onde está concentrada a renda no Rio de Janeiro?
</h1>

<br>

## Visando a prática das habilidades:
    - Entendimento do problema e do contexto de negócio
    - Aquisição dos dados
    - Limpeza dos dados
    - Análise Exploratória dos Dados  
<br>

## Ferramentas utilizadas:
    - numpy
    - pandas
    - geopy
    - folium
<br>
  
## Descrição do processo
<br>

Coletei do IBGE os dados para limpeza e análise, porém eles disponibilizam planilhas com dados já organizados e limpos.
Então fiz o download da Tabela 4.19.1.1 - Pessoas de 10 anos ou mais de idade, total da renda, economicamente ativas e ocupadas na semana de referência, por sexo. <br>
Trabalhei neles retirando o que não seria necessário para o meu objetivo, deixando somente a renda total das pessoas de cada município e o respectivo nome. <br>
A partir disto busquei e substitui cada nome de município por suas coordenadas, e as acrescentei ao mapa do estado do Rio de Janeiro com todas as divisas demarcadas.
<br>

## Conclusões
<br>

Para uma análise de viabilidade econômica, os municípios citados a seguir, e também os que ficam entre dois ou mais, são os que eu sugeriria para iniciar o estudo. <br>
A maior concentração da renda em nosso estado está na capital. A soma do rendimento dos seus moradores é a maior de todos os municípios. Inclusive pela história da nossa cidade, que sempre foi zona portuária e comercial, e durante muitos anos capital do Brasil.<br>
Dado este fato amplamente conhecido, retirei da tabela o município do Rio de Janeiro pois seu valor se diferenciava drasticamente de todos os outros.<br>
Então assim produzimos nosso segundo gráfico, conseguindo visualizar melhor a concentração de renda em nosso estado.<br>

Observamos que as cidades que mais se destacam são: <br>
      - Duque de Caxias <br>
      - São Gonçalo <br>
      - Nova Iguaçu
      <br>
As 3 concentram alta atividade industrial, e com próximidade a capital. Dado o alto custo de vida e do comércio na captial entendemos porque cidades vizinhas também concentram industrias e são populosas.<br>
Outras cidades que também se destacam no gráfico, em ordem, são: <br>
      - Belford Roxo <br>
      - São João de Meriti <br>
      - Niterói <br>
      - Petrópolis <br>
      - Campos dos Goytacazes <br>
      - Volta Redonda <br>
As 3 primeiras cidades estão entre as principais citadas anteriormente e a capital do estado, no quesito geográfico, então foram favorecidas pelo crescimento dos municípios vizinhos. <br>
As 3 últimas estão bem mais afastadas da capital, com exceção de Petrópolis que tem limite com Duque de Caxias, e cresceram em volta das industrias, como a maior siderurgica da América Latina em Volta Redonda, a extração de petróleo e gás natural em Campos dos Goytacazes, e a industria e comércio textil em Petrópolis. <br>
<br>





