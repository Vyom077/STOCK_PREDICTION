**Project Title:** NVIDIA Stock Prediction with Stacked LSTM and Tiingo API

**Overview**

This project implements a Stacked LSTM (Long Short-Term Memory) deep learning model to predict the future closing prices of NVIDIA stock over the next 100 days. The historical stock data is obtained using the Tiingo API. The project includes thorough visualizations to illustrate data trends and model performance.

**Dependencies**

* Python 3.6+
* Tiingo ([https://api.tiingo.com/](https://api.tiingo.com/)) - Get your free API key.
* Pandas 
* NumPy
* Matplotlib 
* Scikit-learn
* TensorFlow
* Keras 

**Results**

The project will generate detailed visualizations including:

* Line plots of historical NVIDIA stock closing prices.
* Plots comparing predicted stock prices vs. actual prices over the next 100 days.
* Performance metrics such as RMSE (Root Mean Squared Error) or MAE (Mean Absolute Error)

**Important Notes**

* Stock market predictions are inherently complex and uncertain. This project serves as an educational exercise; use the results with caution.
* The Tiingo API might have usage limits for free accounts. Consider their pricing plans if you need more extensive data.
* Hyperparameter tuning of the Stacked LSTM model can potentially improve the results.

**Future Extensions**

* Experiment with different time windows for data preparation.
* Incorporate additional technical indicators into the model.
* Explore other deep learning architectures (e.g., CNN-LSTM combinations).
* Add news sentiment analysis as a feature. 

