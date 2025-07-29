# 🎬 Netflix Titles Clustering

This project performs clustering on the Netflix Movies and TV Shows dataset from Kaggle to discover patterns and group similar content.

## 📊 Dataset
- Source: [Kaggle - Netflix TV Shows and Movies](https://www.kaggle.com/datasets/divyaraj2006/netflix-tv-shows-and-movies)
- Features: title, type, director, cast, country, date_added, rating, release_year, duration, genres, etc.

## 🔧 Steps
1. **Data Cleaning**  
   - Handled missing values  
   - Parsed duration, extracted year and month from `date_added`

2. **Feature Engineering**  
   - Encoded `type`, `rating`, and top genres from `listed_in`  
   - Normalized `release_year` and `duration`

3. **Clustering**  
   - Used `KMeans` on selected features  
   - Visualized clusters using `PCA` (2D)

## 🧠 Libraries
- `pandas`, `numpy`, `matplotlib`, `seaborn`  
- `scikit-learn`: `KMeans`, `StandardScaler`, `OneHotEncoder`, `PCA`

## 📌 Output
- Cluster assignments for each title
- 2D PCA scatter plot showing clusters

## Why not impress by out put 
- Low amount of data
