# 🎬 Movie Rating Prediction with Python | CodSoft Task 2

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Internship](https://img.shields.io/badge/CodSoft-Data%20Science-red)

> **"Can we decode the 'Blockbuster Formula'? This project uses Machine Learning to predict movie ratings based on genre, director, and audience engagement."**

---

## 📄 Project Overview
In the film industry, success is often seen as unpredictable. However, data tells a different story. As **Task 2** for the **CodSoft Data Science Internship**, I developed a regression model to predict IMDb ratings. This project involves deep **Exploratory Data Analysis (EDA)** to uncover what truly drives a movie's success—is it the hype, the runtime, or the genius behind the camera?

### 🎯 Objective
To build a **Random Forest Regressor** capable of estimating movie ratings by analyzing historical data patterns.

---

## 📊 Visual Insights (EDA)
Data visualization is the bridge between raw numbers and cinematic insights. Here are the key findings:

### 1. The Popularity Paradox
There is a significant positive correlation between the number of votes and the rating. Movies that generate high engagement levels tend to have higher overall quality scores.
![Popularity vs Quality](https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON/blob/main/Images/popularity%20equal%20quality.png?raw=true)

### 2. Genre Dominance
Not all genres are created equal. My analysis shows that **Action** and **Sci-Fi** often lead the charts in terms of average ratings in this dataset.
![Average Rating by Genre](https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON/blob/main/Images/average%20movie%20rating%20by%20genre.png?raw=true)

### 3. The Runtime Myth
Does a longer movie mean a better movie? The regression line shows a near-flat relationship, proving that **Duration** has almost no impact on the final rating.
![Duration vs Rating](https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON/blob/main/Images/do%20longer%20movies%20get%20better%20rattings.png?raw=true)

### 4. The Director's Influence
Certain directors acts as a "seal of quality." The data identifies top-tier directors whose movies consistently score higher than average.
![Director Analysis](https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON/blob/main/Images/which%20derector%20guarantee%20a%20hit.png?raw=true)

### 5. Correlation Heatmap
The technical backbone of the project—revealing that **Votes** is the strongest predictor for ratings, far outweighing runtime.
![Feature Correlation](https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON/blob/main/Images/feature%20correlation%20heatmap.png?raw=true)

---

## 🛠️ Technologies & Tools

| Category | Tools Used |
| :--- | :--- |
| **Language** | Python 🐍 |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Seaborn, Matplotlib |
| **Machine Learning** | Scikit-Learn (Random Forest, Linear Regression) |
| **Environment** | Jupyter Notebook / Google Colab |

---

## 🚀 Key Workflow Steps

1. **Data Preprocessing:** Handled missing values and cleaned the movie titles and years.
2. **Feature Engineering:** Encoded categorical variables like `Genre` and `Director` using Target Encoding to preserve their relationship with the `Rating`.
3. **Exploratory Data Analysis:** Created visualizations to understand the impact of popularity and duration on ratings.
4. **Model Training:** Implemented a **Random Forest Regressor** to handle the non-linear relationships in the data.
5. **Evaluation:** Used R-squared and Mean Squared Error (MSE) to validate model performance.

---

## 📂 Repository Structure

```text
├── Images/               # Visualizations and EDA plots
├── Movie_Rating_Prediction.ipynb # Main Project Notebook
├── README.md             # Documentation
└── requirements.txt      # Dependencies

```

---

## 🔗 Connect with Me

I'm always open to discussing Data Science, Machine Learning, or even just great movies!

* **Author:** Faizan Firoz Shah
* **Role:** Data Science Intern @ CodSoft
* **Batch:** January 2026
* **Internship ID:** CS11NY482650
* **GitHub:** [Faizanakacoder](https://github.com/Faizanakacoder)
* **LinkedIn:** [My LinkedIn Profile](https://www.google.com/search?q=https://www.linkedin.com/in/0faizanshah0)

---

<div align="center">
<p>⭐ <b>If you found this project helpful, please give it a Star!</b> ⭐</p>
<p><i>Happy Coding! 🚀</i></p>
</div>

```

-----


```
