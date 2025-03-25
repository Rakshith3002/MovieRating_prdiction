🎬 IMDb India Movies - Movie Rating Prediction

📌 Overview Ever wondered what makes a movie highly rated? This project dives deep into the IMDb India Movies dataset to analyze trends and predict movie ratings. Using machine learning models, we explore factors like genre, duration, and votes to understand what influences audience ratings.



📂 About the Dataset 


We’re working with a dataset that contains details about Indian movies, including:

Movie Name 🎥

Release Year 📅

Duration ⏳

Genre 🎭

IMDb Rating (Target Variable) ⭐

Votes 🗳️

Director & Leading Actors 🎬

Our goal? To clean, analyze, and build a predictive model that estimates a movie’s IMDb rating!


🔍 Exploratory Data Analysis (EDA) To get meaningful insights, we explored:

📊 Rating Distributions – Are most movies highly rated, or do ratings follow a normal curve?

🎭 Genre & Director Trends – Which genres and directors dominate the top-rated list?

📈 Time-Based Trends – How have movie ratings changed over the years?

💡 Correlations – Does a longer duration mean a higher rating? Do more votes translate to better ratings?

We used visualizations like histograms, scatter plots, and heatmaps to make sense of the patterns.


🚀 Feature Engineering To improve our model’s predictions, we: 

🔹 One-hot encoded categorical variables (like Genre and Director) 

🔹 Scaled numerical features (Votes, Duration) 

🔹 Created new features based on data trends


🧠 Building the Prediction Model We tested multiple models to find the best one for predicting ratings:

Linear Regression 🏗️ (Basic but interpretable)

Ridge Regression 🔍 (Prevents overfitting)

Decision Tree Regressor 🌳 (Captures non-linear relationships)

Random Forest Regressor 🌲 (Ensemble learning for better accuracy)


To evaluate the models, we used:

📉 Mean Squared Error (MSE) – Lower is better

📊 Mean Absolute Error (MAE) – Measures prediction accuracy

📈 R-squared (R²) – Tells us how well the model fits the data

After testing, we picked the model with the best balance of accuracy and interpretability.


🎯 Key Insights & Results

🔹 Votes have a strong impact – More votes usually mean a better rating.

🔹 Drama & Action genres dominate – These genres consistently receive high ratings.

🔹 Director influence matters – Certain directors repeatedly produce high-rated films.

🔹 Model Performance – The best model achieved high accuracy in predicting IMDb ratings!


⚡ How to Run the Project

 To utilize this dataset and associated code:

 Clone the repository:

 git clone file_address

 Open and execute the IMDB_Movies_Rating_Prediction.ipynb Jupyter Notebook on Google Colab.

 Check the results – The output folder contains plots and model predictions!


📌 Requirements

Make sure you have the following installed:

🔹 Python 3.x

🔹 Pandas

🔹 NumPy

🔹 Matplotlib

🔹 Seaborn

🔹 Scikit-learn


👨‍💻 Contributors

👤 Rakshith Kuchanpally – Django Developer & Data Science Enthusiast

💡 Open to contributions! Fork the repo and improve the model.
