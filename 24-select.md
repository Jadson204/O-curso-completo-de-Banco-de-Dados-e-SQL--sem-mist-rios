# O COMANDO SELECT
-- seleção projeção e junção
```sql
- SELECT NOW();
-- Retorna a data e a hora corrente
- SELECT NOW() as DATA_HORA;
```

# ALIAS DE COLUNAS
``` sql
-- Retorna a data ea hora corrente no formato de tabela
- SELECT NOME, SEXO, EMAIL FROM CLIENTE;
- SELECT NOME AS CLIENTE, SEXO, EMAIL FROM CLIENTE;
- SELECT NOME, SEXO, EMAIL, ENDERECO FROM CLIENTE;
- SELECT * FROM CLIENTE; 
- SELECT EMAIL, SEXO, ENDERECO, NOME , NOW() FROM CLIENTE;
```

