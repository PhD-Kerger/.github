# Research in Smart Cities with AI: Public Sharing Systems 🚗🚲

Welcome to the GitHub repository for my PhD research on **Smart Cities** with a focus on **AI-driven Public Sharing Systems** at the Chair of Artificial Intelligence at the University of Mannheim.

This repository contains code, data, and research related to optimizing and analyzing public sharing systems in the context of smart cities. The project leverages machine learning, optimization algorithms, and data analysis to improve public transportation, bike-sharing, and other shared resources within urban environments.

## Research Focus 🎯

The main objective of my research is to explore how AI technologies can enhance the efficiency, sustainability, and accessibility of public sharing systems. This includes:

- **Public Bike-Sharing Networks**
- **Traffic Analysis**
- **Demand Prediction**
- **Infrastructure Optimization**
- **User Behavior Analysis**

## Key Repositories 🔑

Here are the repositories related to my research:

### Infrastructure, Data Collection & Data Processing

#### [Main](https://github.com/PhD-Kerger/main)
Main Repository to setup development containers such as the TimescaleDB, OSRM, Kepler.gl, and Grafana instances. Further contains data loading and dumping scripts.

#### [GBFS-Go-Adapter](https://github.com/PhD-Kerger/gbfs-go-adapter)
JSON Schema definitions and Go language bindings for the General Bikeshare Feed Specification (GBFS).

#### [GBFS-Data-Collector](https://github.com/PhD-Kerger/gbfs-collector)
Data collection tool for gathering GBFS data from public bike-sharing systems into Parquet files.

#### [Nextbike-Data-Collector](https://github.com/PhD-Kerger/nextbike-collector)
Data collection tool for gathering data from Nextbike public bike-sharing systems into Parquet files.

#### [GTFS-Data-Collector](https://github.com/PhD-Kerger/gtfs-collector)
Data collection tool for gathering GTFS data from public transportation systems.

#### [Tier-Parquet-Compactor](https://github.com/PhD-Kerger/tier-parquet-compactor)
Data compaction tool for historical Tier e-scooter sharing system data files.

#### [Mobility-Alerter](https://github.com/PhD-Kerger/mobility-alerter)
A notification system for monitoring public mobility data and alerting on significant events or anomalies with Apprise.

#### [Data Pipelines](https://github.com/PhD-Kerger/data-pipelines)
Data pipelines for processing and transforming collected data into analysis-ready formats.

### Artifical Intelligence

#### [Trip Destination Prediction](https://github.com/PhD-Kerger/trip-destination-prediction)
Machine Learing approach to predict the destination coordinates of vehicles based on GBFS fields with XGBoost multi-target regression.

#### [Temporal-Knowledge-Graph O/D Location Linkage](https://github.com/PhD-Kerger/btg-bikeshare)
Temporal-Knowledge-Graph for Linking Micromobility O/D locations with Urban Context.

## Contact 📬

- Email: [daniel.kerger@students.uni-mannheim.de](mailto:daniel.kerger@students.uni-mannheim.de)
- ORCID: [0000-0003-3064-1637](https://orcid.org/0000-0003-3064-1637)
- GitHub: [DanielKerger](https://github.com/DanielKerger)
