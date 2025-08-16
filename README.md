# 🎵 Music Recommendation System

## 📌 Overview
This project implements a **content-based music recommendation engine** that suggests similar songs to a given track.  
It uses **TF-IDF vectorization** and **cosine similarity** on song metadata (genre, artist, and track name) to recommend the top-N most relevant songs.  

The project includes **exploratory data analysis (EDA)** for understanding the dataset, as well as a recommendation pipeline with visualization of results.

---

## 🚀 Features
- Analyzes and visualizes the distribution of **genres** and **top artists**.  
- Combines **genre, artist name, and track name** into a unified feature space.  
- Uses **TF-IDF** to convert textual features into numerical vectors.  
- Computes **cosine similarity** between tracks for recommendation.  
- Provides **top-10 song recommendations** for any given input song.  
- Visualizes recommended songs with **Matplotlib/Seaborn**.  

---

## 📂 Dataset
- The dataset used: `tcc_ceds_music.csv`  
- Contains metadata about songs, including **track name, artist name, and genre**.  
- Ensure this file is in the working directory before running the notebook.  

---

## ⚙️ Technologies Used
- **Python**  
- **Pandas** for data handling  
- **Matplotlib / Seaborn** for visualization  
- **Scikit-learn** for TF-IDF vectorization and similarity computation  

---

## ▶️ Usage
1. Clone this repository or download the notebook.  
2. Place `tcc_ceds_music.csv` in the same directory.  
3. Open and run the notebook:  

```bash
jupyter notebook Music_recommendation_system.ipynb
