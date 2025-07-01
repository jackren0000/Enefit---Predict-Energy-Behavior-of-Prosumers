### **Enefit: Predicting Energy Behavior Like a Pro! ⚡**

Ever wondered how energy companies predict how much power we'll use? It's a super complex puzzle, but in this project, we're diving into a massive dataset from Enefit to predict the energy consumption and production patterns of "prosumers" (folks who both produce and consume energy!). Our goal is to minimize those tricky energy imbalance costs.

#### **Our Energy Expedition 🗺️**

1.  **Data Juggling 🤹:** This project is a data beast! We're wrangling a ton of different datasets:
    *   `train.csv`: The main energy consumption/production data.
    *   `gas_prices.csv`: Gas price info.
    *   `electricity_prices.csv`: Electricity price data.
    *   `client.csv`: Client information.
    *   `forecast_weather.csv`: Weather forecasts.
    *   `historical_weather.csv`: Past weather data.
    *   `county_lon_lats.csv`: Location mapping.

2.  **Data Prep & Feature Magic ✨:** Before we can predict anything, we need to clean and supercharge our data. We've built some awesome pipelines to:
    *   Handle missing values and ensure data types are spot on.
    *   Create new, powerful features from existing ones (like extracting time-based features from dates).
    *   Merge all these different datasets together into one super-dataset!
    *   Scale our data so our models can learn effectively.

3.  **LSTM Power! 🧠:** For the prediction part, we're using a fancy **Long Short-Term Memory (LSTM)** neural network. LSTMs are perfect for time-series data like energy consumption because they can learn from long-term dependencies. We're training it to predict future energy behavior and minimize those imbalance costs.

#### **Tech We Used 🛠️**

*   Python
*   Pandas & NumPy
*   Polars (for lightning-fast data processing!)
*   Matplotlib & Seaborn
*   TensorFlow & Keras (for our awesome LSTM model!)
*   Jupyter Notebook

#### **Want to Generate Some Insights? 🚀**

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jackren0000/Enefit---Predict-Energy-Behavior-of-Prosumers.git
    ```
2.  **Install the libraries:**
    ```bash
    pip install pandas numpy polars matplotlib seaborn tensorflow keras jupyter
    ```
3.  **Run the notebooks:**
    *   For data analysis and feature engineering:
        ```bash
        jupyter notebook DataAnalysis-predict-energy-behavior-of-prosumers.ipynb
        ```
    *   For the LSTM model:
        ```bash
        jupyter notebook lstm-predict-energy-behavior-of-prosumers.ipynb
        ```