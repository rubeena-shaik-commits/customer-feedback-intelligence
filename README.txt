Customer Feedback Intelligence System

## 1. Project Overview
This project analyses customer reviews using Python and rule-based Natural Language Processing (NLP) to classify customer feedback as Positive, Negative or Neutral.

## 2. Project Objectives
- Analyse customer review data.
- Identify and handle missing values.
- Clean customer review text.
- Perform sentiment classification.
- Visualise customer sentiment and ratings.
- Compare sentiment with customer ratings.

## 3. Technologies Used
- Python
- Pandas
- Matplotlib
- Regular Expressions
- Google Colab

## 4. Dataset
Women's Clothing Reviews dataset containing customer reviews, ratings and product information.

Total reviews analysed: 22,641.

## 5. Project Workflow
1. Load the dataset.
2. Explore the dataset.
3. Check missing values and duplicates.
4. Clean review text.
5. Define sentiment keywords.
6. Implement sentiment analysis with basic negation handling.
7. Calculate sentiment counts and percentages.
8. Create visualisations.
9. Compare sentiment with customer ratings.
10. Export the final analysis.

## 6. Results

| Sentiment | Review Count | Percentage |
|---|---:|---:|
| Positive | 17,629 | 77.86% |
| Neutral | 3,557 | 15.71% |
| Negative | 1,455 | 6.43% |
| Total | 22,641 | 100% |

## 7. Project Files
- Customer_Feedback_Intelligence.ipynb – Complete Python notebook.
- Customer_Feedback_Analysis_Final.csv – Analysed customer reviews.
- Sentiment_Summary.csv – Sentiment summary.
- requirements.txt – Required Python libraries.

## 8. Limitations
This project uses keyword-based sentiment analysis. It has basic negation handling but cannot fully understand context, sarcasm or complex language.

## 9. Future Improvements
- Implement machine-learning-based sentiment classification.
- Improve contextual sentiment detection.
- Develop an interactive customer feedback dashboard.
