# 📈 Stock Price Prediction using Machine Learning

This project implements a stock price prediction system using historical data and supervised machine learning techniques. The goal is to predict future stock prices based on previous trends and patterns.

---

## 📁 Dataset

- Historical stock data was loaded using the **yfinance** API.
- Features include:
  - `Open`
  - `High`
  - `Low`
  - `Close`
  - `Volume`
- The data was split into training and testing sets to evaluate prediction performance.

---

## 🧠 Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** / **Seaborn** – Data visualization
- **Scikit-learn** – ML models, training, and evaluation
- **yfinance** – Stock market data collection
- **Jupyter Notebook** – Development environment

---

## 🔍 Project Workflow

1. **Importing Libraries**  
   Essential Python libraries for data handling, visualization, and modeling are imported.

2. **Data Collection**  
   Fetched stock data using `yfinance`.

3. **Exploratory Data Analysis (EDA)**  
   - Visualized trends in stock prices.
   - Checked for missing values and basic statistics.

4. **Feature Engineering**  
   - Created input/output pairs using the 'Close' price.
   - Scaled features for ML models.

5. **Model Training**  
   - Implemented regression models such as:
     - **Linear Regression**
     - **Support Vector Regression (SVR)**
     - **Decision Tree Regressor**
   - Evaluated models on test set using metrics like **R² score** and **Mean Squared Error**.

6. **Prediction & Visualization**  
   - Compared actual vs predicted stock prices.
   - Plotted predictions to visualize accuracy.

---

## 🎯 Results

The models were trained to predict the next day's closing stock price.  
The accuracy varied based on the model used and the size of the training dataset.  
Here’s an example of performance (varies by model):

- **Linear Regression R² Score**: *0.92*
- **SVR R² Score**: *0.85*
- **Decision Tree R² Score**: *0.89*

---

## 📌 Future Improvements

- Add LSTM (Long Short-Term Memory) based models for better time series prediction.
- Include sentiment analysis using stock-related news.
- Build a dashboard for real-time predictions.

---


## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

