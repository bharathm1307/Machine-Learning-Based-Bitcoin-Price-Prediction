# ₿ Machine Learning Based Bitcoin Price Prediction

A Machine Learning-based Bitcoin price prediction system designed to analyze historical cryptocurrency market data and forecast future Bitcoin price movements using multiple predictive models such as **Linear Regression**, **Logistic Regression**, **ARIMA**, and **Facebook Prophet**.

The system helps users analyze Bitcoin price trends, predict future closing prices, and determine whether Bitcoin prices are expected to rise or fall.

---

## 📌 Project Overview

Cryptocurrency markets are highly volatile and influenced by several factors including market trends, trading volume, investor behavior, and economic conditions. Traditional analysis methods often struggle to provide reliable future price estimations.

This project introduces a **Machine Learning-Based Bitcoin Price Prediction System** that leverages historical Bitcoin market data and predictive analytics to forecast future Bitcoin prices.

The system provides:

- 📈 **Regression Model** → Predicts next-day Bitcoin closing price  
- 📊 **Forecasting Model (ARIMA & Prophet)** → Predicts future price trends  
- 🔍 **Classification Model** → Predicts whether Bitcoin price will increase or decrease

The application includes an interactive **Streamlit dashboard** for model exploration, trend visualization, and prediction analysis.

---

## 🎯 Problem Statement

Predicting cryptocurrency prices is difficult due to:

- High market volatility
- Rapid price fluctuations
- Dynamic trading behavior
- Lack of accurate prediction systems
- Complex time-series dependencies

This project solves these challenges using **Machine Learning and Time Series Forecasting techniques**.

---

## ✨ Features

✅ Bitcoin price prediction using Machine Learning  
✅ Next-day closing price prediction  
✅ Future trend forecasting using **ARIMA**  
✅ Time-series forecasting using **Facebook Prophet**  
✅ Bitcoin movement classification (**Price Up / Price Down**)  
✅ Interactive Streamlit dashboard  
✅ Data visualization and trend analysis  
✅ Historical market data analysis  
✅ Real-time prediction insights

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Machine Learning
- Linear Regression
- Logistic Regression
- Scikit-learn

### Time Series Forecasting
- ARIMA
- Facebook Prophet

### Data Analysis
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Frontend
- Streamlit

### Development Tools
- Visual Studio Code
- GitHub

---

## 📊 Dataset Used

The project uses **historical Bitcoin market data** containing cryptocurrency trading information.

### Dataset Features

- Timestamp
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume
- Market Capitalization

The dataset is used to train and evaluate prediction models for Bitcoin price forecasting.

---

## 🤖 Machine Learning Models Used

### 1️⃣ Linear Regression

Used to predict the **next-day Bitcoin closing price** based on historical trading features.

### 2️⃣ Logistic Regression

Used for **classification**, predicting whether Bitcoin price is expected to:

- 🔼 Go Up
- 🔽 Go Down

### 3️⃣ ARIMA Forecasting Model

Used for **time-series forecasting** to predict future Bitcoin closing prices.

### 4️⃣ Facebook Prophet Model

Used for advanced trend forecasting and future price estimation.

---

## ⚙️ System Architecture

The project follows the workflow below:

```text
Historical Bitcoin Dataset
            ↓
      Data Preprocessing
            ↓
     Feature Selection
            ↓
   Machine Learning Models
            ↓
Regression | Classification | Forecasting
            ↓
     Streamlit Dashboard
            ↓
     Bitcoin Price Prediction
```

---

## 🔍 Workflow

1. Load historical Bitcoin market data  
2. Preprocess and clean the dataset  
3. Extract important market features  
4. Train machine learning models  
5. Generate:

   - Bitcoin closing price prediction  
   - Future trend forecasting  
   - Price direction classification

6. Display outputs using Streamlit visualizations

---

## 📂 Project Structure

```text
Machine-Learning-Based-Bitcoin-Price-Prediction/
│── app.py
│── forecasting_model.py
│── requirements.txt
│── Bitcoin_3_11_2025-5_12_2025_historical_data_coinmarketcap.csv
│
│── models/
│   ├── classification_model.pkl
│   └── prophet_model.pkl
│
│── README.md
```

---

## 🚀 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/bharathm1307/Machine-Learning-Based-Bitcoin-Price-Prediction.git
```

### Step 2: Navigate to Project Folder

```bash
cd Machine-Learning-Based-Bitcoin-Price-Prediction
```

### Step 3: Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate virtual environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### Step 4: Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run the Project

### Run Streamlit Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📸 Screenshots

### Dashboard Interface

_Add your project screenshots here_

Example:

```md
![Dashboard](screenshots/dashboard.png)
```

---

## 🧪 Testing

The project was tested using:

- Functional Testing  
- Machine Learning Model Testing  
- Forecasting Accuracy Testing  
- Dashboard UI Testing  
- Data Visualization Testing  
- Integration Testing

All core functionalities worked successfully.

---

## 📌 Results

The system successfully achieved:

✔️ Bitcoin price trend prediction  
✔️ Next-day price forecasting  
✔️ Future market trend analysis  
✔️ Bitcoin movement classification  
✔️ Interactive visual analytics dashboard

---

## 🔮 Future Improvements

- Real-time cryptocurrency API integration  
- Support for multiple cryptocurrencies  
- Deep Learning models (**LSTM, RNN**)  
- Improved prediction accuracy  
- Live trading signal generation  
- Cloud deployment support

---

## 👥 Project Information

**Project Type:** Academic Project

**Domain:**  
Machine Learning + Cryptocurrency Analytics + Time Series Forecasting

**Objective:**  
To develop an intelligent system capable of forecasting Bitcoin prices and predicting market movement using Machine Learning techniques.

---

## 📄 License

This project is developed for **academic purposes**.

---

## ⭐ Support

If you found this project useful, consider giving it a **star ⭐ on GitHub**.