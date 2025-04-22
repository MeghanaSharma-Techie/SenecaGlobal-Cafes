# SenecaGlobal-Cafes
Databricks ETL Project using Google Maps API to fetch nearby cafes around Seneca Global.

# Seneca Global Cafes ETL Project ☕️

## 📌 Project Summary
This project fetches nearby cafes around Seneca Global's location using Google Maps Places API via RapidAPI.

## 🛠️ Tech Stack
- Databricks Community Edition
- Python, PySpark, Pandas, SQL
- Google Maps API (RapidAPI)

## 📍 Coordinates Used
Seneca Global: `17.434848, 78.376755`

## 🔄 ETL Process
- **Extract**: Data from API
- **Transform**: Process & format in Pandas
- **Load**: Save to Spark SQL table

## 📈 Output
You can query the `Nearby_SenecaGlobalCafes` table in SQL.

## 📦 Dataset
Dynamic, fetched via API – no static CSV used.
