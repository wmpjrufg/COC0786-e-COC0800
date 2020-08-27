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

<p align="justify">Para ilustrar essas situações vamos aplicar alguns critérios de limpeza dos dados no <a href="https://www.kaggle.com/austinreese/craigslist-carstrucks-data"><i>dataset</i></a> de carros usados da Craiglist. O arquivo pode ser acessado via plataforma Kaggle e se trata de um problema de predição de preços de veículos usados no Estados Unidos da América. O <a href="https://www.kaggle.com/austinreese/craigslist-carstrucks-data"><i>dataset</i></a> possui um total de 25 colunas com descrições de modelo, fabricante, cor e outros tipos de dados relativos à um veículo.</p>

<p align="justify">Para consultar o Notebook Jypiter exemplo clique no link.</p>

![Alt ou título da imagem](https://www.flaticon.com/free-icon/file_2570575?term=python&page=1&position=5)
<a href="https://wmpjrufg.github.io/COC0786-e-COC0800/Notebooks/notebook1.ipynb"><i>notebook</i></a>
