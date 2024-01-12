# Postgres-training-materials

## Getting Started
The Internals of PostgreSQL for database administrators and system developers

https://www.interdb.jp/pg/index.html

https://edu.postgrespro.com/postgresql_internals-14_parts1-3_en.pdf

https://www.postgresql.org/docs/current/internals.html

## How a Postgres Works (High Level)

https://www.interdb.jp/pg/pgsql01.html

https://www.interdb.jp/pg/pgsql02.html

Chapter 1 of https://edu.postgrespro.com/postgresql_internals-14_parts1-3_en.pdf

### Path of a Query
https://www.interdb.jp/pg/pgsql03.html

https://www.postgresql.org/docs/current/query-path.html

### Parser

https://www.postgresql.org/docs/current/parser-stage.html

#### Planner/Optimizer

https://www.postgresql.org/docs/current/planner-optimizer.html

#### Executor

https://www.postgresql.org/docs/current/executor.html

## How Indices Work

### Part 1
https://postgrespro.com/blog/pgsql/3994098

### Part 2
https://postgrespro.com/blog/pgsql/4161264

### Part 3 (Hash Indices)
https://postgrespro.com/blog/pgsql/4161321

### Part 4 (B-Tree Indices)
https://postgrespro.com/blog/pgsql/4161516

### Part 5 (Gin Indices)
https://habr.com/en/company/postgrespro/blog/448746/

### Heap Only Tuple Scans and Index Scans
https://www.interdb.jp/pg/pgsql07.html

## Joins and Sorting

### Merge Joins and Sorting Strategies

https://postgrespro.com/blog/pgsql/5969770

## Transaction System and Updating Data

https://www.interdb.jp/pg/pgsql05.html

Part 1 (Chapter 2-8) of https://edu.postgrespro.com/postgresql_internals-14_parts1-3_en.pdf

### Locks

Part 3 (Chapter 12-15) of https://edu.postgrespro.com/postgresql_internals-14_parts1-3_en.pdf

## Json and JsonB

https://scalegrid.io/blog/using-jsonb-in-postgresql-how-to-effectively-store-index-json-data-in-postgresql/

## Other
https://www.interdb.jp/pg/pgsql04.html

Buffer and WAL
Part 2 (Chapter 9-11) https://edu.postgrespro.com/postgresql_internals-14_parts1-3_en.pdf

## Generalized Intro to Databases (Focus on the Storage Engine and Distribution)

[Database Internals](https://www.amazon.com/Database-Internals-Deep-Distributed-Systems/dp/1492040347/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=)

Written to generalize all database, with a focus on MySQL and Postgres. Could be a little confusing if you are a beginner who only cares about Postgres, but its a great read, well organized, packed with lot of good information for anyone who wants get started building databases.

## Table Access Methods

https://www.postgresql.org/docs/current/tableam.html
https://www.postgresql.fastware.com/blog/postgresql-table-access-methods

### OrioleDB Architecture (Non-MVCC,  OLTP)

[OrioleDB](https://github.com/orioledb/orioledb/blob/main/doc/arch.md#orioledb-architecture)

### Hydra (ColumnStore OLAP)

[Hydra](https://github.com/hydradatabase/hydra/tree/main)

### Zedstore (ColumnStore OLAP)

https://github.com/greenplum-db/postgres/tree/zedstore
https://www.postgresql.org/message-id/CALfoeiuF-m5jg51mJUPm5GN8u396o5sA2AF5N97vTRAEDYac7w%40mail.gmail.com
https://news.ycombinator.com/item?id=24761008
Source Code? https://github.com/greenplum-db/postgres/tree/zedstore
https://blogs.vmware.com/opensource/2020/07/14/zedstore-compressed-columnar-storage-for-postgres/
https://www.pgcon.org/events/pgcon_2020/sessions/session/44/slides/13/Zedstore-PGCon2020-Virtual.pdf
