# Notebooks Overview

This folder contains all analytical notebooks developed for the **NorthStar Urban Mobility and Logistics Analytics Project**. Each notebook focuses on a specific stage of the data analysis and system development process.

---

## 📂 Notebook Structure

### 1. 01_sql_in_r.ipynb
This notebook uses SQL queries executed within R (via the `sqldf` package) to analyse structured operational data.  
It focuses on identifying key issues such as delivery failures, delays, and performance differences across hubs and zones.

---

### 2. 02_r_analytics.ipynb
This notebook performs statistical analysis and data manipulation using `dplyr`, along with visualisation using `ggplot2`.  
It uncovers patterns and trends that are not easily visible through SQL queries alone.

---

### 3. 03_python_processing.ipynb
This notebook handles data processing, transformation, and additional analysis using Python.  
It is used for cleaning, preparing datasets, and generating insights through Python-based tools and visualisations.

---

### 4. 04_mongodb_development.ipynb
This notebook focuses on designing and implementing a MongoDB Atlas NoSQL database.  
It models complex, semi-structured data such as complaints, delivery incidents, and app events using document-based structures.

---

## 🎯 Purpose

The notebooks together provide a complete analytics workflow, combining:
- SQL-based querying
- Statistical analysis
- Data processing
- NoSQL database design

This integrated approach supports better understanding of operational inefficiencies and enables data-driven decision-making for NorthStar.

---

## ⚙️ Tools & Technologies

- R (sqldf, dplyr, ggplot2)
- Python
- MongoDB Atlas
- Google Colab

---

## 📌 Notes

- All datasets are loaded from Google Drive or the `/data` folder.
- Each notebook is designed to be run independently but contributes to the overall analysis.

