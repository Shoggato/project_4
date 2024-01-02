## Project Name: WindyPredictAI

# Overview:
In the collaborative project "WindyPredictAI," our team, consisting of Eleanor Hayden, Stefan Shover, and Erika Walker, explores Predictive Forecasting with a focus on wind speed prediction. Leveraging historical weather data from Iowa State University and current weather forecasts from Weather.gov for Saint Louis, our goal is to train a neural network model capable of predicting whether it will be windy. The outcomes of this project carry practical implications for industries such as construction, sports events, and individual activity planning.

# Key Features:
1) __Data Collection:__
    * Training data sourced from Iowa State University `(https://mesonet.agron.iastate.edu/request/download.phtml)`.
    * Testing data obtained from Weather.gov `(https://www.weather.gov/)` for Saint Louis.
2) __Data Cleaning:__
    * Utilizing Pandas, ensures data comparability across features in training and testing sets.
    * Applies tensorization to vectorize data for improved machine learning interpretation.
3) __Model Development:__
    * Explores gradient boosted models, such as XGBoost, for initial predictions.
    * Constructs a Neural Network model to identify patterns and predict wind speed.

# Features:
* Relative Humidity
* Temperature
* Dewpoint
* Wind Speed
* Short Forecast
* Is Daytime
* Mapped Forecast

# Target:
* Wind Speed (Knotes): Float value

# Expected Outcomes:
This intriguing project aims to assess the performance of machine learning models trained on historical data for predicting rain. By incorporating current weather data, our model strives to achieve over 80% accuracy in predicting whether it will be windy.

# Outcomes:
Both XGBoosted Regression and the Deep Neural Network methods struggled to discern patterns in the data. It became evident that the available features and data were insufficient. To improve the model, we recommend considering additional features or obtaining more relevant data related to rain predictions. The limitations arose from compromises made with the historical and forecast data.

# Project Structure:
* Data Retrieval and Processing:
    * Fetches and processes historical and forecasted weather data.
* Normalization and Preprocessing:
    * Utilizes Scikit-learn transformers to normalize and preprocess the data.
* Model Training and Evaluation:
    * Explores gradient boosted models (XGBoost) and develops a Neural Network for wind speed prediction.
    * Evaluates the model using relevant metrics and visualizations.
* Hyperparameter Tuning:
    * Utilizes Keras Tuner to search for optimal hyperparameters for the Neural Network.
* Model Export:
    * Saves the trained model for future use or deployment.

# Requirements:
* Python 3.x
* Libraries: requests, pandas, numpy, scikit-learn, TensorFlow, Keras Tuner, XGBoost, matplotlib

# How to Use:
1) __Clone the Repository__
```bash
git clone https://github.com/yourusername/WindyPredictAI.git
cd WindyPredictAI
```
2) __Install Dependencies:__
3) __Run  the Jupyter Notebooks:__
   * Open and run the Jupyter Notebook provided (`WindyPredictAI.ipynb`).
4) __Explore and Customize:__
   * Explore the notebook, modify parameters, or extend functionality based on your needs.
5) __Save and Export:__
   * Save the trained model and any generated visualizations.

# Authors:
Erika Walker
Eleanor Hayden
Stefan Shover

# Acknowledgments:
Special thanks to Iowa State University for the historical weather data, Weather.gov for the forecast data, and the open-source community for their contributions.

