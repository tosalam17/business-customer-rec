# Business Customer Recommendation System

This project builds a recommendation system using collaborative filtering on the Amazon Electronics ratings dataset. The system suggests products to users based on their historical preferences and similarities to other users or items.

## 📂 Project Overview

The notebook walks through the full pipeline of building a recommender system:

- Loading and preprocessing the Amazon ratings dataset
- Filtering sparse user-item interactions
- Constructing a utility matrix
- Implementing:
  - **User-Based Collaborative Filtering** using cosine similarity
  - **Item-Based Collaborative Filtering**
- Generating top-N recommendations for selected users
- Visualizing user-product matrices

## 🧠 Key Techniques

- **Cosine Similarity** for user-user and item-item similarity
- **Sparse Matrix Handling** to improve scalability
- **Top-K Filtering** to recommend relevant items
- **Pivot Tables** to construct user-item matrices

## 📊 Dataset

- **Source**: Amazon Product Ratings (Electronics category)
- **Format**: CSV file with `userId`, `productId`, and `rating`

> Note: Due to the large size of the original dataset, a sample may be used for demonstration purposes.

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

## 🚀 Running the Project

1. Clone the repository or download the notebook.
2. Place the dataset (`ratings_Electronics.csv`) in the same directory.
3. Open and run the notebook:
   ```bash
   https://github.com/tosalam17/business-customer-rec/blob/main/Recommendation_Systems_Learner_Notebook_Full_Code.ipynb
