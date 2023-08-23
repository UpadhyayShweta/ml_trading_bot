# Machine Learning Trading Bot

![Decorative image.](Images/display-image.png)

## Background

In this notebook,we’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Our firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave our firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. we’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

We’ll combine your algorithmic trading skills with financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

We will also create a report that compares the performance of the machine learning models based on the trading predictions that each makes and the resulting cumulative strategy returns.

## Files

* [Analysis Notebook](machine_leraning_trading_bot.ipynb)
* [Resources](Resources/emerging_markets_ohlcv.csv)
> **Note:** The provided CSV file contains OHLCV data for an MSCI&ndash;based emerging markets ETF that [iShares](https://www.ishares.com/us/products/268704/ishares-currency-hedged-msci-emerging-markets) issued. Investments in emerging markets make up an important aspect of a well-diversified investment portfolio. This is because the included equities have potentially higher long-term returns, even though they carry more risk.

## Instructions

The steps for this analysis are divided into the following sections:

* Establish a Baseline Performance

* Tune the Baseline Trading Algorithm

* Evaluate a New Machine Learning Classifier and check
> *Did our new model perform better or worse than the provided baseline model? 
> *Did our new model perform better or worse than your tuned trading algorithm?

* Create an Evaluation Report

## Evaluation Report

As part of your GitHub repository’s README.md file, you will also create a report that compares the performance of the machine learning models based on the trading predictions that each makes and the resulting cumulative strategy returns.
#### With SVM classifier 
![Classification Report for SVM model with 3 months training period](Images/clf_report_svm_tt_3m.png)
![Classification Report for SVM model with 1 months training period](Images/clf_report_tt_1m.png)
![Classification Report for SVM model with 10 months training period](Images/clf_report_tt_10m.png)
![Actual returns vs Strategy Returns plot with 3 months training period](Images/plot_tt_3m_svm.png)
![Actual returns vs Strategy Returns plot with 1 months training period](Images/plot_tt_1m_svm.png)
![Actual returns vs Strategy Returns plot with  10 months training period](Images/plot_tt_10m_svm.png)

#### With AdaBoost Classifier
![Classification Report for AdaBoost model with 3 months training period](Images/clf_report_AdaBoost .png)
![Actual returns vs Strategy Returns plot with 3 months training period](Images/plot_with_AdaBoost.png)