## Projects

### [1. West Nile Virus incidence rate prediction across US](https://github.com/ncsa/CPRHD_WNV_GI)
- The main aim of this project was to predict the West Nile Virus (WNV) incedence rate across US for every county. This prediction would help the city authorities to spray for mosquitoes at right time thus killing the larvae of the disease causing mosquitoes
- Based on our research, there were several influencing factors like population, socio-economic featires, mosquito trap data, and weather that we found out to affect the WNV incedence rates (IR)
- The data was collected from variety of sources like NARR, Census board, NASA (for weather) and so on. All the large scale-multi dimensional datasets were cleaned and processed using Python scripting and OpenRefine
- The missing data points in Socio-economic features were imputed using __Vector Auto-Regression__ method
- Exploratory data analysis was conducted to check the effect of Entropy, Cummulative degree days, temporal lag and neighouring county cases on the incedence rate of current county and also to understand outliers
- The packages used for visualization are __matplotlib, bokeh, seaborn, plotly and ipywidgets__ 
- Several Statistical models were built including __Random Forest, Zero-Inflated Poisson Regression, Long Short Term Memory networks__ and __Seasonal ARIMA__ to forecast the WNV IR and the __LSTM model__ gave us an accuracy of more than __90%__

---
### [2. Predicting mortality by Acute Lower Respiratory Diseases in Americas](https://github.com/vpb2/PracticalHealthData)
- The main aim of this project was to understand the patterns of mortality caused by Acute Lower Respiratory Diseases and to predict the mortality rate for the year 2020 in Americas
- The primary data was provided to us by WHO which included the mortality data for all diseases. This data was cleaned and processed using Python scripting to include only Acute Lower Respiratory Diseases
- Several other indicators like population, number of physicians per 1000, and GDP data were integrated after downloading from data.world and processing it with python
- Created __Auto-ARIMA__ model to check the time-series validity of the indicators
- Built __Vector Auto-Regression__ model to perform Multivariate Time Series forecasting and predicted the death count for countries in the American continent with a __Mean Absolute Percentage Error of 0.0822__ 

![Mortality per year](/images/PHD2.png)
---
![Indicators for Mortality](/images/PHD3.png)
---
##### Forecast example for Canada: 
![Predictions for Canada](/images/PHD4.png)
---

### [3. Oscar predictions](https://github.com/vpb2/Machine_Learning_Oscars)
- The main aim of this project was to predict which movie will win an Oscar in a particular year based on other awards it has won
- The data from online movie databases like iMDb, rotten tomato, and movielens was downloaded and processed. Data for missing points was webscraped and cleaned for modelling using python scripts
- Exploratory analysis was conducted using python and juputer notebooks to identify trends and outliers, detect anomalies and understand the relationship between other awards, critic and user ratings with the movie winning the Oscar
- Implemented __Logistic Regression, Naive Bayes, Decision Trees__ and __Random Forest__ algorithms using sklearn package to compare different models and achieved an accuracy of __90%__ in resulting predictions

![IMDB heatmap](/images/Osc1.png)
---
![Oscar win and loss grouped by Genre](/images/Osc2.png)
---

