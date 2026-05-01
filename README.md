# PostGIS

**Student:** Matthew Martin  
**Course:** GIST 604B – Open Source GIS  
**Module:** Module 4: PostGIS Database Orchestration  
**University of Arizona**  

## Project Description
This project is a repository for working with spatial data using PostgreSQL and PostGIS. There are to help teach how to use SQL queries on example GIS datasets. Then I used the sql files from the sql folder to create my own SQL queries to find the information or satisfy the workflow needed for each topic.

## Tools and Technologies
- SQL Queries
- PostGIS
- PostgreSQL

## What I Did
- Set up a PostGIS-enabled PostgreSQL database using Docker
- Import spatial datasets into a database environment
- Wrote and executed queries using VS Code PostgreSQL extension for the following:
    - basic sql queries
    - queries to see the geometry of datasets
    - spatial relationship queries
    - spatial joins to join tables together


## How to View / Run
- Open in codespaces and set up a PostGIS-enabled PostgreSQL database using Docker.
- Import spatial datasets into a database environment.
- Run the code in each of the sql files to receive each output and visualization

## Repository Structure
The demos folder contains demonstration sql scripts to help learn the structure of sql queries. The sql folder contains custom queries that satify each of the the four topics used in the module.

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   └── Dockerfile
    ├── sql/
    │   ├── 01_basic_sql_queries.sql
    │   ├── 02_geometry_queries.sql
    │   ├── 03_spatial_relationships.sql
    │   └── 04_spatial_joins.sql
    ├── demos/
    │   ├── demo_aggregation_queries.sql
    │   ├── demo_basic_queries.sql
    │   ├── demo_filtering_queries.sql
    │   └── demo_postgis_queries.sql
    └── docker-compose.yml

## Notes

- 
- SQL files contain exercises and hints.
-
