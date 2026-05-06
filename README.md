TuneSense: AI-Powered Audio Recommendation
🎵 Project Overview
An artificial intelligence and data science project aimed at building a music recommendation engine and analyzing audio characteristics using machine learning algorithms.

📂 Dataset Information
The project relies on the Spotify 2023 dataset, which includes:

Track Information: Track name, artist(s) name, and release date.

Streaming Metrics: Total streams, and appearances in playlists and charts across various platforms (Spotify, Apple Music, Deezer, Shazam).

Audio & Musical Features:

Beats Per Minute (bpm)

Danceability percentage (danceability_%)

Energy percentage (energy_%)

Valence/Positivity percentage (valence_%)

Musical mode (mode)

🛠️ Tools & Libraries Used
Python

Google Colab

Pandas & NumPy: For data manipulation and analysis.

Scikit-Learn: For machine learning modeling and preprocessing (StandardScaler).

Matplotlib & Seaborn: For data visualization.

⚙️ Workflow
Exploratory Data Analysis (EDA):

Inspecting the dataset and handling missing values.

Visualizing the distribution of audio features and the most-streamed tracks.

Data Preprocessing:

Converting categorical variables (e.g., mapping Major and Minor to numerical values 0 and 1).

Scaling features using StandardScaler for balanced numerical calculations.

Machine Learning Algorithms:

K-Means Clustering: To group similar songs based on their acoustic characteristics.

K-Nearest Neighbors (KNN): To measure similarity and recommend new songs based on user preferences.

🚀 How to Run
Upload the spotify-2023.csv file into your Google Colab environment.

Open the project notebook (.ipynb) in Google Colab.

Run the cells sequentially to execute the data preparation, clustering, and recommendation steps.

📊 Results
Developed a system capable of clustering and classifying musical tracks.

Provided accurate track recommendations based on rhythm and energy preferences.

Authors: Hala & Abdullah
