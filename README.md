# Projet Data Pipelines DSIA

## Objectif
Plateforme de pipelines de données e-commerce pour l'ingestion en temps réel et le traitement batch.

## Stack Technique
- **Ingestion**: Kafka (Stream Producer & Anomaly Detector)
- **Stockage**: PostgreSQL & MinIO
- **Orchestration**: Airflow
- **Analyse**: Marimo / Jupyter
- **Déploiement**: Docker Compose

## Installation
1. `docker-compose up -d`
2. Lancez `python producers/stream_producer.py` pour alimenter le flux.
3. Surveillez les alertes sur le topic Kafka `alerts`.