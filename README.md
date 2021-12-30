#  Predicting-Ideal-location-for-a-new-reastaurant-using-Yelp-dataset

This dataset is a subset of Yelp's businesses, reviews, and user data. It was originally put together for the Yelp Dataset Challenge which is a chance for students to conduct research or analysis on Yelp's data and share their discoveries. In the most recent dataset you'll find information about businesses across 8 metropolitan areas in the USA and Canada.

## Getting Started


- Conducted Exploratory Data Analysis and Machine Learning/Predictive Analytics to classify 1-5 star yelp reviews.
- Applied Python NLTK Text classification to preprocess the Yelp reviews and perform sentiment analysis to analyze customer sentiments.
- Utilized SVD for dimension reduction, K-Means, Random Forest and Support Vector Machines for data classification
- Used Latent Dirichlet allocation to automatically detect latent subtopics within the text of reviews.
- Offered suggestions to find a favorable location to open a restaurant along with most favored food items in the areas of Phoenix, AZ.

- Predicting Yelp Reviews using Bigram Multinomial Naive Bayes with Oversampling:
- Conducted Exploratory Data Analysis and Machine Learning/Predictive Analytics to classify 1-5 star Yelp reviews!

## 🔑Prerequisites

```
# import packages
import os, glob
import pandas as pd
import numpy as np
import seaborn as sns
import re
import string
import matplotlib.pyplot as plt
import matplotlib.mlab as mlab
import matplotlib
import pickle
plt.style.use('ggplot')
from matplotlib.pyplot import figure

import tweepy
import matplotlib.pyplot as plt
from  textblob import TextBlob 
import time

%matplotlib inline
matplotlib.rcParams['figure.figsize'] = (12,8)

pd.options.mode.chained_assignment = None
```
<!-- ## Installing
## Running the tests
## Break down into end to end tests
## And coding style tests
## Deployment
## 🛠Built With

* [Scikit-learn](https://scikit-learn.org/stable/) 
## Contributing
## Versioning -->
## 💃Authors

* **Preet Mehta**  
<p>
<a href="https://www.linkedin.com/in/preetmehta/">
  <img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/Linkedin%20(1).svg" alt="kushal's linkedin" width="24px" />
</a>  

<a href="https://ynpreetmehta.medium.com/">
<img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/medium-seeklogo.com.svg" alt="Medium" width="25px" height='23.5' />
</a>  
  
<!-- ![Medium](mediumlogo/medium-seeklogo.com.svg?raw=true "Title") -->

 
<a href="https://www.instagram.com/ynpreet/" target="blank">
  <img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/Instagram%20(1).svg" alt="instagram" width="24px" />
</a>

<a href="https://www.youtube.com/channel/UCCcw6HxUkkfrlKn7-6SszDQ/featured" target="blank">
  <img align="left" src="https://github.com/ynpreet/Ynpreet/blob/main/images/youtube-logo-icon-png-svg.png" alt="youtube"  width="25px" height='23.5' />
</a></p><br><br>

## 👀License

This project is licensed under the MIT License - see the [LICENSE.md](https://opensource.org/licenses/MIT) file for details

## 🙏Acknowledgments

* Special Thanks to **[Bhavishek M](https://www.linkedin.com/in/bkmalik/)** for sharing wonderful insights about Social & Web abalysis on "Yelp Dataset challenge"
* [References](https://engineeringblog.yelp.com/2015/02/yelp-dataset-challenge-is-doubling-up.html) 

## 📁 Dataset
You can get the Dataset here

[Link](https://www.kaggle.com/yelp-dataset/yelp-dataset)

## 💡Working 

Make Sure that you Either Have *Jupyter Notebook* or *Spyder* to Run the code with amazing Visualizations and run any of the following in your Command Prompt in the directory that holds this repo. 

```
Jupyter Notebook
```
or
```
Spyder
```
## 👏And it's done!

- <details> <summary> 💬 Problem Solver. Passion Catalyst. Change Maker. Love simulating conversations especially if done over beer. Feel free to contact in case of any query or to collaborate to work on ML projects😎 </summary> <a href="https://wa.me/919408377842" target="blank"><img align="center" src="https://github.com/ynpreet/Ynpreet/blob/main/images/5ae21cc526c97415d3213554.png" width="40x" /></a>
</details>


