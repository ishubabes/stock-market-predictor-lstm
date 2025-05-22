# 📈 Stock Market Predictor

A Python-based machine learning tool that analyzes historical stock data to predict future price movements and recommends BUY or SELL actions. It also provides live market capitalization analysis and visualization for portfolio weightings.

---

## 🚀 Features

### ✅ Historical Stock Analysis
- Fetches 10 years of historical stock data via [`yfinance`](https://pypi.org/project/yfinance/).
- Calculates daily price changes and classifies movement (up/down).
- Creates a target variable for binary classification (1 = BUY, 0 = SELL/HOLD).

### ✅ Machine Learning Models
Trains and evaluates the following models:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Each model:
- Uses standardized features (`Open`, `High`, `Low`, `Close`, `Volume`).
- Outputs an accuracy score and classification report.
- Predicts the next move using the latest market data.

### ✅ Market Capitalization Analysis
- Retrieves live market capitalization for top stocks (e.g., AAPL, MSFT, AMZN, TSLA, etc.).
- Computes weightage of each stock in a sample market portfolio.
- Displays weights using a pie chart.

### ✅ Visualizations
- Pie chart of stock weights based on market capitalization.
- Bar chart comparing model accuracy for different stocks.

---

## 🛠️ Technologies Used

| Tool | Description |
|------|-------------|
| `Python 3` | Core programming language |
| `pandas` | Data manipulation |
| `numpy` | Numerical calculations |
| `matplotlib` | Data visualization |
| `yfinance` | Fetching financial data |
| `scikit-learn` | Machine learning models and tools |

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/stock-market-predictor.git
   cd stock-market-predictor
