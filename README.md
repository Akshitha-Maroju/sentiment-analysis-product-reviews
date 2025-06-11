# sentiment-analysis-product-reviews

📊 Sentiment Analysis Product Review
📌 Project Overview
This project is a machine learning-based product review rating system that analyzes the sentiment of user-written product reviews and predicts a numerical rating from 1 to 5. Built using Python, pandas, scikit-learn, and TF-IDF vectorization, the model is trained and run on Google Colab. A simple Gradio interface allows real-time user interaction.

⚙️ Technologies Used
Algorithm: Logistic Regression
Development Platform: Google Colab
User Interface: Gradio (for input/output interaction)

🚀 How It Works
User submits a product review.
The review is processed (cleaned and vectorized).
A logistic regression model analyzes the sentiment.
The model predicts a rating between 1 and 5.
The result is displayed through a Gradio web interface.

📂 Files Included
product_review.ipynb – Jupyter notebook with the complete code
logistic_model.pkl – Trained Logistic Regression model
vectorizer.pkl – TF-IDF vectorizer
Gradio interface code
Dataset file(s)

💡 Features
Clean and interactive UI with Gradio
Accurate rating predictions based on review sentiment
Easy to use and run entirely within Google Colab
Lightweight and beginner-friendly

✅ How to Run
Open product_review.ipynb in Google Colab.
Upload the following files if not preloaded:
  logistic_model.pkl
  vectorizer.pkl
Run all the cells in order.
The Gradio interface will launch — enter your product review to get a predicted rating.

📌 Example
Input: “This product is amazing and works perfectly.”
Output: Predicted Rating: 5
