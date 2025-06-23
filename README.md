# steam-games-analysis-bdpa
Steam Games Success Analysis

This project explores the factors that lead to game success on Steam, driven by a strong interest in understanding what makes certain games stand out. Understanding what drives success on Steam is more than an academic exercise—it has real-world importance. For developers, knowing these factors helps improve game design, creating experiences that attract players. For marketers, it guides advertising efforts, focusing on what matters to the gaming community. For players, it offers a way to find enjoyable titles within Steam’s large collection. With Steam influencing the gaming industry, predicting success is a valuable goal that connects innovation with better player experiences in a competitive market.

Research Focus

This study focuses on one key question:
Which game attributes best predict high positive review counts on Steam?
Positive reviews act as a strong indicator of player satisfaction and game popularity, making them the focus of our analysis. Using the Steam Games Dataset from Kaggle, which includes data on 97,405 games, the project applies Apache Spark and PySpark for efficient data processing and machine learning. A Random Forest Regressor is used to identify complex relationships among features, supported by a Linear Regression model as a baseline.

Hypotheses and Sub-questions

Hypothesis 1: Lower pricing increases positive review counts.
Hypothesis 2: Genres such as indie or action are associated with higher positive review counts, as indie games have shown strong review-to-sale conversion rates on Steam.
Hypothesis 3: More recent release dates correlate with greater positive review volumes.
Through these hypotheses and questions, the project aims to provide useful insights for the gaming industry, showing how big data and predictive modeling can reveal what drives success on Steam.

Dataset

The analysis uses the Steam Games Dataset from Kaggle (https://www.kaggle.com/datasets/fronkongames/steam-games-dataset), which contains detailed information on 97,405 games available on Steam, including their names, release dates, genres, tags, pricing, and review counts.
