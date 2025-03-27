# S&P Treasury Yield ML Analysis

## 📌 Project Overview
This project applies machine learning techniques to analyze the relationship between the **S&P 500 Index** and **U.S. Treasury Yields**. It aims to predict **S&P 500 closing prices** using regression and forecast **market direction** (up/down) using classification.

### Key Features:
- **Data Collection**: Fetches historical S&P 500 (^GSPC) and Treasury Yield (^TNX) data using `yfinance`.
- **Feature Engineering**: Computes daily returns, moving averages, and market volatility.
- **Regression Model**: Uses **Linear Regression** to predict S&P 500 closing prices.
- **Classification Model**: Implements **Logistic Regression** to predict market trends.
- **Performance Evaluation**: Assesses models with **metrics and visualizations**.

## ⚙️ Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install numpy pandas matplotlib seaborn yfinance scikit-learn
```

## 🚀 Usage
Run the script in a Python environment:
```bash
python script.py
```
This will:
1. Download historical financial data.
2. Engineer key financial indicators.
3. Train machine learning models.
4. Evaluate model performance.
5. Generate visualizations.

## 📊 Model Outputs
### 🔹 Regression Model (S&P 500 Price Prediction)
- **Mean Absolute Error (MAE)**: Measures prediction accuracy.
- **R-squared Score**: Assesses model fit.
- **Visualization**: Graph comparing **actual vs. predicted** prices.

### 🔹 Classification Model (Market Direction Prediction)
- **Accuracy Score**: Measures prediction reliability.
- **Confusion Matrix**: Evaluates prediction outcomes.
- **Classification Report**: Displays precision, recall, and F1-score.
- **Confusion Matrix Heatmap**: Graphical representation of model performance.
- <img width="458" alt="image" src="https://github.com/user-attachments/assets/768f4b7b-bc5d-4842-a8c0-39e1cb9bad6d" />
- <img width="452" alt="image" src="https://github.com/user-attachments/assets/1c3672b3-ad77-43fc-bac4-91c6d418b9bd" />
- <img width="458" alt="image" src="https://github.com/user-attachments/assets/173cf119-48ee-4659-87d9-9ac41d64a3a9" />





## 🛠 Future Enhancements
- Implement **Neural Networks** for improved predictions.
- Add **Sentiment Analysis** from financial news data.
- Integrate **real-time data streaming**.
- Deploy as a **web-based dashboard**.

## 📄 License
This project is licensed under the **MIT License** - see LICENSE file for details.

## 👨‍💻 Author
Developed by Jeremy Martinez-Quinones.
