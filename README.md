### Desafio O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
<p>Digital Innovation One </p>
<p>Aluna: Mirian Ajiki Molicawa </p>
<p>Mentor: Leonardo Cestarolli</p>


Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos. Nesse sentido, você pode organizar esse repositório da forma como preferir... Dica: organizar tudo em seu README.md pode ser uma alternativa bem rápida e efetiva, principalmente porque o GitHub provê uma interface bem simples e intuitiva para isso. Bons estudos!

Entrevista do Venilton Falvo Junior com o Gerente de Arquitetura de Dados - Leonardo Cestarolli da empresa Banco Carrefour.

<h2>O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados </h2>

Venilton - Bancos de dados SQL e NoSQL tem sido um assunto que tem gerado muitas dúvidas aos profissionais e alunos da área da TI a respeito de seu uso, O NoSQL irá substituir o SQL?
Leonardo - Grande parte dos especialistas asseguram que não, pois o surgimento do NoSQL surgiu apenas para suprir demandas onde o processamento dos bancos relacionais (SQL), não estava tendo um desempenho satisfatório , geralmente em aplicações que utilizam grande fluxo de dados e não seguem um certo padrão de schema, assim como nas aplicações tradicionais manipuladas por bancos de dados SQL.

Venilton - Os Bancos de dados não relacionais (NoSQL) apresentam uma estrutura de armazenamento feita exatamente para esses grandes fluxos de dados e para resolver problema desse armazenamento que não segue o padrão, a estrutura NoSQL cria um esquema para cada dado após o seu armazenamento. Eis a questão, se esses dados estão desordenados, como fazer uma consulta precisa?
Leonardo - A estrutura do NoSqL também pensou nisso e consulta os dados através da criação de índices para que sua localização possa ser encontrada e concluímos que seus papéis são complementares e muitas empresas estão se adequando ao modo híbrido de banco de dados , ou seja, o uso dos dois em paralelo , extraindo o melhor de cada banco para que seu banco de dados tenha um desempenho satisfatório mesmo com constantes mudanças nos fluxos de dados.

O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
Há um crescimento exponencial dos Sistemas de gerenciamento de bancos de dados(SGBD). E é necessário para o Engenheiro de Dados, buscar em se aperfeiçoar e se adaptar a esses plataformas. O contexto geral sobre o uso do banco de dados na atualidade.
Venilton - O que é SQL e NoSQL?
Leonardo - Banco de Dados Relacional - É um tipo de banco que armazena as relações entre tabelas, a exemplo da tabela cliente, relacionada a tabela de vendas da empresa, no qual será possivel pegar as vendas para determinado cliente através de um campo relacionado entre eles. - Banco de Dados não-Relacional - É um tipo de banco que não utiliza ou não possui campos relacionais entre as tabelas. Nos que possuem, eles não priorizam a relação, o tornando estético. A vantagem dele em relação ao relacional, é a facil escalabilidade(Aumento gradual dos dados armazenados) do banco, no qual ele se ultiliza de clusters.

Venilton - O NoSQL não foi criado para substituir o SQL?
Leonardo - Não, o banco de dados relacional é util para garantir a segurança e cumprimento da função no qual o banco de dados foi estabelecido, no qual, o NoSQL possui deficiência. Em resumo, são complementares sendo um para organização e outro para armazenamento em escala.

Venilton - Como se consulta um dado armazenado no NoSQL? A consulta deve ser planejada desde o começo, buscando evitar erros de busca e inconsitência de dados. Busque sempre priorizar dados importantes no NoSQL. Conhecer um SGBD de cada tipo é o suficiente para iniciar?
Venilton - Não é necessário conhecer todos os tipos a fundo, mas conhecer suas particularidades e saber a necessidades deles pra cada caso.


A Flexibilidade do NoSQL em frente ao SQL
Venilton - O NoSQL é mais flexivel por não seguir o ACID, ao contrário do SQL, além dos dados do NoSQL serem distribuidos em nuvem. No Banco Carrefour, quais o SGBD mais utilizados?
Leonardo - Oracle, HDFS, MongoDB, GCP

Evolução da arquitetura de sistemas e transições de estruturas
- A evolução quando o ambiente já é estabelecido é mais difícil, por isso é necessario a portabilidade ou a readaptação do banco com as novas tecnologias.
Sobre Datalake e Databricks
- Datalake é um repositório utilizado para armazenar todos os dados estruturados e não estruturados. Ao armazená-los de forma não estruturada pode-se realizar diferentes tipos de análise, incluindo processamento de big data, análise em tempo real e machine learning, a fim de adquirir melhores decisões. - Databricks é uma empresa que uma plataforma baseada na Web para trabalhar com o Spark, que fornece gerenciamento automatizado de cluster e notebooks no estilo IPython.

Venilton - Quais os maiores desafios na hora de realizar o ETL?
Leonardo - O maior desafio é a parte de manipulação de dados, no qual pode ser traduzido por diversas rotinas.

Venilton - O tipo de banco de dados influencia na complexidade?
Leonardo - Existe, mas não é só isso. Depende muito da estrutura e da demanda desse banco.

Venilton - Como é gerada a demanda dos dado e quem define quais dados serão coletados?
Leonardo - Depende do conhecimento e da infraestrutura do time. Além de outros fatores especificos.

Engenheiro e Cientista de dados
- O Papel do Engenheiro é preparar o banco para o cientista analisar os dados.
Deficiências em pessoas com skill em Estatística

Venilton - É necessario ter conhecimentos em estatística para poder ter o dominio na ciência de dados? Quais dicas para quem quer ser Engenheiro de dados do Banco Carrefour?
Leonardo - A ferramenta de SGBD não é o principal e sim o entendimento do conceito e aplicação dele.

https://web.dio.me/lab/o-papel-dos-bancos-de-dados-sql-e-nosql-na-engenharia-de-dados/learning/3892c232-fea3-4e52-bffb-3942aaf00f38
