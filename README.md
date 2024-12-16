# Google Stock Price Prediction

This project analyzes and predicts **Google Stock Prices (GOOG)** using Python. The notebook fetches data, preprocesses it, and applies advanced deep learning models such as **RNN**, **LSTM**, and **GRU** for time series forecasting.

---

## **Project Overview**

The notebook follows these main steps:

1. **Data Collection**
   - Fetch historical stock data for Google (GOOG) using `yfinance`.

2. **Data Preprocessing**
   - Splitting the data into training and testing sets.
   - Scaling and reshaping the data to fit deep learning models.

3. **Feature Engineering**
   - Creating datasets with lag features for input to RNN-based models.

4. **Model Training and Evaluation**
   - Models implemented:
     - **RNN (Recurrent Neural Network)**
     - **LSTM (Long Short-Term Memory)**
     - **GRU (Gated Recurrent Unit)**
   - The models are trained and evaluated for time series forecasting.

5. **Results Visualization**
   - Visualizes predictions and actual stock prices.

---

## **Requirements**

Make sure you have the following libraries installed:

```bash
pip install yfinance keras-tuner scikit-learn matplotlib pandas numpy tensorflow
```

---

## **How to Run**

1. **Clone this repository**
   ```bash
   git clone https://github.com/alinaeimiz/google-stock-prediction.git
   ```
2. **Install the requirements**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**
   - Open `GOOG.ipynb` using Jupyter Notebook or Jupyter Lab.
   - Execute all cells sequentially.

4. **Analyze Results**
   - Compare actual and predicted stock prices.

---

## **Project Structure**

```
.
├── GOOG.ipynb          # Jupyter Notebook for the project
├── README.md           # Project documentation (this file)
└── requirements.txt    # List of libraries (optional)
```

---

## **Models Used**

- **RNN (Recurrent Neural Network)**: A simple sequential model for time series.
- **LSTM (Long Short-Term Memory)**: Handles long-term dependencies for accurate forecasting.
- **GRU (Gated Recurrent Unit)**: A lightweight alternative to LSTM for faster training.

---

## **Results**

- Visualizations of predictions vs. actual stock prices.
- Performance metrics (e.g., RMSE, MSE) for each model.

---

## **About the Author**

**Ali Naeimi**  
Master of Computer Science Student  
GitHub: [alinaeimiz](https://github.com/alinaeimiz)  
Email: [alinaeimi2001@gmail.com](mailto:alinaeimi2001@gmail.com)

---

## **License**

This project is licensed under the MIT License.
