# Tokyo Olympic Azure Data Engineering Project

A comprehensive data engineering and analytics project analyzing the **2020 Tokyo Olympics** dataset using **Azure services** and **Tableau** for visual insights.

## 🏗️ Project Architecture

The data engineering pipeline was designed using a suite of Azure services to ensure smooth ingestion, storage, transformation, and analysis of Tokyo Olympics data.

![Architecture Diagram](images/architecture.png)

## 📊 Project Overview

This project leverages a full Azure-based architecture to process and analyze data from the 2020 Olympics. It explores athlete participation, gender trends, and medal distribution using powerful cloud tools and data visualization.

## 🔧 Technologies Used

- **Azure Data Factory** – Data ingestion
- **Azure Data Lake Gen 2** – Scalable data storage
- **Azure Databricks (Apache Spark)** – Data cleansing, transformation, and analysis
- **Azure Synapse Analytics** – SQL-based advanced analytics
- **Tableau** – Interactive data visualization

## 🧾 Dataset

- Source: [Kaggle - 2021 Olympics in Tokyo Dataset](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)
- Files used:
  - `Athletes.csv`
  - `Coaches.csv`
  - `EntriesGender.csv`
  - `Medals.csv`
  - `Teams.csv`

## 📁 Project Structure

📦tokyo-olympic-azure-data-engineering-project
┣ 📊 Tableau Report (Tokyo_Olympic.twb)
┣ 📓 Jupyter Notebook (Tokyo Olympic Transformation.ipynb)
┣ 📁 Datasets (CSV files)
┗ 📄 README.md


## 📌 Key Insights

- Countries with the highest gold medal counts
- Gender participation across disciplines
- Mean number of entries by gender per discipline
- Medal distribution heatmaps and bar charts

## 🔍 Visualizations (Tableau)

- **Map-based medal distribution**
- **Stacked bar charts** for gender-based participation
- **Line charts** for average entries by gender

## 🚧 Limitations

- Dataset does not support real-time data
- Missing or inconsistent values required preprocessing
- Analysis is limited to 2020 Olympics (no historical comparison)

## 🔄 Future Enhancements

- Integrate real-time data pipelines
- Create a live dashboard using Power BI or Synapse
- Expand to multi-Olympic event analysis
- Include athlete performance and predictive modeling

## 📚 References

- Mishra, P. K., & Kumar, M. (2021). *Limitless Analytics with Azure Synapse*. Packt Publishing.
- Palacio, A. B. (2021). *Distributed Data Systems with Azure Databricks*. Packt Publishing.
- Stirrup et al. (2016). *Tableau: Creating Interactive Data Visualizations*. Packt Publishing.

---

**Author**: Pavan Kumar Muppala  
**Course**: COS80023 – Big Data (Swinburne University)  
**Date**: October 2024
