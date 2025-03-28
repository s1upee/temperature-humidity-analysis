# 🌡️ Temperature and Humidity Analysis

## 📌 Overview
This project focuses on the analysis of time-series sensor data for **temperature** and **humidity**, applying statistical methods, visualization techniques, and predictive modeling to extract meaningful insights. The dataset consists of sensor readings over time, allowing for trend exploration, anomaly detection, and machine learning applications.

## 🔬 Key Features
- **Data Cleaning & Preprocessing**: Handling missing values, type conversions, and preparing the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Generating insights through **visualizations**, including trend plots, histograms, and boxplots.
- **Anomaly Detection**: Identifying outliers using **Z-score** and **IQR method**.
- **Rolling Statistics**: Applying **rolling mean and standard deviation** for time-series smoothing.
- **Predictive Modeling**: Implementing **Linear Regression** to predict humidity based on temperature.
- **Future Predictions**: Estimating humidity values for unseen temperature data points.

## 📂 Dataset
The dataset contains **time-series sensor readings** recorded in an experimental setup. The primary columns include:
- **Time** – Timestamp of the recording.
- **Temperature** – Sensor-recorded temperature values.
- **Humidity** – Corresponding humidity measurements.
- **Experiment ID** – Identifier for experimental runs.

Stored in `Datasets/Data_Experiment_1/pi2.xlsx`.

## 🚀 Implementation Steps
1. **Data Cleaning** – Convert types, handle missing values, and prepare for analysis.
2. **EDA & Visualization** – Understand trends and distributions through visualizations.
3. **Anomaly Detection** – Identify and visualize outliers in temperature and humidity.
4. **Rolling Statistics** – Compute rolling means and standard deviations for time-series insights.
5. **Machine Learning Model** – Train a **Linear Regression** model to predict humidity from temperature.
6. **Future Predictions** – Extend the model to forecast humidity for new temperature values.

## 📊 Sample Visualizations

### Temperature & Humidity Trends
![Trend Graph](https://github.com/s1upee/temperature-humidity-analysis/blob/main/assets/trend_plot.png)

### Boxplot of Temperature and Humidity
![Boxplot](https://github.com/s1upee/temperature-humidity-analysis/blob/main/assets/boxplot.png)

### Linear Regression Prediction
![Regression](https://github.com/s1upee/temperature-humidity-analysis/blob/main/assets/regression.png)

### K-Means Clustering
![Clustering](https://github.com/s1upee/temperature-humidity-analysis/blob/main/assets/kmeans_clusters.png)

## 🛠️ Installation & Usage
To run this project locally:
```bash
# Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/temperature-humidity-analysis.git
cd temperature-humidity-analysis

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook
```

## 📖 Resources  
- 📂 **Dataset Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/466/gnfuv+unmanned+surface+vehicles+sensor+data+set+2)  
- 📜 **Documentation on pandas**: [pandas.pydata.org](https://pandas.pydata.org/)  
- 📊 **Seaborn for Data Visualization**: [seaborn.pydata.org](https://seaborn.pydata.org/)  
- 🤖 **Scikit-learn for Machine Learning**: [scikit-learn.org](https://scikit-learn.org/)  


## 🔗 Future Work
- **Expanding ML models** – Experimenting with advanced **time-series forecasting** techniques.
- **Interactive Dashboards** – Developing a **Streamlit** app for real-time data visualization.
- **Sensor Integration** – Testing the model with live IoT sensor data.

## 📜 License  
This project is licensed under the MIT License. The dataset is sourced from the **[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/466/gnfuv+unmanned+surface+vehicles+sensor+data+set+2)** and is available for research purposes.


---

📢 _This repository demonstrates strong analytical and technical skills in data science, visualization, and machine learning._

