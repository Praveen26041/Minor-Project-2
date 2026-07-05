# Minor-Project-2

# 🎬 Entertainment Content Segmentation Using K-Means Clustering

A Machine Learning project that groups Netflix movies and TV shows into meaningful clusters using the **K-Means Clustering** algorithm. The project demonstrates a complete unsupervised learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, evaluation, and visualization.

---

## 📌 Project Overview

Streaming platforms like Netflix contain thousands of movies and TV shows. Manually categorizing this content is challenging due to its scale and diversity.

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to automatically segment entertainment content based on features such as:

- Release Year
- Duration
- Content Type
- Rating

The generated clusters can be used to improve recommendation systems and better understand content patterns.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Feature Scaling
- K-Means Clustering
- Elbow Method for Optimal Clusters
- Silhouette Score Evaluation
- Cluster Visualization
- Export Clustered Dataset

---

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

**Source:** Kaggle

https://www.kaggle.com/datasets/shivamb/netflix-shows

### Dataset Features

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Load Dataset
2. Handle Missing Values
3. Remove Unnecessary Columns
4. Encode Categorical Features
5. Convert Duration into Numeric Values
6. Feature Scaling using StandardScaler
7. Apply K-Means Clustering
8. Determine Optimal Clusters using Elbow Method
9. Evaluate using Silhouette Score
10. Visualize Cluster Distribution
11. Save Clustered Dataset

---

## 📁 Project Structure

```
Entertainment-Content-Segmentation/
│
├── Entertainment_Content_Segmentation.ipynb
├── netflix_titles.csv
├── Entertainment_Content_Clusters.csv
├── PROJECT REPORT.pdf
├── README.md
└── requirements.txt
```

---

## 📈 Results

- Successfully segmented Netflix content into **5 clusters**
- Generated cluster labels for every movie and TV show
- Visualized cluster distribution
- Evaluated clustering quality using the **Silhouette Score**

The resulting clusters provide insights that can support:

- Content Recommendation Systems
- Personalized User Experience
- Content Analysis
- Business Intelligence

---

## 📷 Sample Visualizations

The notebook includes:

- Distribution of Release Year
- Duration Histogram
- Elbow Method Plot
- Cluster Scatter Plot
- Cluster Distribution

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Entertainment-Content-Segmentation.git
```

Move into the project directory

```bash
cd Entertainment-Content-Segmentation
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📦 Requirements

```
pandas
numpy
matplotlib
scikit-learn
jupyter
```

Install all dependencies using

```bash
pip install -r requirements.txt
```

---

## 📚 Future Improvements

- Use DBSCAN and Hierarchical Clustering for comparison
- Add Genre-based clustering
- Build an interactive recommendation system
- Deploy using Streamlit or Flask
- Integrate real-time Netflix data

---

## 👨‍💻 Author

**Praveen Kumar Dubey**

B.Tech CSE (AI & ML)

KIET Group of Institutions

---

## 📄 License

This project is intended for educational and learning purposes.
