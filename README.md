# 🎬 Movie Rating Prediction | CodSoft Task 2

### 📄 Project Overview
* **Objective:** Build a machine learning model to predict the rating of a movie based on features like genre, director, and actors.
* **Domain:** Data Science / Machine Learning (Regression Analysis).
* **Significance:** Analyzing historical movie data to understand the factors that influence audience ratings and commercial success.
* **Context:** Completed as **Task 2** for the **CodSoft Data Science Internship** (Batch Jan 2026).

### 📊 Dataset Details
* **Source:** IMDb Movies India Dataset.
* **Key Columns:** `Name`, `Year`, `Duration`, `Genre`, `Rating`, `Votes`, `Director`, `Actor 1`, `Actor 2`, `Actor 3`.
* **Challenges:** The dataset required significant cleaning (handling missing values, converting string text to numbers, and encoding high-cardinality categorical data).

### 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation), NumPy (Numerical Ops), Matplotlib & Seaborn (Visualization), Scikit-Learn (Modeling).
* **Environment:** Jupyter Notebook / Google Colab.

### 🚀 Methodology
1.  **Data Acquisition:** Loaded the `IMDb Movies India.csv` dataset using Latin-1 encoding to handle special characters.
2.  **Data Cleaning:**
    * Removed rows with missing ratings (target variable).
    * Cleaned the `Year` column by removing parentheses.
    * Cleaned the `Duration` column by removing "min" and converting to integers.
    * Cleaned the `Votes` column by removing commas.
3.  **Exploratory Data Analysis (EDA):**
    * Visualized the distribution of movie ratings.
    * Analyzed the impact of movie duration on ratings.
    * Identified top-performing directors and genres.
4.  **Feature Engineering:**
    * Applied target encoding (mean encoding) to handle high-cardinality columns like `Director` and `Genre`.
5.  **Model Building:**
    * Split the data into training and testing sets.
    * Trained a **Linear Regression** model (or Random Forest) to predict the continuous rating variable.
6.  **Evaluation:**
    * Evaluated model performance using Mean Squared Error (MSE) and R2 Score.
    * Visualized Actual vs. Predicted ratings to assess model accuracy.

### 📈 Key Results
* The model successfully identifies trends between casting choices/genres and the final movie rating.
* Demonstrated that certain directors and genres significantly weight the predicted score.

### 🔗 Project Link
* **Repository:** [https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON](https://github.com/Faizanakacoder/MOVIE-RATING-PREDICTION-WITH-PYTHON)

### 👤 Author Information
* **Name:** Faizan Firoz Shah
* **Internship:** CodSoft Data Science Intern
* **Batch:** January 2026
* **Internship ID:** CS11NY482650
