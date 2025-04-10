# SELECT – Seleção de Colunas

## 💡 Para que serve  
Serve para selecionar colunas de tabelas.


## 📚 Sintaxe

```sql
SELECT coluna_1, coluna_2, coluna_3  
FROM schema_1.tabela_1;
```

## 🧪 Exemplos

- Exemplo 1 – Seleção de uma coluna
  Liste os e-mails dos clientes da tabela `sales.customers`
```sql
SELECT email
FROM sales.customers;
```

- Exemplo 2 – Seleção de mais de uma coluna
  Liste os emails e nomes dos clientes:
```sql
SELECT email, first_name, last_name  
FROM sales.customers;
```

- Exemplo 3 – Seleção de todas as colunas
  Liste todas as informações dos clientes:
```sql
SELECT *  
FROM sales.customers;
```
