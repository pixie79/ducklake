## Overview
This repository contains materials for a blog post demonstrating the integration between Unity Catalog and DuckDB. The examples provided showcase how to use DuckDB with Unity Catalog for data management and querying.  
Repository Structure
Dockerfile.nginx: Dockerfile for setting up an NGINX server.
notebooks/duckdb.ipynb: Jupyter notebook demonstrating SQL operations with DuckDB and Unity Catalog.
notebooks/dbt.ipynb: Jupyter notebook demonstrating the use of dbt (data build tool) with DuckDB and Unity Catalog.
requirements.txt: List of dependencies required for running the notebooks and examples.

## Prerequisites
- Docker
- Docker Compose

## Setup
- Clone the repository:  
```bash
git clone <repository-url>
```



## Usage
To run the example, execute the following command:  
```bash 
docker compose up --build -d 
```
After starting the Docker containers, you can access the Jupyter notebooks at http://localhost:8888/lab?token=ducklake. The notebooks demonstrate how to use DuckDB with Unity Catalog for data management and querying.

Open the notebooks:  
- Navigate to notebooks/dbt.ipynb to see dbt operations with DuckDB and Unity Catalog.
- Navigate to notebooks/duckdb.ipynb to see SQL operations with DuckDB and Unity Catalog.

You can reach the Unity Catalog at http://localhost:8080/api/2.1/unity-catalog.
You can reach the Unity Catalog UI at http://localhost:3000