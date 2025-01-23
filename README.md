# Projeto DSlist para deploy no railway

---

- application-dev.properties
  - configuração para criar o sql do banco de dados e fazer o seed
  - cria o arquivo 'create.sql' na raiz do projeto
  - busca o seed no arquivo 'import.sql'
  - após aplicar comentar as linhas abaixo

```
#spring.jpa.properties.jakarta.persistence.schema-generation.create-source=metadata
#spring.jpa.properties.jakarta.persistence.schema-generation.scripts.action=create
#spring.jpa.properties.jakarta.persistence.schema-generation.scripts.create-target=create.sql
#spring.jpa.properties.hibernate.hbm2ddl.delimiter=;
```
