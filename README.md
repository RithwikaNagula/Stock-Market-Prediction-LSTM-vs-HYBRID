
Stock Price Prediction: LSTM vs Hybrid (LSTM + XGBoost)

This project compares the performance of a pure LSTM model versus a hybrid model that combines LSTM for feature extraction and XGBoost for final prediction. It focuses on forecasting stock prices and generating a 30-day future outlook based on historical data.


Overview

Stock price prediction is a challenging task due to the volatile and non-linear nature of the market. In this project, we:
- Use an LSTM neural network to learn time-series dependencies.
- Extract LSTM outputs as features.
- Use XGBoost, a gradient boosting algorithm, to improve accuracy and capture nonlinear relationships.
- Perform 30-day future predictions for stock prices.

Technologies Used

- Python
- Pandas, NumPy
- Matplotlib / Plotly
- Scikit-learn
- TensorFlow / Keras (LSTM)
- XGBoost
- Streamlit (for UI, if applicable)

📁 Project Structure
.
├── app.py # Main application script
├── requirements.txt # Python dependencies
└── README.md # Project documentation

🚀 How to Run

1. Clone the repository:

   git clone https://github.com/RithwikaNagula/Stock-Market-Prediction-LSTM-vs-HYBRID.git
   cd Stock_Price_Prediction-LSTM-vs-HYBRID-

   
2. Install dependencies:
pip install -r requirements.txt


3.Run the app:
python app.py


This model helps:

-Understand the advantages of hybrid models in time-series forecasting.

-Improve prediction accuracy using ensemble learning.

-Apply deep learning and gradient boosting for financial data modeling.

OUTPUTS:

Comparing LSTM vs Hybrid Prediction
![image](https://github.com/user-attachments/assets/df2d775c-1abc-4676-b0c1-7629fc6b1ee2)

Prediction Plot
![image](https://github.com/user-attachments/assets/ff288987-f9fb-4c85-b210-663cf6139108)

30-Day Forecast
![image](https://github.com/user-attachments/assets/1a9e79fd-5197-44e1-b5ce-6d71d4afa964)


