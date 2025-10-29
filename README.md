# 🎶 Spotify & YouTube Music Trend Analysis

## 🎯 Project Overview

This project analyzes music performance metrics from the **Spotify & YouTube Music Dataset** to uncover trends in song popularity, platform usage, and track characteristics across both major streaming platforms.

The analysis is conducted using **Python** in a Jupyter Notebook, leveraging data manipulation with **Pandas** and visualization with **Matplotlib** and **Seaborn**.

---

## 💾 Data Source and Attribution

The dataset used for this analysis was sourced from **Kaggle**:

* **Dataset Name:** Spotify Youtube Data
* **Author:** Rohit Grewal
* **Link:** [https://www.kaggle.com/datasets/rohitgrewal/spotify-youtube-data/data](https://www.kaggle.com/datasets/rohitgrewal/spotify-youtube-data/data)

---

## 🛠️ Technologies Used

* **Python 3.x**
* **Pandas**: For data cleaning, manipulation, and aggregation (`df_mean_melted`, `track_likes_to_views`, etc.).
* **Seaborn** & **Matplotlib**: For creating comprehensive visualizations (Bar Plots, Pie Charts, and the Correlation Heatmap).
* **Jupyter Notebook**: The primary environment for analysis and presentation (`Spotify_Youtube_analysis.ipynb`).

---

## 📊 Dataset Features

The analysis utilizes a combined dataset featuring metrics from Spotify and YouTube. Key columns analyzed include:

| Feature | Description | Analysis Focus |
| :--- | :--- | :--- |
| **Stream** | Total number of times the song was streamed on **Spotify**. | Popularity and Correlation. |
| **Youtube Views, Likes, Comments** | Engagement metrics for the track on **YouTube**. | Engagement ratios and Channel performance. |
| **Album\_type** | Type of the track release (`album`, `single`, `compilation`). | Comparative analysis of engagement averages. |
| **Danceability** | A score (0 to 1) indicating suitability for dancing. | Track/Album characteristic ranking. |

---

## 💡 Analysis Questions Answered (Q.1 - Q.9)

The Jupyter Notebook provides a complete solution for the following nine business and analytical questions:

### I. Platform Popularity & Engagement Analysis
* **Q.1:** Top 10 Artists - with the Highest **Views** on YouTube.
* **Q.2:** Top 10 Tracks - with the Highest **Streams** on Spotify.
* **Q.5:** Top 5 YouTube Channels - based on the **Views**.
* **Q.6:** The Top Most Track - based on **Views**.
* **Q.7:** Which Top 7 Tracks have the highest **Like-to-View ratio** on YouTube?

### II. Track & Album Characteristic Analysis
* **Q.3:** What are the most common **Album Types** on Spotify? How many tracks belong to each album type?
* **Q.4:** How do the **Average Views, Likes, and Comments** compare between different **Album Types**?
* **Q.8:** Top Albums having the Tracks with maximum **Danceability**.

### III. Correlation Study
* **Q.9:** What is the **Correlation** between Views, Likes, Comments, and Stream?

---

## 📈 Key Visualizations

The analysis is supported by targeted visualizations to interpret key findings:

1.  **Album Type Distribution:** A **Pie Chart** illustrating the proportion of `album`, `single`, and `compilation` tracks.
2.  **Average Engagement Comparison:** A **Grouped Bar Plot** (using `sns.barplot`) comparing the average metrics across the different `Album_type` categories.
3.  **Correlation Matrix:** A **Heatmap** (using `sns.heatmap`) clearly showing the correlation coefficients between the core metrics (`Views`, `Likes`, `Comments`, `Stream`).

---

## 📁 Repository Structure

* `Spotify Youtube Dataset.csv`: The dataset used for the analysis (required for running the notebook).
* `Spotify_Youtube_analysis.ipynb`: The main Jupyter Notebook containing all the code, analysis steps, and output tables/visualizations.


