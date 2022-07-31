# Comparative study of Air Quality Index Prediction using Vector AutoRegression and Neural Networks

<br>

### Hypothesis:
Probability of more extended forecasting and improved accuracy  over training three years of data in comparison to one year's data using Vector AutoRegression
Finer Forecasting of Neural Network's model over Vector AutoRegression

<br>

### Data:
Available: Pollutant concentration levels with a frequency of 15 min
Additional (if possible): Wind speed, rainfall, temp, humidity, pressure

<br>

### Study Area: Bangalore

<br>

### Challenges:
Handling Null data
Upsampling weather data to merge with pollutant data as there will be a difference in the frequency of data recorded

<br>

### Knowledge gap:
Various neural networks models for multivariate time series prediction
Feature Extraction:
Season (spring, summer, monsoon, winter)
Morning, Afternoon, Evening, Night

<br>

### Future Scope:
Include the Topography feature, and train the model, along with more than one place

<br>

### Methodology:
Data Collection
Data Stationarity Check
Data Processing (Missing values imputation)
Exploratory Data Analysis (Correlation, Autocorrelation, ADF test, Granger-causality Test)
Train models
Forecast
Model Evaluation
