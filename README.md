# Rotten Tomatoes Movie Review Analysis 📽️🎥

## **Overview**
This project is an in-depth analysis of movie reviews and revenues using **Rotten Tomatoes** datasets and box office data. It aims to uncover patterns between audience and critic reviews, explore systematic differences in scoring, and predict movie revenues using various machine learning models.

---

## **Datasets**
We use two publicly available datasets from Kaggle:
1. **Rotten Tomatoes Reviews**:  
   Audience and critic reviews with scores and sentiments.  
   [Dataset Link](https://www.kaggle.com/datasets/bwandowando/rotten-tomatoes-9800-movie-critic-and-user-reviews)  

2. **Box Office Revenue Data**:  
   Revenue data for 1000 highest-grossing movies.  
   [Dataset Link](https://www.kaggle.com/datasets/kalilurrahman/top-box-office-revenue-data-english-movies)

---

## **Additional Files & Resources**
Due to file size constraints, all project datasets, notebooks, and outputs can be accessed through this [Google Drive folder](https://drive.google.com/drive/folders/1Y060fW1jof9RHWECeU3vU7EX1rYtEcsz?usp=drive_link).

## **Project Objectives**
1. **Data Exploration and Preprocessing**:  
   Perform data cleaning, feature engineering, and merging datasets.
   
2. **Analyzing Score Differences**:  
   Explore systematic differences in scores between critics and audiences.

3. **Revenue Prediction**:  
   Build predictive models to forecast movie revenue using scores and sentiments.

4. **Detailed Textual Analysis**:  
   Analyze sentiment patterns and lifecycle phases of audience reviews for select movies.

---

## **Tools & Techniques**
- **Data Analysis**: Python, Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning Models**: 
  - Decision Tree (Accuracy: 81%)
  - Random Forest
  - Neural Network (Best Model: Accuracy: 83.50%)
- **Textual Analysis**: Natural Language Processing (NLP) for audience reviews
- **Statistical Testing**: ANOVA, t-tests
- **Visualization**: Violin plots, word clouds

---

## **Key Findings**
1. **Score Distribution**:  
   Audience scores tend to cluster, while critic scores have a broader distribution.
   
2. **Systematic Differences**:  
   Critics favor certain genres, languages, and release types. A statistically significant bias was detected.

3. **Revenue Prediction**:  
   Positive sentiment and high scores were associated with higher revenues. Neural networks yielded the best predictive accuracy.

4. **Textual Insights**:  
   Sentiment patterns shifted with lifecycle phases (e.g., theatrical, streaming).

---

