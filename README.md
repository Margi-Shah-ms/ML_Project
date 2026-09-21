# GMM-Based Consumer Sentiment Analysis

## PDF
https://drive.google.com/file/d/1BYonA94lfWFYKhrS92iUhHi6mw83_JDL/view?usp=sharing

## pptx
https://docs.google.com/presentation/d/15yOHRlyNxsvWEX_LHLb0F_ig13ZOVEcE/edit?usp=sharing&ouid=103337296187085832625&rtpof=true&sd=true

## 📖 Project Overview
This project applies Gaussian Mixture Models (GMM) to analyze consumer sentiment in online food delivery platforms. Instead of using predefined sentiment labels, the model identifies hidden customer segments based on satisfaction ratings and feedback patterns.

## 🎯 Objectives
- 📊 Analyze consumer sentiment using survey-based customer satisfaction data.
- 🤖 Apply Gaussian Mixture Models (GMM) for unsupervised sentiment segmentation.
- 📈 Determine the optimal number of sentiment clusters using Bayesian Information Criterion (BIC).
- 📉 Visualize sentiment clusters using Principal Component Analysis (PCA).
- 💡 Identify key factors influencing customer sentiment, such as Service Quality, Packaging Quality, and Value for Money.

## 🗂️ Dataset
The dataset contains survey responses collected from users of online food delivery platforms.

### 📌 Features Used
- ⭐ Service Quality
- 📦 Packaging Quality
- 💰 Value for Money
- 👥 Customer Demographics
- 📝 Textual Feedback

## ⚙️ Methodology

### 🧹 1. Data Preprocessing
- Converted rating attributes into numerical values.
- Cleaned and transformed survey data.
- Applied Z-score normalization for feature standardization.

### 🎯 2. Feature Selection
Selected important sentiment-related features:
- ⭐ Service Quality
- 📦 Packaging Quality
- 💰 Value for Money

### 🤖 3. Clustering Using GMM
Gaussian Mixture Models (GMM) were applied to identify latent customer sentiment groups through unsupervised learning.

### 📊 4. Model Selection
Bayesian Information Criterion (BIC) was used to determine the optimal number of clusters.

### 📉 5. Visualization
Principal Component Analysis (PCA) was used to reduce dimensionality and visualize customer segments.

### 📝 6. Text Analysis
Customer feedback was analyzed to identify common themes associated with each sentiment cluster.

## 🛠️ Technologies Used
- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 🤖 Scikit-Learn
- 📊 Matplotlib
- 📈 Seaborn
- 🧠 Gaussian Mixture Model (GMM)
- 📉 Principal Component Analysis (PCA)

## 📋 Results
- ✅ Identified three distinct customer sentiment clusters.
- ✅ BIC validation confirmed the optimal cluster count (K = 3).
- ✅ Revealed hidden customer behavior patterns beyond traditional positive/negative sentiment analysis.
- ✅ Text analysis highlighted key sentiment drivers such as service experience and app usability.

## 🎉 Conclusion
The project demonstrates that customer sentiment is multi-dimensional and can be better understood through unsupervised learning techniques. By combining GMM clustering, BIC validation, PCA visualization, and textual feedback analysis, meaningful customer segments were identified that can support business decision-making and customer experience improvement.
