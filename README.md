## Twitter Data Pipeline

### Description

Ce mini projet consiste à mettre en place un pipeline de données avec Apache Airflow pour récupérer des données depuis l'API Twitter (X) et les stocker dans un bucket S3, utilisé comme Data Lake. Le pipeline automatise le processus de collecte, de transformation et de stockage des données (posts twitter) pour une analyse future.

### Prerequis

- Python 3.6+
- Docker

### Installation

```bash
    docker-compose up --build
```

### Références

- [Documentation Airflow](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html)