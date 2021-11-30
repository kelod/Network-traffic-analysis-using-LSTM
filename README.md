# Network-traffic-analysis-using-LSTM
Analyzing real world network traffic, using LSTM.

In this university project, I analyzed a real world network's subnetwork, and its link traffic.
I tried to predict the traffic for one link monitoring only one link, and also a whole subnetwork.
All data comes from my.es.net site, using webscraping methods.

Content:
- Scraping.ipynb : In this file I downloaded the data, then I tried out several methods for predicting multiple times ahead in the time series. (Using sequence-to-sequence model, batch methods, etc...)
- SubNetwork_OnlyOne.ipynb : In this file I tried to concentrate on one link's traffic prediction based on only that particular link. I tried out several methods to beat the naive lag model, like downsampling, ensemble methods, etc...
- SubNetwork.ipynb : In this file I trained the LSTM model with a multivariate time series, then I examined the results.
