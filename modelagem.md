# Modelagem de Dados

## Como modelar dados

- Identificar os tipos de entidade (tabela);
- Identificar atributos (coluna);
- Aplicar convenção de nomes;
- Identificar relacionamentos;
- Associar chaves;
- Normalizar para reduzir a redundância dos dados;

## Nomenclaturas

- Tabelas com nome em maiúsculo.
- Colunas com nome em minúsculo.
- Nunca usar espaço em branco.
- Não use acentos e cedilha.
- Para separar nomes use o símbolo de _ (underline), ou outros simbolos não são permitidos.
- Para uma boa prática use um prefixo (3 caracteres) para indicar as tabelas e utilize este prefixo para as colunas.
  - Exemplo:
    ```sql
        CLI_CLIENTE - cli_nome
    ```
- Para os campos chaves use o nome ID ou Codigo

## Objetos (Constraints)

| Tipo de Objeto (Constraint) | dbDiagram |
| --------------------------- | --------- |
| Chave Primária | primary key |
| Chave Unica | unique |
| Chave Extrangeira | Ref: |
| Auto Numeração | increment |
| Permitir Nulo | Not Null |
| Não Permitir Nulo | Null |
| Valor Padrão | Default: |


https://dbdiagram.io/home
https://survey.stackoverflow.co/2023/#databases
https://blog.betrybe.com/tecnologia/bancos-de-dados/
https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-are-databases

