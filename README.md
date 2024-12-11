# ⚡ WattSolution

WattSolution is a cutting-edge machine learning project designed to **optimize residential energy consumption** through predictive modeling and anomaly detection. By leveraging Pecan Street energy data, this repository explores how data-driven solutions can enhance energy efficiency and identify potential issues in residential energy usage.

---

## 📑 Table of Contents
- [🚀 Project Overview](#-project-overview)
- [📁 Repository Structure](#-repository-structure)
- [📊 Data](#-data)
- [⚙️ Setup](#️-setup)
- [📌 Usage](#-usage)
- [✨ Results](#-results)
- [🤝 Contributing](#-contributing)

---

## 🚀 Project Overview

WattSolution focuses on three primary goals:
1. **🔍 Outlier Detection**: Identifying anomalies in energy consumption data to uncover unusual patterns or errors.
2. **📈 Energy Consumption Prediction**: Developing models to forecast future energy usage based on historical trends, weather conditions, and other factors.
3. **🌟 WattWise**: Creating an advanced AI-based dashboard using Streamlit to provide users with actionable insights into energy consumption patterns. The dashboard offers:
   - **📊 WattVision**: Interactive visualizations of energy usage trends and patterns.
   - **🤖 WattBot**: An intelligent assistant powered by AI for answering user queries and providing tailored energy-saving tips.

This project integrates energy consumption and weather data to build an efficient pipeline, paving the way for actionable insights into energy usage patterns. It aims to assist researchers, energy providers, and households in understanding and optimizing their energy consumption.

---

## 📁 Repository Structure

- **`data/`**: Contains all datasets used in the project.
  - **`raw/`**: Original, unprocessed energy and weather data.
  - **`processed/`**: Cleaned and merged datasets ready for analysis.
- **`models/`**: Stores the trained machine learning models from the prediction pipeline.
- **`notebooks/`**: Includes Jupyter notebooks for each step of the pipeline:
  - `00-data_processing.ipynb`: Data cleaning and feature engineering.
  - `01-data_exploration.ipynb`: Exploratory data analysis.
  - `03-energy_prediction.ipynb`: Model training and validation for energy consumption predictions.
  - `04-new_vs_old_datasets.ipynb`: Comparison of predictions for new versus old datasets.
  - `05-run_streamlit.ipynb`: Prepares and launches the Streamlit app.
- **`streamlit_app/`**: Contains the Streamlit application for interactive data visualization and insights.

---

## 📊 Data

The project uses Pecan Street's anonymized residential energy data. The data is organized into two main folders:
- **Raw Data (`data/raw/`)**: Unprocessed energy and weather data files.
- **Processed Data (`data/processed/`)**: Cleaned and combined datasets prepared for analysis and modeling.

### 🌐 Data Source
The energy data is sourced from [PecanStreet](https://www.pecanstreet.org/), a provider of anonymized residential energy data for research purposes.

---

## ⚙️ Setup

To use this repository, you will need to run the notebooks in sequential order, which mimics how a pipeline works without automated triggers. Ensure the following setup:
1. Install **Python 3.8+**.
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt


## 📌 Usage

# Step 1: Run the notebooks in order to execute the pipeline:
1. 00-data_processing.ipynb: Perform data cleaning and feature engineering.
2. 01-data_exploration.ipynb: Conduct exploratory data analysis.
3. 03-energy_prediction.ipynb: Train and validate energy consumption models.
4. 04-new_vs_old_datasets.ipynb: Compare predictions between old and new datasets.
5. 05-run_streamlit.ipynb: Prepare the Streamlit app for interactive visualization.

# Step 2: Launch the Streamlit app for visualization and AI-powered insights:
cd streamlit_app
streamlit run WattWise.py

## ✨ Results
# Key outputs of the project:
1. Anomaly detection insights for identifying unusual energy usage.
2. Predictive models for forecasting energy consumption.
3. Visualizations through the Streamlit app (WattVision).
4. AI-powered insights and recommendations via WattBot.