# Title: Football-Player-Market-Value-Prediction


#### -- Project Status: [Completed ✅]

## Project Intro/Objective

This is a dataset created from webscrping, using python. Data was collected, cleaned, transformed, and aggregated from two websites () from over 20 tables. Beautifulsoup library in Python was used to achieve the same. Various predictive models were used to create an accurate predictor system. Players were chosen from top Football/Soccer leauges like Premier League, La Liga, Bundesliga, Serrie A, and Ligue 1. The final dataset had over 350 players with detailed statistics parameters of performance collected from over 2 seasons. 
Use the Final3.xslx for final aggregated results

### Methods Used
* Inferential Statistics
* Machine Learning
* Feature Engineering
* Predictive Modeling
* Data Visualization
* Classification 

### Technologies
* Python
* Pandas, TensorFlow, SkLearn
* Collab

## Project Description
* This Notebook is based off a dataset I created by webscraping data from various open source resources, aggregating data into tabular format, performing transformations on columnar data for effective use. I wrote a script at the time to fetch data and most of the web-scraping was done on python using beautifulsoup. Final dataset was narrowed down to 350+ player data, with their market value, and 50+ football statistical data from over two seasons of professional football!
* We could predict their market value with an accuracy of 90% with a 5% error marging. Best model in this case was Random-Forrest Regressor!
* All models are subject to betterment with more stringent hyper-parameter tuning. This can be achieved by random selection, brute force methods, etc. Various other classifiers can also be used, but the most standard classifiers have been considered in this notebook.
* Recommend standard practices for data transformation, outlier detection, and null value substitution have been incorporated in this notebook.
* Good visualizations have also been shown in the notebook for explaining the importance and significance of certain parameters. It can be easily understood by people coming from non-technical backgrounds. Various parameter tuning and scaling methods are shown that helped me achieve enhanced results!


## Getting Started

  
 One can simply download the notebook and dataset, open in platforms like Jupyter, Collab, and Run each cell to see results!
  This Python 3 environment comes with many helpful analytics libraries installed
 It is defined by the kaggle/python Docker image: https://github.com/kaggle/docker-python
 For example, here's several helpful packages to load

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

Input data files are available in the read-only "../input/" directory
For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))




## Contact

* Feel free to contact team leads with any questions or if you are interested in contributing!
* https://www.linkedin.com/in/akarshsinghh/

