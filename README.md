# 🌙 TuneSense: Advanced AI-Powered Music Analytics & Prediction 🎵

> **"Where Data Science meets the rhythm of the soul."**

## ✨ Project Overview
**TuneSense** is a comprehensive Data Science and Artificial Intelligence project designed to explore, classify, and predict music trends. Using the **Spotify 2023** dataset, we built a multi-stage pipeline that goes beyond simple recommendations to include predictive modeling and deep statistical analysis of audio characteristics.

---

## 📂 Dataset Insights
The project utilizes the **Most Streamed Spotify Songs 2023** dataset, focusing on:
* **Streaming Power:** Total streams and platform presence (Apple Music, Deezer, Shazam).
* **Audio DNA:** BPM, Danceability %, Energy %, Valence %, and Acousticness %.
* **Musical Structure:** Key and Mode (Major/Minor).

---

## 🛠️ Tech Stack
* **Language:** Python 🐍
* **Environment:** Google Colab ☁️
* **Data Wrangling:** Pandas & NumPy
* **Machine Learning (Scikit-Learn):** * `LinearRegression` for stream prediction.
    * `KMeans` for audio clustering.
    * `KNeighborsClassifier` & `GaussianNB` for mode classification.
* **Visualization:** Matplotlib & Seaborn 📊

---

## ⚙️ Advanced Workflow

### 1. Exploratory Data Analysis (EDA) 🔍
* Detailed cleaning and handling of missing values.
* Correlation heatmaps to find relationships between "Energy" and "Streams".

### 2. Predictive Modeling (Supervised Learning) 📈
* **Linear Regression:** Built a model to predict the number of streams based on a song's audio features.
* **Performance Metrics:** Evaluated using MAE, MSE, and RMSE.

### 3. Classification & Logic ⚖️
* **KNN & Naive Bayes:** Implemented these algorithms to classify tracks into their musical modes (Major/Minor) with high accuracy.

### 4. Unsupervised Learning (Clustering) 🌌
* **K-Means Clustering:** Grouped thousands of songs into unique "Music Moods" using the **Elbow Method** to find the optimal number of clusters.

---

## 🚀 How to Use
1.  Clone this repository.
2.  Upload `spotify-2023.csv` to your environment.
3.  Open the `.ipynb` notebook in **Google Colab**.
4.  Run all cells to witness the magic of AI! 🌙

---

## 📊 Final Results & Conclusion
* Successfully predicted song popularity trends using regression.
* Achieved clear segmentation of music styles through clustering.
* Demonstrated that technical audio features (like Danceability) are strong predictors of a song's global success.

***

### 👥 Authors
* **Hala Alkhawaldeh** 🌙 (Lead AI & Data Science Developer)
* **Abdalla Sharqawi** (Academic Collaborator)

---
<p align="center">
  <i>"Always aim for the moon. If you miss, you may hit a star."</i> 🌙✨
</p>
