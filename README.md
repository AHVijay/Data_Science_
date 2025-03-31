# 🎬 Netflix Movies and TV Shows Analysis

## 📌 Project Summary

The aim of this project is to analyze the Netflix dataset of movies and TV shows available until 2019, sourced from the third-party search engine Flixable. The goal is to group the content into relevant clusters using Natural Language Processing (NLP) techniques to enhance the user experience through a recommendation system. This will help prevent subscriber churn for Netflix, which currently has over 220 million subscribers. 📊

Additionally, the dataset is analyzed to uncover insights and trends in the streaming entertainment industry. 🎥

## 🔍 Project Workflow

The project follows a structured step-by-step process:

1. **Handling Missing Values**
   - 🛠 Cleaning and filling null values to maintain data integrity.
   
2. **Managing Nested Columns**
   - 📂 Processing nested columns such as `director`, `cast`, `listed_in`, and `country` to improve visualization and analysis.

3. **Binning the Rating Attribute**
   - 📊 Categorizing ratings into groups: `adult`, `children's`, `family-friendly`, and `not rated` to enhance interpretability.

4. **Exploratory Data Analysis (EDA)**
   - 🔬 Gaining insights into factors that may contribute to subscriber churn.
   - 📈 Identifying trends in content popularity and distribution.

5. **Feature Engineering for Clustering**
   - 🎭 Using attributes such as `director`, `cast`, `country`, `genre`, `rating`, and `description`.
   - ✂️ Tokenizing, preprocessing, and vectorizing text data using the TF-IDF vectorizer.

6. **Dimensionality Reduction**
   - ⚡ Applying Principal Component Analysis (PCA) to reduce dimensionality and improve model performance.

7. **Clustering Techniques**
   - 🧩 Implementing **K-Means Clustering** and **Agglomerative Hierarchical Clustering**.
   - 📌 Determining optimal cluster numbers:
     - **K-Means:** 4 clusters 🎯
     - **Hierarchical Clustering:** 2 clusters 🏗
   - 🏆 Evaluating clusters using silhouette scores and other validation techniques.

8. **Developing a Content-Based Recommender System**
   - 🔍 Utilizing a **cosine similarity matrix** to provide personalized recommendations based on clustered content.
   - 🚀 Aiming to reduce subscriber churn by enhancing user satisfaction and engagement.

## 🎯 Expected Outcomes

- A **well-defined clustering model** for Netflix content. 🎬
- A **recommendation system** that improves user experience and retention. 🤖
- Key **insights into streaming trends** and subscriber engagement. 📊
- Enhanced **decision-making for content curation** to cater to diverse audiences. 🎯

## 🛠 Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, NLTK, SciPy) 🐍
- **Natural Language Processing (NLP)** (TF-IDF Vectorization) 📚
- **Machine Learning** (K-Means, Hierarchical Clustering, PCA) 🤖
- **Recommendation Systems** (Cosine Similarity Matrix) 🔄
- **Data Visualization** (Seaborn, Matplotlib) 📊

## ✅ Conclusion

This comprehensive analysis and recommendation system are expected to enhance user satisfaction, leading to improved retention rates for Netflix. By clustering similar content and delivering personalized recommendations, Netflix can offer a better viewing experience and reduce subscriber churn. 🎥🚀
