# COVID-19 Data Analysis

This project is a basic data analysis and prediction in response to COVID-19 done for my Master's Big Data Technology Course

## Requirement
- Python 3.7 or higher
- Jupyter Server
- Numpy
- Pandas
- Sklearn
- Keras
- Matplotlib
- Geopandas
- Seaborn
- Tabulate
- Descartes
- Statsmodels

## Installation
- I would suggest using `anaconda` to install these packages because some packages like geopandas has lots of dependencies
- I used `Jupyter notebook` to do my code for analysis so I would suggest to use the similar packages so that you can see what is happening in each step
- Copy `states` directory to the root becuase the code uses the figures from that folder to plot the US plots
- You also need figures folder and three subfolders inside it i.e : `gobal, predictions, and US`

## Data Analysis
### For United States
- Open **COVID_US.ipynb** file
- This notebook automatically pulls data from the [New York Times Server](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series) for the analysis and spits out some interesting graphs for US and Louisiana

### For Global
- Open **COVID.ipynb** file
- This notebook automatically pulls data from the [New York Times Server](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series) for the analysis and spits out some interesting graphs for whole world and a plot for China

## Prediction

- Open **COVID-KERAS.ipynb** file
- I used Keras LSTM for predicting the cases that would arise for next 12 days
- There is no extra steps you have to do to run this.
- If all the packages are installed correctly, the code will pull the data as previous from [New York Times Server](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series), preprocesses it and will show the predictions graph and data for next 12 days
- **Note** I was also playing around with Facebook's prophet for data prediction, it was something I wanted to learn, I got some interesting graphs from there too. Plese check it out in the **COVID-FBPROPHET.ipynb** notebook. I have not included this part in the report.