# Module 2: SQL and Data Processing

## Goal
Develop confidence working with relational data, large datasets, and distributed processing systems used in ML and analytics engineering.

## Learning outcomes

- write efficient SQL queries
- reason about joins, aggregations, and filtering
- understand ETL and ELT patterns
- work with Spark SQL and distributed data
- understand data lakehouse concepts

## Topics

### SQL fundamentals
- SELECT, WHERE, GROUP BY, HAVING, ORDER BY
- joins: inner, left, right, full
- subqueries and CTEs
- window functions
- aggregation patterns
- case statements and conditional logic

### Performance and optimization
- indexing basics
- query plans
- partitioning and clustering concepts
- common anti-patterns
- materialized views where relevant

### Data processing and ETL
- ingestion patterns
- transformation logic
- bronze/silver/gold architecture basics
- pipeline design principles
- incremental vs full loads

### Apache Spark fundamentals
- resilient distributed datasets (RDD) conceptually
- DataFrames and transformations
- lazy evaluation
- actions and caching
- execution plans
- performance tuning basics

## Exercises

- Write a series of SQL questions against a sample sales dataset
- Build a small Spark job that reads, transforms, and writes data
- Create a data pipeline that cleans raw data into a modeled dataset
- Compare ETL and ELT workflows and explain tradeoffs

## Suggested stack

- PostgreSQL or SQLite for learning SQL
- PySpark for Spark basics
- Databricks notebooks for lakehouse-style workflows

## Deliverable

Create a data transformation notebook or script that:

- reads source data
- cleans and validates it
- aggregates it meaningfully
- writes a curated output dataset

