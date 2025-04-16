# 🔗 Data Pipeline for Integrating Legislative, Academic, and Public Health Datasets

This project showcases a full-stack data pipeline that ingests, processes, and analyzes heterogeneous datasets from three domains: legislative debates (Oireachtas API), academic course catalogs (WSU XML), and public health data (CDC JSON). It emphasizes seamless integration of structured and semi-structured data using modern data engineering and visualization tools.

## 📌 Project Objectives

- Ingest semi-structured data (JSON, XML) into MongoDB.
- Transform, clean, and normalize data using Python and Pandas.
- Load processed data into PostgreSQL for structured querying.
- Perform exploratory data analysis and basic machine learning (clustering).
- Build an interactive dashboard using Dash for user-friendly insights.

## 🧰 Technologies Used

- **Languages & Libraries**: Python, Pandas, Seaborn, Plotly, Dash, xml.etree, requests
- **Databases**: MongoDB (NoSQL), PostgreSQL (SQL)
- **Visualization Tools**: Plotly, Dash, Seaborn
- **APIs & Datasets**:
  - [Oireachtas Open Data API](https://api.oireachtas.ie/v1/debates)
  - [WSU Course XML Data](https://aiweb.cs.washington.edu/research/projects/xmltk/xmldata/data/courses/wsu.xml)
  - [CDC Public Health Data](https://data.cdc.gov/api/views/9j2v-jamp/rows.json)


## 📊 Visualizations & Analysis

- **Oireachtas**:
  - Time-series of speaker activity
  - Debate type distributions
  - Correlations between speaker count and speech length

- **WSU Courses**:
  - Violin plots for credit-hour vs. seat limits
  - Heatmaps for academic resource distribution

- **CDC**:
  - Clustering health estimates by age and year
  - Yearly trends of disease estimates

## 📈 Dashboard Preview

The dashboard, built using Dash and Plotly, includes:
- Filters for domain-specific data exploration
- Real-time interactive charts
- Summary statistics and cross-domain insights

  
## 🔍 Key Takeaways

- Demonstrates integration of multi-format, multi-domain datasets

- Highlights benefits of hybrid NoSQL + SQL architecture

- Offers reusable ETL templates and visual storytelling for public data

## 🚀 Future Work

- Add sentiment analysis for debates

- Enable real-time data ingestion using Kafka

- Expand machine learning with supervised models

- Integrate cross-domain data linkage (e.g., policy impacts on public health)
