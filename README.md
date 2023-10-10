
# Stock Market Prediction using Numerical and Textual Analysis

This project aims to predict stock market prices using a combination of numerical analysis and sentiment analysis of news headlines. It leverages time series analysis techniques and machine learning algorithms to make predictions based on historical stock data and news sentiment.

This project is a part of The Sparks Foundation GRIP internship which highlights time series analysis of historical stock prices and sentimental analysis of news headlines.
The historical stock prices dataset have been taken from https://finance.yahoo.com/ and the news headlines data is used from https://bit.ly/36fFPI6.

I have used Auto-ARIMA model to make stock market prices predictions using the historical stock prices data. In the sentiment analysis model, I have made use of different machine learning algorithms-Random Forest Regressor, LightGBM, Adaboost and Xgboost- to make the predictions.

## Acknowledgements

 - [Historical stock prices data](https://finance.yahoo.com/)
 - [Textual (news) data](https://bit.ly/36fFPI6)



## Steps Involved

### Data Preprocessing
Data preprocessing steps include handling missing values, converting data types, and ensuring data quality. The 'pandas' library is used for this purpose.

### Numerical Analysis
Various numerical indicators are calculated to understand market trends, including moving averages, standard deviations, and returns. These indicators provide insights into the historical performance of the stock.

### Textual Analysis
Sentiment analysis is performed on news headlines to gauge market sentiment. The 'NLTK' library is used for text preprocessing and sentiment analysis.

### Modeling
Machine learning models, including random forest regressor, AdaBoost regressor, XGBoost, and LightGBM, are applied to predict stock market prices based on historical data and sentiment scores.

### Results
The results of the stock market price predictions are presented and analyzed. Visualizations may include time series plots, prediction accuracy, and other relevant metrics.


## How to Use
To use this project, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies listed in the 'Dependencies' section.
3. Run the Jupyter Notebook or Python script to perform stock market prediction.

## Dependencies
- pandas
- numpy
- ta (Technical Analysis Library)
- nltk (Natural Language Toolkit)
- pmdarima (AutoARIMA)
- scikit-learn
- xgboost
- lightgbm
- matplotlib
- vaderSentiment

You can install these dependencies using pip:

```bash
pip install pandas numpy ta nltk pmdarima scikit-learn xgboost lightgbm matplotlib vaderSentiment
```
## 🚀 About Me
I'm enthusiastic and Driven Computer Science Engineering Student specializing in Artificial Intelligence and Machine Learning. With a strong foundation in Data science, with hands-on experience in ML and NLP.


[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manishk002)


## Authors

- [@manishk002](https://www.github.com/manishk002)

