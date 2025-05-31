# 🚀 IBM Data Science Capstone Project – SpaceX Launch Analysis

## 📋 Project Overview

This capstone project was developed as the final assignment of the **IBM Data Science Professional Certificate**. The goal of this project is to apply data science tools and methodologies to analyze and predict the outcomes of **SpaceX Falcon 9** rocket launches. This end-to-end data science project includes:

- Data Collection (API, Web Scraping, CSV)
- Data Wrangling & Processing
- Exploratory Data Analysis (EDA)
- Interactive Visual Analytics with Plotly Dash and Folium
- Predictive Modeling using Machine Learning

## 🔍 Problem Statement

SpaceX advertises significantly lower launch costs by reusing Falcon 9 rocket boosters. Accurately predicting whether a first-stage booster will land successfully can lead to more efficient mission planning and cost management.

The objective is to **predict the success of Falcon 9 first stage landings** using historical data and machine learning models.

## 📂 Repository Structure

```
📦spacex-launch-analysis
 ┣ 📁 notebooks/
 ┃ ┣ SpaceX_API_calls.ipynb
 ┃ ┣ Web_Scraping_MissionData.ipynb
 ┃ ┣ Data_Wrangling.ipynb
 ┃ ┣ EDA_Visualization.ipynb
 ┃ ┣ SQL_Analysis.ipynb
 ┃ ┣ Folium_Maps.ipynb
 ┃ ┣ Plotly_Dash_Dashboard.ipynb
 ┃ ┗ Predictive_Modeling.ipynb
 ┣ 📁 images/
 ┣ 📁 data/
 ┣ 📄 spacex-dash-app.py
 ┣ 📄 presentation.pdf
 ┣ 📄 README.md
 ┗ 📄 requirements.txt
```

## 🧰 Technologies Used

- **Python 3.11+**
- **Pandas, Numpy**
- **Plotly, Dash, Seaborn, Matplotlib**
- **Folium (Geospatial visualization)**
- **Scikit-learn (Machine Learning)**
- **BeautifulSoup, Requests (Web scraping)**
- **PostgreSQL & SQL Magic**
- **Jupyter Notebooks**

## 📈 Key Features

- 🌐 **Data Sourcing** via SpaceX REST APIs and HTML web scraping
- 🧼 **Data Wrangling** with multi-source integration and cleaning
- 📊 **EDA** with visual and statistical insights
- 🌍 **Interactive Mapping** with Folium for launch sites & proximity analysis
- 📉 **Classification Models** including Logistic Regression, SVM, Decision Tree, and KNN
- 📊 **Plotly Dash Dashboard** for real-time user interaction
- ✅ **Best Model Performance**: Achieved using GridSearchCV with cross-validation

## 🧪 Model Evaluation

| Model              | Test Accuracy |
|-------------------|---------------|
| Logistic Regression | 0.93          |
| Support Vector Machine (SVM) | 0.94          |
| Decision Tree      | 0.92          |
| K-Nearest Neighbors | 0.89          |

The **SVM classifier** performed the best with the highest accuracy on test data.

## 📁 Dataset Sources

- **SpaceX Launch Data API** – [`https://api.spacexdata.com`](https://api.spacexdata.com)
- **Wikipedia Launch History** – Scraped using BeautifulSoup
- **CSV Files** provided via Coursera’s cloud storage

## 🖥️ Dashboard Deployment

Launch the dashboard with:

```bash
python spacex-dash-app.py
```

Access the interactive dashboard at `http://127.0.0.1:8050/`.

## 🎯 Project Presentation

The final presentation is available here:  
📄 [`presentation.pdf`](./presentation.pdf)

## 🔗 License

This project is submitted as part of IBM’s Data Science Capstone on Coursera and is intended for educational purposes.

## 🙌 Acknowledgements

- IBM Skills Network Team
- Coursera
- SpaceX Public API
- Wikipedia Contributors