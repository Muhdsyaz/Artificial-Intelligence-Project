# CRYPTO CURRENCY PREDICTION USING MACHINE LEARNING

## A. PROJECT SUMMARY

**Project Title:** Cryptocurrency Prediction Using Machine Learning

**Team Members:** 
- Muhammad Azri Bin Abdullah Zawawi
- Muhammad Syazani Bin Mohd Shah
- Muhammad Zulfahmi Bin Zambri
- Zaki Armindo


- [ ] **Objectives:**
- Getting real-time crptocurrency data.
- Prepare data for training and testing.
- Predict the price of crptocurrency using LSTM neural network.
- Visualize the prediction results.


##  B. ABSTRACT 

A Cryptocurrency is a peer-to-peer digital exchange system in which cryptography is used to generate and distribute currency units. This process requires distributed verification of transactions without a central authority. Transaction verification confirms transaction amounts, and whether the payer owns the currency they are trying to spend while ensuring that currency units are not spent twice. This verification process is called mining. Cryptocurrencies use a variety of mining technologies, according to their particular requirements. For instance, certain Cryptocurrencies focus on restricting the number of transactions validated per unit time, while others concentrate on achieving fast, lightweight services. Some mining algorithms are deliberately memory intensive; others are computationally expensive.


![Coding](https://cdn-japantimes.com/wp-content/uploads/2018/01/z2-crypto-a-20180123.jpg)

Figure 1 shows the example of Crypto Coins.


## C.  DATASET

In this project, we’ll discuss about prediction in crptocurrency

For each currency, we are used 1 year dataset

The data contains total of 6 main features. The details for them are as follows :

- Close Price – It is the market close price for currency for that particular day.
- Open Price – It is market open price for currency for that day.
- High Price – It is highest price of currency for the day.
- Low Price – It is the lowest price for currency for that day.
- Ajd Close - Adjusted close is the closing price after adjustments for all applicable splits and dividend distributions. Data is adjusted using appropriate split and dividend multipliers, adhering to Center for Research in Security Prices (CRSP) standards.
- Volume – The volume of currency that is being in trade for that day.


**Ripple (XRP)**

Dataset that we are used for XRP are from 15/4/2020 until 15/4/2021. We have trained same LSTM model on Ripple data. We are predicting prices from 22 March 2021 to 15 April 2021. Below table shows our dataset example.


![Figure 1](https://github.com/azriawi/Artificial-Intelligence-Project/blob/main/Image/XRP%20Example%20Dataset.jpg)

Figure 2 shows the example of XRP dataset.

![Figure 2](https://i1.wp.com/pirimidtech.com/wp-content/uploads/2018/04/0-4.jpg?w=592&ssl=1)

Again, overall difference between real and predicted prices is from 0 to 5.6%.


**Ethereum (ETH)**

For Ethereum, dataset that we are used is from 11/5/2020 - 11/5/2021. Below table shows our dataset example.

![Figure 3](https://github.com/azriawi/Artificial-Intelligence-Project/blob/main/Image/ETH%20Example%20Dataset.jpg)

Figure 3 shows the example of ETH dataset.

As shown above, difference between real and predicted close price is 0% to 7.4%. For really simple LSTM model we’ve trained and tested.

**BITCOIN (BTC)**

For Bitcoin, dataset that we are used is from 18/5/2020 - 18/5/2021. Below table shows our dataset example.

![Figure 3](https://github.com/azriawi/Artificial-Intelligence-Project/blob/main/Image/BTC%20Example%20Dataset.jpg)

Figure 4 shows the example of BTC dataset.

## D.   PROJECT STRUCTURE

The following directory is our structure of our project:
- $ tree --dirsfirst --filelimit 10
- .
- ├── image
- │   ├── BTC Example Dataset.jpg
- │   ├── ETH Example Dataset.jpg
- │   └── XRP Example Dataset.jpg
- ├── Results
- │   ├── BTC Result Prediction.jpg
- │   ├── ETH Result Prediction.jpg
- │   └── XRP Result Prediction.jpg
- ├── BTC.ipynb
- ├── BTC.py
- ├── BTC-USD.csv
- ├── ETH.ipynb
- ├── ETH.py
- ├── ETH-USD.csv
- ├── XRP.ipynb
- ├── XRP.py
- ├── XRP-USD.csv
- 2 directories, 15 files

The dataset/ directory contains the data described in the “Cryptocurrency Prediction dataset” section.

Three images provided are the examples of dataset from three types of cryptocurrency which BTC, ETH and XRP.

We’ll be reviewing three Python scripts in this tutorial:

- BTC.ipynb: Accepts our input dataset for BTC and performs prediction for its price. A training history BTC Result Prediction.jpg containing origin/valid/prediction curves is also produced.
- ETH.iypnb: Accepts our input dataset for ETH and performs prediction for its price. A training history ETH Result Prediction.jpg containing origin/valid/prediction curves is also produced.
- XRP.ipynb: Accepts our input dataset for XRP and performs prediction for its price. A training history XRP Result Prediction.jpg containing origin/valid/prediction curves is also produced.

In the next two sections, we will train our cryptocurrencies price predictor.

## E   TRAINING THE PREDICTION

We are now ready to train our face mask detector using Keras, TensorFlow, and Deep Learning.

From there, open up a terminal, and execute the following command:

COMING SOON!!! zzzzzzzz


![Figure 4](https://www.pyimagesearch.com/wp-content/uploads/2020/04/face_mask_detector_plot.png)


## F.  RESULT AND CONCLUSION

For every crpyto currency that we are predict, we only predict for 25 days from the dataset that we are used

**BITCOIN (BTC)**

This is the prediction of Bitcoin result for 25 days from 24/4/2021 - 18/5/2021. As we can see, the purple line indicates the prediction and the blue line is the origin data.

![Figure 4](https://github.com/azriawi/Artificial-Intelligence-Project/blob/main/Image/BTC%20Result%20Prediction.jpg)

**Ethereum (ETH)**

Prediction of ETH result for 25 days from 17/4/2021 - 11/5/2021.

![Figure 4](https://github.com/azriawi/Artificial-Intelligence-Project/blob/main/Image/ETH%20Result%20Prediction.jpg)

**Ripple (XRP)**

Prediction of XRP result for 25 days from 22/3/2021 - 15/4/2021.


![Figure 4](https://github.com/azriawi/Artificial-Intelligence-Project/blob/main/Image/XRP%20Result%20Prediction.jpg)

**Conclusion**

For every crypto currency that we used as dataset to predict (BTC, XRP, ETH), we can see that the difference between real and predicted price is not too much differents. The predicted result is almost as accurate as the real data, so we can conclude that this AI prediction system is 80% accurate.

## G.   PROJECT PRESENTATION 

COMING SOON!!! zzzzzzzzzzzzzzz

[![demo](https://img.youtube.com/vi/-p7HGwOWxtg/0.jpg)](https://www.youtube.com/watch?v=-p7HGwOWxtg "demo")




