# Final Project:

## Runescape Grand Exchange Analysis & Supervised Machine Learning Bot
The Grand Exchange, commonly referred to as the GE, is a trading system for players to purchase and sell tradeable items in Old School RuneScape.

### Folder 1: Scrapper, Analyisis, ML
First we test our connection to the OSRS Grand Exchange API. in Test.py
Once we confirm our connection, we build a scrapper.py to connect to the OSRS grand exchange API, to export out the runes into a csv file


We Analyse over csv file with 1 year of grand exchange data sourced via the runescape Grand Exchange API. We do exploratory data analysis with Data_exploration.ipynb

We will be using python to help us looking at historical price's from 10 previous days, in order to try and predict the next day's price. We first need normalize our values. We do this by using the coefficent of variation formula. We split our data inti training and testing sets in order to apply a simple lstm model. We use Tensorflow to train our model to look 10 days into the past, in order to predict 1 day into the future the price of runes. ge_ml.ipynb

### Folder 2: Flask App





### Folder 3. Tableau & ETL


Link to Tableau Dashboard


## Skills

* Python (Pandas, matplotlib, tensorflow, seaborn)
* SQL
* API
* Tableau
* Extract, Transform Load
* Machine Learning
* S3



#### Anaconda Enviornment Set up

* Install pandas
* Install requests
* Install matplotlib
* Install seaborn
* Install Tensorflow


