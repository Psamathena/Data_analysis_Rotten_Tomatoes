# Data_analysis_Rotten_Tomatoes
A mini project to test data analysis skills on the famous rotten tomatoes dataset
Here's a small README for your Rotten Tomatoes dataset project with a Random Classifier model and given metrics:

---

# **Rotten Tomatoes Movie Rating Prediction**

## **Project Overview**
This project aims to classify movies based on their ratings using a machine-learning model trained on Rotten Tomatoes data. The dataset includes various features related to critic and audience ratings, which are used to predict the rating category of a movie.

## **Dataset Description**
The dataset consists of movie-related features such as:
- **Tomatometer Ratings**: Aggregated critic scores.
- **Audience Ratings**: Viewers’ ratings.
- **Critic & Audience Counts**: The number of reviews considered.
- **Runtime & Certification**: Movie duration and age restrictions.

## **Model & Performance Metrics**
A **Random Classifier model** was trained, and its performance was evaluated using multiple metrics:

### **Model Evaluation Metrics**
- **Mean Squared Error (MSE)**: 0.0082
- **Root Mean Squared Error (RMSE)**: 0.0903
- **Mean Absolute Error (MAE)**: 0.0082
- **R-squared Score**: 0.9856
- **Accuracy Score**: 99.18%

### **Classification Report**
| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|---------|---------|
| 0     | 1.00     | 1.00   | 1.00    | 1487    |
| 1     | 0.98     | 0.99   | 0.99    | 1289    |
| 2     | 0.99     | 0.97   | 0.98    | 658     |
| **Overall Accuracy** | **0.99** | **0.99** | **0.99** | **3434** |

### **Confusion Matrix**
```
[[1487    0    0]
 [   0 1282    7]
 [   0   21  637]]
```
