# FUNÇÕES DE AGREGAÇÃO

# CONTANDO OS REGISTROS DE UMA TABELA
```SQL
SELECT COUNT(8) FROM CLIENTE;/*Não recomendado, pois retorna o nome da função na tabela*/

SELECT COUNT (*) AS "Quantidade de registros da Tab. Cliente"
FROM CLIENTE

SELECT SEXO, COUNT(*) 
FROM CLIENTE;
/*Vai gerar um erro*/

SELECT SEXO, COUNT(*)
FROM CLIENTE
GROUP BY SEXO;
```