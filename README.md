# PostGIS / Geo Queries

Coleção de queries e mini-projetos usando PostgreSQL + PostGIS, desenvolvidos nos blocos de estudo de segunda-feira.

## Objetivo
Construir e documentar consultas espaciais reais — desde operações básicas (`ST_Distance`, `ST_Intersects`) até análises mais complexas (buffers, clustering espacial, junções geoespaciais).

## Estrutura
```
exemplos/
  01-operacoes-basicas.sql
  02-buffers-e-areas.sql
  03-joins-espaciais.sql
```

## Como usar
Cada arquivo `.sql` tem comentários explicando o objetivo da query e o raciocínio por trás da escolha da função PostGIS usada.

## Progresso
- [ ] Operações básicas (ST_Distance, ST_Within, ST_Intersects)
- [ ] Buffers e cálculo de área
- [ ] Joins espaciais entre tabelas
- [ ] Indexação espacial (GiST) e otimização de performance
- [ ] Mini-projeto: análise de cobertura geográfica

📖 Trilha completa em [trilha-postgresql-postgis.md](./trilha-postgresql-postgis.md)
