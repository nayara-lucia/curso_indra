# Treinamento INDRA COMPANY


CREATE TABLE IF NOT EXISTS desafio.produto (

id_produto string,
ds_produto string,
id_subcategoria string

)
COMMENT 'Tabela de Produtos'
ROW FORMAT DELIMITED
FIELDS TERMINATED BY '|'
STORED AS TEXTFILE
location '/datalake/raw/produto/'
TBLPROPERTIES ("skip.header.line.count"="1");










