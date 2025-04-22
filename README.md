# Movie_watch

# 🎬 Movie Watch Pattern Clustering

This project performs unsupervised machine learning to cluster users based on their movie-watching behavior. It uses KMeans clustering on features such as watch time, genre preference, and average rating behavior.

---

## 📁 Dataset

**File**: `movie_watch.csv`  
**Columns**:
- `watch_time_hour` - Hour of the day the user watches movies (0-23)
- `genre_preference` - User's favorite genre (e.g., comedy, thriller)
- `avg_rating_given` - Average rating the user gives to movies (scale of 1-5)

---

## 🔍 Objective

To identify user groups with similar viewing behaviors for insights like:
- Better content recommendation
- Personalized notifications
- Targeted marketing

---

## 🧠 Methodology

1. **Data Preprocessing**
   - Label encoding for genres
   - Feature scaling using StandardScaler

2. **Clustering**
   - KMeans with 3 clusters

3. **Dimensionality Reduction**
   - PCA for visualization in 2D

4. **Visualization**
   - Scatter plot using Seaborn

---

## 📌 Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

Install dependencies:
```bash
pip install pandas scikit-learn matplotlib seaborn
```

---

## 🚀 How to Run

1. Place `movie_watch.csv` in your working directory.
2. Run the Python script `movie_watch_clustering.py`.
3. The output will display a 2D scatter plot of the clusters.

---

## 📈 Output

- 3 user clusters visualized using PCA.
- Each point represents a user, color-coded by their assigned cluster.

---

## 📚 References / Credits

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)

---

## ✍️ Author

- *[Your Name Here]*
- April 2025
