# tccmbauspesalq
Repositório do TCC do MBA USP-ESALQ em Big Data e Analytics

1. NIOSH Worker Well-Being Questionnaire (WellBQ). O arquivo pode ser baixado através da página oficial do WellBQ no seguinte url:
https://www.cdc.gov/niosh/twh/wellbq/default.html#anchor_1593621108194

2. probabilidades_deparas: arquivo que contém todas as frequências dos dados demográficos e probabilidades de respostas de cada item de cada questão do questionário NIOSH. Contém todos os deparas das questões, domínios, subdomínios e constructos apresentados nas questões do questionário, os deparas das características demográficas utilizadas para gerar os dados sintéticos. 

3. cubo_análise_demografica: cubo de consumo que gera a tabela com o resumo dos dados demográficos, possui uma conexão criada com o arquivo GraficosResultados para geração de tabela dinâmica. 

4. cubo_análises_resultados: tabela vertical (dado de consumo) gerado para realizar análises e gráficos relacionando dados demográficos com dados de respostas de cada um dos trabalhadores respondentes. Contém uma conexão com o arquivo GraficosResultados para geração de gráficos e tabelas dinâmicas. 

5. TabelasAnaliseDadosResultados: Contém dois cubos de consumo, um para geração da tabela de dados demográficos e outro para geração da tabela de correlações. Contém uma conexão com o arquivo GraficosResultados. 

6. GraficosResultados: Arquivo que contém todas as análises de dados, gráficos, tabelas dinâmicas e tabelas de correlação e de dados demográficos, possui conexões com as tabelas anteriores que servem como base de dados para a geração das análises apresentadas no arquivo. Observar que talvez seja necessário configurar novamente a conexão entre os arquivos renomeando o PATH environment dos arquivos (caminhos de pastas onde os arquivos são armazenados). 

7. cria_tabela_analises: Notebook Jupyter contendo todos os códigos e scripts desenvolvidos para a criação dos artefatos apresentados neste trabalho. Para a execução do notebook é necessário ter o Python e o Jupyter instalados na máquina. O único artefato necessário para a execução sem erros do notebook é o arquivo probabilidades_deparas.xlsx que contém as probabilidades geradoras dos dados demográficos e de respostas do questionário NIOSH. 
