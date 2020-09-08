### O PRÉ-PROCESSAMENTO

<p align="justify">A etapa de pré-processamento é posterior a coleta ou seleção dos dados que serão tratados para extração de conhecimento.O pré-processamento dos dados é então uma etapa primordial em problemas que envolvem Mineração de Dados e é onde normalmente se gasta a maior energia para aplicação de modelos de Mineração de Dados. Fernandez [1] afirma que 70% do tempo gasto no processo de mineração de dados é com o pré-processamento das informações.Portanto é nessa etapa que o cientista de dados deverá ter o entendimento do “negócio”e com esse entendimento fazer a preparação da base de dados.</p>

<p align="justify">A escolha dos atributos (ou variáveis) da forma mais assertiva possível poderá garantir um bom desempenho no processo de extração de conhecimento de uma base. A etapa de pré-processamento dos dados tem como objetivo preparar os dados para que seja possível aplicar os modelos de Inteligência Computacional que serão detalhados na fase de processamento. Nessa etapa questões como a qualidade dos dados, pré-visualização dos dados, seleção de atributos mais relevantes são fatores que o analista de dados deverá levar em consideração para realização de uma avaliação mais assertiva.</p> 

<p align="justify">Para esse processo é fundamental a utilização dos procedimentos de Análise Exploratória de Dados (<b>EDA <i>Exploratory Data Analysis</i></b>) que consiste na aplicação de técnicas estatísticas para obter esse conhecimento prévio da base.</p> 

### A LIMPEZA DE DADOS

<p align="justify">A limpeza dos dados é a primeira tarefa de pré-processamento de dados. Nessa etapa tarefas de verificação de registros incompletos (<i>missing values</i>), duplicados e dados incorretos são analisados. Em relação aos registros incompletos Schmitt [2] afirma que são soluções passíveis de aplicação:</p>

1. Ignorar os registros;
2. Completar manualmente os valores faltantes;
3. Substituir por uma constante global;
4. Uso da média para preencher os valores faltantes;
5. Uso do valor mais provável, que pode ser predito com outra técnica de aprendizado de máquina como por exemplo os modelos de aprendizado semi-supervisionado.

<p align="justify">Outro aspecto a se observar na limpeza de dados são as variáveis com valores incorretos que tecnicamente são denominados na literatura como ruídos ou outliers. Esses ruídos normalmente desviam-se significativamente do padrão restante da população. Por exemplo em um banco de dados com alturas humanas existe um valor registrado de 6 metros, esse erro tipográfico produziu um outliers no conjunto de dados relativos à altura [3]. Porém deve-se ter atenção pois nem sempre outliers são produtos de erros de preenchimento, sendo que esse ruído pode ser apenas um dado que naturalmente se desvia do restante das amostras. Em problemas que envolvem análise de transações bancárias os outliers são muito importantes pois eles são um indicativo de fraudes no sistema.</p>

<p align="justify">Para ilustrar essas situações vamos aplicar alguns critérios de limpeza dos dados no dataset [4] de carros usados da Craiglist.org. O arquivo pode ser acessado via plataforma Kaggle e se trata de um problema de predição de preços de veículos usados no Estados Unidos da América. O dataset [4] possui um total de 25 colunas com descrições de modelo, fabricante, cor e outros.</p>

<p align="justify">Para consultar o Notebook Jypiter exemplo clique no link.</p>

+ Lorem ipsum dolor sit amet
+ Consectetur adipiscing elit
+ Integer molestie lorem at massa
+ Facilisis in pretium nisl aliquet
+ Nulla volutpat aliquam velit
  - Phasellus iaculis neque
  - Purus sodales ultricies
  - Vestibulum laoreet porttitor sem
  - Ac tristique libero volutpat at
+ Faucibus porta lacus fringilla vel
+ Aenean sit amet erat nunc
+ Eget porttitor lorem

!!!! na frente do texto:  
!!! na frente do texto:  

|  nome |  imagem |
|---|---|




<a href="https://nbviewer.jupyter.org/github/wmpjrufg/COC0786-e-COC0800/blob/gh-pages/Notebooks/notebook1.ipynb"><i>notebook 1 de carros usados</i></a>
