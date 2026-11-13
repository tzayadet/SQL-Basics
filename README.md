<p align="center">
  <img src="https://img.shields.io/badge/DATABASES-SQL_BASICS-101010?style=for-the-badge&labelColor=050805&color=00FF41" alt="SQL Basics"/>
  <img src="https://img.shields.io/badge/RELATIONAL-QUERY_PRACTICE-101010?style=for-the-badge&logo=postgresql&logoColor=00FF41" alt="SQL"/>
</p>

# SQL Basics

SQL notes and introductory exercises covering relational queries, filtering, ordering and data aggregation.

<p align="center">
  <a href="docs/index.html"><strong>SHOWCASE SOURCE</strong></a> ·
  <a href="https://github.com/tzayadet/SQL-Basics"><strong>SOURCE CODE</strong></a> · <sub>PAGES ACTIVATION REQUIRED</sub>
</p>

[![GitHub Pages](https://github.com/tzayadet/SQL-Basics/actions/workflows/pages.yml/badge.svg)](https://github.com/tzayadet/SQL-Basics/actions/workflows/pages.yml)

## Contents

- [SQL notes](apuntes-sql.md): syntax notes and quick reference.
- [WHERE and ORDER BY](sql-basics-where-order-by.sql): introductory filtering and sorting exercise.
- [SQL operations 01](sql-operations-01.md) and [SQL operations 02](sql-operations-02.md): additional notes and exercises.

More focused exercises remain in their own repositories to avoid divergent copies:

- [SQL Lost at SQL](https://github.com/tzayadet/SQL-Lost-at-SQL)
- [SQL Police Department](https://github.com/tzayadet/SQL-Police-Department)

## Topics

- SELECT, WHERE and ORDER BY.
- DISTINCT and logical operators.
- Aggregate functions.
- GROUP BY and HAVING.
- Querying and analysing relational datasets.

## Run the exercises

Execute each query against the schema specified by its exercise in a compatible relational database management system. This repository contains notes and queries, not a complete database instance.

## Technology

- SQL
- Relational databases

## Showcase and deployment

The static showcase source is in `docs/`; GitHub Pages activation is required before it can be viewed publicly. It displays sample queries and links to study notes; it does not execute SQL in the browser.

The Pages workflow is defined in `.github/workflows/pages.yml` and publishes the static showcase.

## Scope

This is a learning repository. Query examples may require adaptation to the SQL dialect and schema used by a specific database.

## License

See [LICENSE](LICENSE).
