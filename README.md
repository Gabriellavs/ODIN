# ODIN
Dimensões Ontológicas para Apoio a Análises Textuais

Para iniciar as atividades de execução do método ODIN, siga as instruções abaixo.

-- Instale e configure PDI - Job ETL.

-- Configure o SGBD PostgresSQL. Se preferir outro SGBD, lembre-se de configurar a conexão no Job do ETL

-- Defina o Corpus conforme o assunto.

-- Crie os objetos da base de dados conforme o Modelo de Dados Dimensional.

-- Gere arquivo CSV e XML, do Corpus selecionado, com os dados dos arquivos (No portal PUBMED o serviço está disponível).

-- Adicione o arquivo na pasta para a leitura. Veriricar no Job do ETL se a transformação está direcionada para a pasta correta.

-- Escolha as Ontologias e armazen-as no local onde deverão ser lidas.

-- Limpe e Anote o Corpus com as Ontologias escolhidas.

-- Armazene a anotação na tabela stganotacao.

-- Prepare o arquivo de personalização conforme as necessidades de execução - (Exemplo configODIN.xml).

-- Adicione o ODIN.jar na pasta de preferência e direcione a transformação do ETL Ontológico para a pasta desejada.

-- Instale, configure e execute o Job ETL.

-- Configure o Power Bi.


****************************

Versões:

Eclipse IDE for Java Developers
Version: Mars Release (4.5.0)

PostgreSQL
pgAdmin3 LTS by BigSQL
Version: 1.23.0b (May 31 2017)

Microsoft Power BI Desktop
Versão: 2.73.5586.661 64-bit

Pentaho Data Integration
Versão: 8.1

