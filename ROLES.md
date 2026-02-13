Role
Name
Primary
Responsibility
(Spanish)
Key Artifacts
(English)
Evaluation Criteria (DGETI +
English)
1. The
Analyst
Traduce las reglas
de negocio a un
•
erd_diagram.
Concept: Correct cardinality
(1:N, N:M). English: Clear&
Designe
r
(Architec
t)
modelo visual.
Garantiza la
Normalización
(3FN).
mmd •
dictionary.m
d
descriptions in Data
Dictionary. Tech: Diagram
compiles in
Mermaid/Lucidchart.
2. The
SQL
Develop
er
(Builder)
Escribe el código
DDL para crear la
estructura. Define
tipos de datos
exactos.
•
01_schema.sq
l •
Constraints
(PK, FK)
Concept: Syntax accuracy
(CREATE, ALTER). English:
Meaningful table/column
names (snake_case). Tech:
Script runs without syntax
errors.
3. The
Databas
e
Adminis
trator
(Guardia
n)
Gestiona
seguridad,
usuarios y
backups.
Ensambla el
entregable final.
•
03_users.sql
• Backup
Strategy
Concept: Security principles
(Least Privilege). English:
Professional comments in
SQL scripts. Tech: Users
have correct permissions
(GRANT/REVOKE).
4. The
Query
Master
(Manipul
ator)
Pobla la base de
datos (Datos
semilla) y extrae
reportes de
inteligencia de
negocios.
•
02_seed.sql
•
queries/*.sq
l
Concept: Logic in JOINs and
Aggregates. English: Query
aliases and readability. Tech:
Queries return accurate data
sets.
5. The
SQL
Tester
Intenta romper la
BD. Valida
integridad
•
tests/bug_re
port.md •
Concept: Understanding of
constraints & validation.
English: Clear bug
descriptions (Expected vs.(QA /
Breaker)
referencial y tipos
de datos.
tests/test_c
ases.sql
Actual). Tech: Identification of
logic/structural flaws.
