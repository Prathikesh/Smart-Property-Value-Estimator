## 🏡 Real Estate Price Prediction

### Overview
![Home Price Prediction UI](images/home_price_prediction.png)

This project is a Real Estate Price Prediction Website that allows users to estimate home prices based on area, BHK, bathrooms, and location. The model is trained using the Bangalore home prices dataset from Kaggle and is deployed via a Flask server. The website is built with HTML, CSS, and JavaScript, which interacts with the Flask API to fetch predicted prices.

---

### 📌 Features
- **Machine Learning Model:** Uses Linear Regression for price prediction.
- **Data Preprocessing:** Includes data cleaning, outlier removal, feature engineering, and dimensionality reduction.
- **Hyperparameter Tuning:** Implemented using GridSearchCV and k-fold cross-validation.
- **Flask Backend:** Serves predictions via an HTTP API.
- **Interactive UI:** Built with HTML, CSS, and JavaScript to take user inputs and display estimated prices.

---

### 🛠️ Tech Stack & Tools

#### 📊 Dataset  
- **Kaggle Dataset:** [Bengaluru House Price Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

#### 🖥️ Programming & Libraries  
- **Python**
- **NumPy & Pandas** – For data cleaning
- **Matplotlib** – For data visualization
- **Scikit-Learn (sklearn)** – For model building  

#### ⚙️ Development & Deployment  
- **Jupyter Notebook, VS Code, PyCharm** – Development IDEs  
- **Flask** – Backend API for price predictions  
- **HTML, CSS, JavaScript** – Frontend for user interaction  

---

### 🚀 Steps to Run the Project  

#### 1️⃣ Train the Model  
Run the Jupyter notebook to train the model and save it using `joblib` or `pickle`.

#### 2️⃣ Start the Flask Server  
```bash
python app.py
