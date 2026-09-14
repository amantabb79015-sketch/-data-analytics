# Seasonal Agriculture Performance Analysis 🌾🌤️

**AICTE Major Project**

## 📌 Project Overview

Agricultural activities are strongly influenced by seasonal changes in
environmental conditions, farming practices, resource availability, and
market conditions. Because of these variations, agricultural performance
can differ from one season to another.

This project analyzes a comprehensive agricultural dataset to understand
these seasonal differences. The analysis identifies meaningful patterns,
trends, relationships, and variations across different seasons and
provides data-driven insights that can help improve farming practices
and resource allocation.

## 🎯 Problem Statement

Raw agricultural data does not clearly show how agricultural performance
changes across seasons or what patterns can be observed under different
seasonal conditions.

The main objective of this project is to analyze the dataset and
understand how **profitability, yield, water usage, input consumption,
and pest/disease risks** vary across the **Kharif, Rabi, and Zaid**
growing seasons.

## 📊 Dataset Details

-   **Size:** 3,880 cleaned farm records with 28 features
-   **Scope:** 8 Indian states and 8 major crops
-   **Seasons Covered:** Kharif, Rabi, and Zaid
-   **Key Features:** Profit (INR), Yield (Tonnes/Ha), Water Used (m³),
    Pesticide Usage (Litre/ha), Fertilizer Usage (kg/ha), and more

## 👥 Target Audience & End Users

-   **Farmers & Agronomists:** To choose suitable crops and seasons for
    better yield and profitability.
-   **Agricultural Policymakers & Government Bodies:** To support
    irrigation planning, subsidies, and efficient resource allocation.
-   **Agribusinesses & Agri-fintech Companies:** To evaluate crop and
    seasonal risks for insurance and lending decisions.
-   **Researchers & Agri-Tech Students:** To use the analysis as a
    reference for further data-driven agricultural studies.

## 🔍 Key Analysis Areas

The Jupyter Notebook explores several important aspects of agricultural
performance:

1.  **Profitability Across Seasons**\
    Comparing average profit margins generated in different seasons.

2.  **Crop Yield Trends**\
    Analyzing average agricultural output (Tonnes/Ha) across seasons.

3.  **Resource Usage vs. Output**\
    Evaluating average water consumption and its efficiency.

4.  **Resource Intensity Analysis**\
    Understanding the distribution and variation of water usage across
    seasons using boxplots.

5.  **Input Usage Analysis**\
    Comparing average pesticide and fertilizer consumption across
    different seasons.

6.  **Crop-Specific Performance & Environmental Risk**\
    Examining crop-level performance and environmental risk patterns in
    the full analysis.

## 🛠️ Technologies Used

-   **Language:** Python 3
-   **Data Manipulation:** Pandas, NumPy
-   **Data Visualization:** Matplotlib, Seaborn
-   **Environment:** Jupyter Notebook / Google Colab

## 🚀 Setup and Execution

To run this notebook on Google Colab:

1.  Upload the `seasonal_agriculture_performance_dataset.csv` file to
    your Google Drive.
2.  Open the `.ipynb` notebook in Google Colab.
3.  Run the cell that mounts your Google Drive:

``` python
from google.colab import drive
drive.mount('/content/drive')
```

4.  Update the dataset path in the `pd.read_csv()` function to match
    your Google Drive directory structure. For example:

``` python
df = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/seasonal_agriculture_performance_dataset.csv')
```

5.  Run all cells sequentially to view the analysis and visualizations.

## 🔮 Future Scope

-   Integrate real-time weather and market-price APIs for live seasonal
    forecasting.
-   Build a Machine Learning model to recommend the optimal crop and
    season for a specific farm.
-   Extend the analysis to additional states and use multi-year data for
    long-term trend forecasting.
-   Develop an interactive dashboard, such as using Power BI or
    Streamlit, for farmers and policymakers.
-   Incorporate soil-health and satellite-imagery data for deeper
    environmental insights.

## 👤 Author

**Mohammed Sulaiman Adnan**

**College:** Mahaveer Institute of Science & Technology
