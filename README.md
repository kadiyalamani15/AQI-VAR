# Comparative study of Air Quality Index Prediction using Vector AutoRegression and Neural Networks

### Summary
<br>

<p aligh="justify">
  Work in Progress
</p>

<br>

### Hypothesis:
<ol>
  <li>
  Probability of more extended forecasting and improved accuracy  over training three years of data in comparison to one year's data using Vector AutoRegression 
  </li>
  <li>
    Finer Forecasting of Neural Network's model over Vector AutoRegression
  </li>
</ol>

<br>

### Data:
<ol>
  <li>
    Available: Pollutant concentration levels with a frequency of 15 min
  </li>
  <li>
    Additional (if possible): Wind speed, rainfall, temp, humidity, pressure
  </li>
</ol>

<br>

### Study Area: Bangalore

<br>

### Challenges:
<ol>
  <li>
    Handling Null data
  </li>
  <li>
    Upsampling weather data to merge with pollutant data as there will be a difference in the frequency of data recorded
  </li>
</ol>

<br>

### Knowledge gap:
Various neural networks models for multivariate time series prediction
  
<br>
  
### Feature Extraction:
<ol>
  <li> 
    Season (spring, summer, monsoon, winter)
  </li>
  <li>
    Morning, Afternoon, Evening, Night
  </li>
</ol>

<br>

### Future Scope:
<p align="justify">
  Include the Topography feature, and train the model, along with more than one place.
</p>

<br>

### Methodology:
<ol>
  <li>
    Data Collection
  </li>
  <li>
    Data Stationarity Check
  </li>
  <li>
    Data Processing (Missing values imputation)
  </li>
   <li>
    Exploratory Data Analysis (Correlation, Autocorrelation, ADF test, Granger-causality Test)
  </li>
  <li>
    Train models
  </li>
  <li>
    Forecast
  </li>
  <li>
    Model Evaluation
  </li>
</ol>
