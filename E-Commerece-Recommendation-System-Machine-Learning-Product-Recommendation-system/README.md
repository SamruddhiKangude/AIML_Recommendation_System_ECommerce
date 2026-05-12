# E-Commerce Recommendation System (Machine Learning & Flask)

## 📌 Overview
In today's digital era, e-commerce platforms are becoming increasingly popular, offering a vast array of products to consumers worldwide. However, with the abundance of choices, it can be overwhelming for users to find products that match their preferences. To address this challenge, implementing a recommendation system can significantly enhance the user experience by providing personalized product suggestions.

This project demonstrates the process of building an e-commerce recommendation system using Flask and machine learning techniques. It leverages content-based algorithms to suggest products based on their features and user preferences. The recommendation system is integrated with a Flask web application, featuring user registration, product browsing, and search functionality to provide a seamless and personalized shopping experience.

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **Machine Learning & Data Processing:** scikit-learn (TF-IDF Vectorizer, Cosine Similarity), pandas, NumPy
- **Database:** SQLite (managed via Flask-SQLAlchemy)
- **Frontend:** HTML, CSS, Bootstrap, Jinja2 Templates

## 🚀 How to Run the Project

Follow these simple steps to run the application on your local machine:

### Prerequisites
Make sure you have **Python** installed on your computer.

### Step 1: Open the Terminal
Navigate to the project directory in your terminal or command prompt:
```bash
cd E-Commerece-Recommendation-System-Machine-Learning-Product-Recommendation-system
```

### Step 2: Install Dependencies
Install all the required Python libraries using `pip`:
```bash
pip install flask pandas scikit-learn flask-sqlalchemy
```

### Step 3: Run the Application
Start the Flask server by running the `app.py` script:
```bash
python app.py
```

### Step 4: Access the Website
Once the server is running, open your web browser and go to:
👉 **http://127.0.0.1:5000**

### How to Use the App:
1. **Browse Trending Products:** The home page displays trending products natively.
2. **Sign Up / Sign In:** Create an account using the buttons on the top right (this will automatically save to your local SQLite database).
3. **Get Recommendations:** Click the **"Go To Main Page"** button, type a product name in the search bar, and specify the number of recommendations you want. The Machine Learning engine will suggest similar products based on text features!

## 💡 About Recommendation Systems
Recommendation systems are algorithms designed to predict user preferences and suggest items they are likely to enjoy. There are several types:
- **Content-based:** Analyzes item attributes and user preferences to recommend similar items.
- **Collaborative filtering:** Relies on user behavior data, such as ratings and interactions.
- **Hybrid & Multi-model:** Combines multiple approaches for more accurate and diverse recommendations.

Building an e-commerce recommendation system with Flask and machine learning offers numerous benefits, including enhanced user engagement, increased sales, and improved customer satisfaction!
