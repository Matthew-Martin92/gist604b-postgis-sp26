# [Project Title]

**Student:** [YOUR NAME]
**Course:** GIST 604B – Open Source GIS
**Module:** [MODULE NUMBER AND NAME]
**University of Arizona**

## Project Description
[2–3 sentences describing what this project is about and what you built or analyzed.]

## Tools and Technologies
- [Tool 1, e.g. QGIS, PostGIS, GeoPandas, Leaflet]
- [Tool 2]
- [Tool 3]

## What I Did
[3–5 bullet points summarizing the key tasks completed in this assignment.]

## How to View / Run
[Instructions for viewing the project. For example:
- Link to live GitHub Pages site (if applicable)
- How to run a Python script
- How to open the map]

## Repository Structure
[Brief description of folders and key files]


# GIST 604B – PostGIS

Repository for working with spatial data using PostgreSQL and PostGIS.

## Repository Structure

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

- demos folder contains sql scripts discussed in the lectures.
- SQL files contain exercises and hints.
- Write and execute queries directly in the `sql/` files using the VS Code PostgreSQL extension.
- Data is downloaded and prepared inside the Codespace environment and is not stored in this repository.
- The database runs in a separate PostGIS container using Docker.
