# PySpark-BigData
Resumo do Projeto
O projeto visou consolidar bases de dados distintas em uma única base por meio do processo de ETL, utilizando ferramentas como Google Colab e Google Cloud. Foram observados os seguintes parâmetros:

Base de Dados:
Os dados utilizados são referentes às Comunicações de Acidentes de Trabalho (CAT) do INSS para o ano de 2022, obtidos do sistema informatizado CATWEB. Estes dados podem apresentar divergências ou ausências, pois são registrados por sistema, telefone ou presencialmente.

Nível Infra:

O arquivo original e o tratado devem ser salvos em coleções diferentes no MongoDB Atlas.
Os datasets devem ser armazenados em um bucket do CloudStorage (tanto o original quanto o tratado).
O dataset final deve ser disponibilizado em um banco de dados MySQL.
Comentários:

Nível Pandas:

Extrair corretamente os dados para um dataframe.
Identificar e corrigir dados inconsistentes, substituindo valores ausentes por NaN/NA ou outro valor justificado.
Excluir colunas desnecessárias, explicando a razão da exclusão.
Comentar todos os passos realizados.
Agregar todos os dataframes originais em um único dataframe tratado.
Criar no mínimo três insights dos dados, podendo utilizar visualizações.
Nível PySpark:

Estruturar o dataframe usando StructType.
Identificar e limpar dados inconsistentes ou nulos.
Avaliar a necessidade de excluir colunas ou linhas, justificando a exclusão.
Renomear pelo menos duas colunas.
Criar pelo menos duas novas colunas relevantes a partir das existentes (utilizando agrupamento, agregação ou joins).
Utilizar filtros, ordenação e agrupamento para extrair dados relevantes.
Utilizar pelo menos duas Window Functions.
Desenvolver cinco insights utilizando SparkSQL.
