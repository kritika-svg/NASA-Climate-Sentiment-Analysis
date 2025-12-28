# NASA Climate Change: Public Sentiment & Engagement Analysis

## 📌 Project Overview
This project analyzes over 500 user comments from NASA's Facebook page (2020–2023). The objective is to decode public opinion on climate change and identify the features that make a comment "highly engaging."

## 🚀 Key Features
* **Sentiment Analysis:** Classifying public comments into Positive, Neutral, and Negative tones.
* **Topic Modeling (LDA):** Identifying hidden themes in public discourse.
* **Engagement Prediction:** A Random Forest Regressor to predict the number of likes a comment will receive based on text features.

## 📂 File Structure
* `Climate Change.ipynb`: Full Python implementation (EDA, NLP, and ML).
* `climate_nasa.csv`: The raw dataset of Facebook comments.
* `climate_engagement_model.pkl`: The trained predictive model.
* `text_vectorizer.pkl`: CountVectorizer used for text processing.
* `Documentation/`: PDF reports detailing the project methodology and findings.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, Scikit-learn, NLTK, Gensim, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook

## 📊 Results & Insights
* **Visual Storytelling:** Comments praising NASA's visualizations had the highest engagement.
* **Predictive Power:** Text length and specific keywords like "CO2" and "science" are strong predictors of likes.
