# Forest Fire Prediction using Weather Data 🔥

![GitHub stars](https://img.shields.io/github/stars/dushyantyadav2005/weatherfwiprediction?style=social)
![GitHub forks](https://img.shields.io/github/forks/dushyantyadav2005/weatherfwiprediction?style=social)


A machine learning project that predicts the Fire Weather Index (FWI) to assess the risk of forest fires based on meteorological data from the Bejaia region of Algeria. This project demonstrates a complete ML pipeline, from data cleaning and exploratory data analysis to model training, evaluation, and deployment with a user-friendly web interface.

---

## 🚀 Key Features

-   **Data Cleaning & Preprocessing**: Handles missing values, corrects data inconsistencies, and prepares the dataset for modeling.
-   **Exploratory Data Analysis (EDA)**: Visualizes data distributions and correlations to uncover insights.
-   **Feature Engineering**: Creates new features to improve model performance.
-   **Model Training**: Implements Ridge and Lasso regression models to predict the FWI.
-   **Model Evaluation**: Assesses model performance using metrics like R-squared and Adjusted R-squared.
-   **Web Interface**: Deploys the trained model using a Flask-based web application for easy-to-use, real-time predictions.

---

## 🛠️ Tech Stack

-   **Backend**: Python, Flask
-   **Data Science**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
-   **Deployment**: Pickle (for model serialization)

---

## ⚙️ Installation and Setup

To get this project up and running on your local machine, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/dushyantyadav2005/weatherfwiprediction.git](https://github.com/dushyantyadav2005/weatherfwiprediction.git)
    cd weatherfwiprediction
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

---

## 🏃‍♂️ Usage

1.  **Run the Flask application**:
    ```bash
    python application.py
    ```

2.  **Open your web browser** and navigate to `http://127.0.0.1:5000`.

3.  **Enter the required weather data** into the input fields and click "Predict" to get the FWI prediction.

---

## 📂 Project Structure
weatherfwiprediction/
├── templates/
│   └── home.html       # HTML template for the web interface
├── application.py      # Flask application for model deployment
├── requirements.txt    # Required Python libraries
├── ridge.pkl           # Trained Ridge regression model
├── scaler.pkl          # Scaler object for data preprocessing
└── notebook.ipynb      # Jupyter notebook with the full analysis
