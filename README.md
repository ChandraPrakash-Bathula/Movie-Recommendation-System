# Netflix Movie Recommendation System
A Comparative Machine Learning Case Study: Movie Recommendation System Using Collaborative Filtering and Content-Based Filtering with Netflix Dataset.

# Netflix Movies Recommendation System.

![Python](https://img.shields.io/badge/Python-3.7%2B-brightgreen.svg) ![Machine Learning](https://img.shields.io/badge/Machine_Learning-Collaborative_Filtering%2C_Content_Based-yellow.svg) ![Recommendation System](https://img.shields.io/badge/Recommendation_System-Netflix_Movie-blue.svg) ![XGBoost](https://img.shields.io/badge/XGBoost-Gradient_Boosting-orange.svg)

## Overview Of this Project :

This project aims to build an advanced Movie Recommendation System for Netflix, leveraging both collaborative filtering and content-based filtering techniques. The system predicts users' preferences by analyzing their past movie ratings, providing personalized movie suggestions. The implementation utilizes Surprise-based Singular Value Decomposition (SVD), K-Nearest Neighbors (KNN) algorithms, and XGBoost Regression to achieve accurate movie predictions.

## Steps Implemented in this Project :

<b>1. Data Collection:</b> We collected a large dataset of anonymous movie ratings from Netflix to build our recommendation system.

<b>2. Data Preprocessing:</b> The collected data was cleaned and processed to ensure high-quality and reliable recommendations.

<b>3. Collaborative Filtering:</b> We used Surprise-based SVD and KNN algorithms to implement collaborative filtering, predicting movie ratings based on user behavior.

<b>4. Content-Based Filtering:</b> Content-based filtering was implemented to recommend movies based on the movie's features, such as title, genre, and cast.

<b>5. Model Evaluation:</b> We evaluated various models and compared their performance using Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE).

## Observations

- **SVD Model**: The Surprise-based SVD algorithm exhibited impressive performance, resulting in low RMSE values and accurate predictions.

- **KNN Model**: The KNN-based collaborative filtering approach also performed well, producing reliable and relevant movie recommendations.

- **XGBoost Regression**: The addition of XGBoost Regression significantly improved the overall prediction accuracy, further enhancing the recommendation system.

- **Content-Based Filtering**: The content-based filtering approach provided diverse recommendations based on movie features, adding a unique dimension to the recommendations.

- **Consideration of Business Objectives**: The system design considered business objectives such as interpretability and non-critical latency requirements, making it more user-friendly.

## Conclusion

The Netflix Movie Recommendation System combines collaborative filtering and content-based filtering techniques to deliver personalized and accurate movie suggestions. The inclusion of XGBoost Regression further enhances the prediction accuracy. The implementation's success is evident from the achieved RMSE of 1.075 and MAPE of 35.02 on the test data, indicating the system's efficiency in providing relevant movie recommendations. The project represents a significant step forward in building a comprehensive and engaging movie recommendation engine for Netflix users.
