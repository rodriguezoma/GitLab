# Extraction et Transformation de Données avec Talend Open Studio.

## Projet ETL avec Talend Open Studio

## 🎯 Objectif
Extraire des données depuis :
- Un fichier CSV
- Une base MySQL
- Une base PostgreSQL source  
Transformer ces données, puis les charger dans une base PostgreSQL cible.  
Surveiller les performances via Grafana.

---

## 🛠️ Technologies utilisées
- **Talend Open Studio for Data Integration** (v8.0+)
- **MySQL** (source)
- **PostgreSQL** (source et cible)
- **Docker & Docker Compose** (pour les bases de données et Grafana)
- **Grafana + PostgreSQL** (monitoring)

---

## 📥 Procédure d’installation

### 1. Prérequis
- Docker et Docker Compose installés
- Talend Open Studio for DI installé localement (ou possibilité d’exécuter les jobs via script Java)
- Accès Internet

### 2. Lancer les bases de données et Grafana
```bash
cd projet-etl-talend
docker-compose up -d
