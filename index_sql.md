## Comprehensive List of SQL Topics

**I. SQL Fundamentals**

1.  **Introduction to Relational Databases:**
    *   History (SEQUEL → SQL), relational model & ACID.
    *   Popular RDBMS: PostgreSQL, MySQL, SQLite, SQL Server, Oracle.
    *   Setting up local DB instances, GUI tools (pgAdmin, MySQL Workbench).
2.  **Basic SQL Syntax:**
    *   Statements, clauses, keywords, identifiers.
    *   Data Types: numeric, character, temporal, boolean, UUID, JSON.
    *   Comments (`--`, `/* … */`).

**II. Data Definition Language (DDL)**

3.  **Creating Databases & Schemas (CREATE DATABASE, CREATE SCHEMA).**
4.  **Tables & Columns:**
    *   `CREATE TABLE`, column definitions, constraints (NOT NULL, UNIQUE, CHECK, DEFAULT).
    *   Auto-increment / identity columns (`SERIAL`, `AUTO_INCREMENT`).
5.  **Altering Tables (`ALTER TABLE`):** Add/modify/drop columns, constraints, rename.
6.  **Dropping Objects:** `DROP TABLE`, `DROP DATABASE`.

**III. Data Manipulation Language (DML)**

7.  **Inserting Data (`INSERT INTO ... VALUES`, `INSERT ... SELECT`).**
8.  **Updating Data (`UPDATE ... SET ... WHERE`).**
9.  **Deleting Data (`DELETE FROM ... WHERE`).**
10. **Transaction Control:** `BEGIN`, `COMMIT`, `ROLLBACK`, isolation levels (READ COMMITTED, REPEATABLE READ, SERIALIZABLE).

**IV. Data Querying (SELECT)**

11. **Basic SELECT & Filtering (`WHERE`).**
12. **Ordering (`ORDER BY`), Limiting (`LIMIT`, `TOP`, `OFFSET`).**
13. **Aggregate Functions:** `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`.
14. **Grouping (`GROUP BY`) & Filtering (`HAVING`).**
15. **Joins:**
    *   `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL JOIN`.
    *   Cross joins, self joins.
16. **Set Operations:** `UNION`, `INTERSECT`, `EXCEPT`.
17. **Subqueries, Correlated Subqueries & CTEs (`WITH`).**
18. **Window Functions:** `OVER`, partitions, ranking (`ROW_NUMBER`, `RANK`, `DENSE_RANK`), running totals, moving averages.
19. **Conditional Expressions:** `CASE`, `COALESCE`, `NULLIF`.

**V. Constraints & Indexing**

20. **Primary Keys & Foreign Keys.**
21. **Unique & Composite Keys.**
22. **Indexes:** B-tree, hash, GIN/GiST, covering indexes, partial indexes.
23. **Performance Considerations & EXPLAIN Plans.**

**VI. Views & Materialized Views**

24. **Creating & Altering Views.**
25. **Using Views for Abstraction & Security.**
26. **Refreshing Materialized Views.**

**VII. Stored Procedures, Functions, & Triggers**

27. **Procedural Languages (PL/pgSQL, T-SQL, PL/SQL).**
28. **Creating Stored Procedures & User-defined Functions (UDFs).**
29. **Triggers:** AFTER/BEFORE INSERT/UPDATE/DELETE.
30. **Event Scheduling & Jobs.**

**VIII. Security & Permissions**

31. **Users, Roles, and Privileges (`GRANT`, `REVOKE`).**
32. **Authentication Methods, SSL connections, encryption.**
33. **Row-Level Security & Policies.**

**IX. Backup, Recovery & Maintenance**

34. **Backup Strategies:** Logical (dump), physical, point-in-time recovery (PITR).
35. **Replication & High Availability (Streaming, Logical Replication).**
36. **Vacuuming / Defragmentation, Statistics, Reindexing.**

**X. Advanced Topics**

37. **Normalization & Denormalization (1NF–5NF).**
38. **ACID vs BASE, CAP theorem in distributed SQL (CockroachDB).**
39. **Partitioning & Sharding.**
40. **NoSQL Extensions:** JSONB, hstore, full-text search.
41. **Temporal Tables & Time-series features.**
42. **Geospatial Data (PostGIS).**
43. **Parallel Query Execution & Columnar Storage (Citus, Redshift).**
44. **Query Optimization & Tuning:** indexes, rewrite rules, statistics, `EXPLAIN ANALYZE`.

**XI. Best Practices**

45. **Consistent Naming Conventions.**
46. **Avoiding SELECT *, proper indexing, avoiding unnecessary DISTINCT.**
47. **Prepared Statements & Parameterized Queries.**
48. **Data Integrity & Referential Integrity.**
49. **Change Management & Migration Tools (Flyway, Liquibase, Alembic).**
50. **Testing: Unit, integration, property-based testing (sqldiff, pgTAP).**

**XII. Ecosystem & Tooling**

51. **ORMs:** SQLAlchemy, Django ORM, Hibernate, ActiveRecord.
52. **Data Visualization & BI Tools (Tableau, Power BI, Metabase).**
53. **Data Warehousing & ETL Pipelines (Airflow, dbt).**

**XIII. Resources**

54. **Standards References (SQL-92, SQL:1999, SQL:2003, SQL:2011, SQL:2016).**
55. **Books:** "SQL Fundamentals", "SQL Performance Explained", "SQL Antipatterns".
56. **Online References:** sqlbolt.com, leetcode SQL, official documentation.
