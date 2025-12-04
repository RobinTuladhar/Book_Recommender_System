<h1 align="center">📚 Book Recommender System</h1>

<p align="center">
  <strong>An end-to-end collaborative filtering-based book recommendation system built using Python, Pandas, and Scikit-Learn, deployed with Streamlit.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-1.30-orange?logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Scikit--Learn-1.2.2-green?logo=scikitlearn&logoColor=white" alt="Scikit-Learn">
</p>

---

## 🔹 Project Overview

This project takes a dataset of books, users, and ratings, and recommends the **most relevant books** to a user using **collaborative filtering** techniques.  
A full **Streamlit web app** is included for interactive use.

🎥 **Watch the demo video:**  
[![Watch the demo](https://img.youtube.com/vi/[YOUR_VIDEO_ID](https://youtu.be/WmRwXHij4bI)/0.jpg)](https://youtu.be/[YOUR_VIDEO_ID](https://youtu.be/WmRwXHij4bI))



---

## 🧠 How It Works

1. **Data Preprocessing**  
   - Clean the datasets (`Books.csv`, `Ratings.csv`, `Users.csv`)  
   - Merge ratings and book metadata into a structured format

2. **Collaborative Filtering**  
   - Create a **user-item rating matrix**  
   - Compute similarity between users or items using **correlation or cosine similarity**  
   - Predict missing ratings to recommend books  

3. **Recommendation**  
   - For a selected user or book, return top recommended books  
   - Recommendations are based on patterns in **user behavior and ratings**  

---

## 📊 Dataset Used

- `Books.csv`  
- `Ratings.csv`  
- `Users.csv`  


---

## 🏗️ Project Structure

```text
Book Recommender System/
├── Untitled.ipynb          # Notebook for preprocessing & model building
├── Books.csv               # Dataset
├── Ratings.csv             # Dataset
├── Users.csv               # Dataset
├── app.py                  # Streamlit web app
├── .gitignore              # Ignore large model files
└── README.md               # Project documentation
