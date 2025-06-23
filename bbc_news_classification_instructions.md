# 📌 Peer Review Instructions

This week's Peer Review has two parts.

---

## 🧪 Part 1: Kaggle Mini-Project [80 pts]

You will participate in the following Kaggle competition:  
👉 [**Kaggle Competition: BBC News Classification**](https://www.kaggle.com/c/learn-ai-bbc/overview)

This competition is about categorizing news articles. You will use matrix factorization to predict categories and submit your notebook for peer evaluation.

You must submit **one deliverable**:
- 📓 A Jupyter notebook with:
  - Exploratory Data Analysis (EDA)
  - Model building and training
  - Comparison with supervised learning

If your project grows too large for a single notebook, you may:
- Use multiple notebooks or scripts in a GitHub repo
- Submit a report-style notebook or PDF summarizing the work

---

## 🧩 Part 2: Limitations of `sklearn` NMF [20 pts]

1. 📥 Load the movie ratings data (from HW3-Recommender-System)
   - Use matrix factorization to predict missing ratings
   - Measure RMSE using `sklearn`’s NMF [10 pts]

2. 🧠 Discuss:
   - Why did `sklearn`'s NMF not perform well compared to baseline or similarity-based methods from Module 3?
   - Suggest fixes or improvements [10 pts]

---

## 🧾 Grading Criteria Overview

Each of your three deliverables will be reviewed by three peers:
- 🧪 Notebook or PDF report
- 💻 GitHub repository (if applicable)
- 📸 Challenge leaderboard screenshot

Use the rubrics provided to guide your work. The project is graded out of 100 points.

---

## 🪄 Step 1: EDA & Feature Extraction [15 pts]

- Perform EDA: inspect, visualize, and clean the data
- Show visualizations (e.g., histograms)
- Explain your plan of analysis
- Choose and explain a word embedding method (e.g., TF-IDF, GloVe, Word2Vec)
- Demonstrate understanding of method in your own words
- Include references at the end of your report

---

## 🏗 Step 2: Build and Train Models [35 pts]

- Should the test set be included when training the matrix factorization model? Why?
- Build a matrix factorization model with chosen hyperparameters
- Measure performance (accuracy, confusion matrix, etc.)
- Submit test predictions to Kaggle
- Experiment with hyperparameters
- Summarize results in tables/graphs
- Try improving performance via feature extraction, ensembling, or subset-specific models

---

## 📊 Step 3: Compare with Supervised Learning [30 pts]

- Train a supervised learning model
- Compare its performance (train/test) with your unsupervised model
- Test with smaller training sets (e.g., 10%, 20%, 50%) and evaluate:
  - Data efficiency
  - Overfitting risks

---

## 📑 Step 4: Final Deliverable

📘 Produce a high-quality, organized **Jupyter Notebook Report** (or PDF). It should clearly present your entire pipeline and findings.

---

## 🤝 Peer Review Etiquette

This project is designed for hands-on Kaggle experience. Treat your peers as professional colleagues:
- Be constructive and thorough in your review
- Evaluate based on clarity, completeness, and insight

---
