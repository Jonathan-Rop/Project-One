## Sheduling data with Apache Airflow
# KWS-Dashboard<img width="901" height="429" alt="ETL" src="https://github.com/user-attachments/assets/d0e74051-b25b-48ec-86b3-e3729052abd5" />

<a name="readme-top"></a>

# <div align="center">SCHEDULING WITH AIRFLOW</div>

Following the previous project ideas trend, it is essential to include scheduling in data pipelines—whether ETL or ELT—since data can arrive and be processed on varying timelines. In this third project, I incorporated Apache Airflow (using Astronomer/Astro) to orchestrate and schedule the pipeline using Directed Acyclic Graphs (DAGs).

The pipeline follows the Extract-Transform-Load (ETL) structure, where raw data is extracted from an API source, loaded into a Bronze PostgreSQL table, transformed, and written into a Gold layer for analytical consumption. Airflow handles the orchestration of each task, ensuring that data movement, cleaning, and loading happen reliably and on schedule.

This project also demonstrates my understanding of containerization, as the pipeline is developed, deployed, and managed within Docker containers, allowing for reproducibility and portability. Additionally, the processed data is visualized in Grafana, providing real-time insights.

In this Project, I have sourced files from an open source data  (Health Data - oN diabetes), perfomed ETL processes using pyspark and visualization using Grafana:

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <ul>
    <li><a href=https://www.python.org/>PYTHON</a></li> 
  <li><a href="https://spark.apache.org/docs/latest/api/python/index.html)">PYSPARK</a></li>
    <li><a href="https://www.postgresql.org/">POSTGRESQL</a></li>
    <li><a href="https://grafana.com/">GRAFANA</a></li>

</ul>
###  Key Features <a name="key-features"></a>
- Perform transformations on provided Data
- Link the Gold layered data to a data warehouse
- perform SQL transformations
- Visualize with Grafana
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 💻 Getting Started with ETLs <a name="getting-started"></a>

To get a local copy up and running, follow these steps.


### Setup

Clone this repository to your desired folder:

> cd my-folder (Folder after filesare stored after cloning)
> git clone [git@github.comm: ETL.git](https://github.com/Jonathan-Rop/KWS-Dashboard.git)

### Prerequisites

To run this project you need:

- GitHub account;
- Editor of your choice(VS code)
- Git installed on your OS.

### Install

> [Linters](https://github.com/microverseinc/linters-config/tree/master/html-css-js)

- Installations required to run this project:

## Prerequisites
-  Install Python
-  Install PostgreSQL
-  Install Pandas
-  Spark and Java version 8
-  PostgreSQL/SQL

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
