# 📚 Book Recommendation System (Machine Learning Project)

## 📖 Overview
This project implements a **Book Recommendation System** using **Collaborative Filtering (CF)** techniques, specifically the **K-Nearest Neighbors (KNN)** algorithm.  
The goal is to suggest books to users based on their interests, past ratings, and similarities between books or users.  

Recommendation systems are widely used in platforms like **Amazon, Goodreads, and Netflix** to enhance user experience by providing personalized suggestions.

---

## ⚙️ Project Features
- Uses **Item-based KNN** for recommendations (more stable than user-based KNN).
- Predicts ratings for books based on similarity measures (Euclidean distance).
- Provides personalized book suggestions.
- Includes **data preprocessing, feature engineering, and visualization**.
- Implements **Random Forest Classifier** for classification tasks.
- Demonstrates how recommendation systems can be built using Python and ML libraries.

---

## 🛠️ Tech Stack
- **Language**: Python 3.6+
- **Libraries**:
  - `numpy` (1.22.4)
  - `pandas` (1.5.0)
  - `scikit-learn` (1.1.1)
  - `seaborn`
  - `matplotlib`

---

## 📂 Dataset
- The dataset contains book details such as:
  - Title
  - Author
  - Ratings
  - Language
  - Number of pages
- Ratings are used to build similarity measures and generate recommendations.

---

## 🚀 Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/bathul2005/Book-Recommendation.git
   cd Book-Recommendation
