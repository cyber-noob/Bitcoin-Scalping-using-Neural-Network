# Bitcoin-Scalping-using-Neural-Network

This project uses a simple LSTM Network which consists of three layers to make the job done. Here we have converted our stock price prediction problem into a sequence prediction  problem where the prices of past 5 minutes are fed into the data in order to predict the price of BTC-USD for the next minute. Here the model works on such a small timeframe due to the assumptions that 
1. Any news related price movements can be compensated by the model to avoid huge losses due to wrong predictions.
2. Since Bitcoin markets are very volatile, I didn't opt for long term predictions since any wrong predictions may cost huge losses.
3. We are always trying to follow the market trends instead of trying to predict long term prospects of the stock/commodity/currency since the future is always uncertain. (eg: Covid-19 market crash)

# Results and Observations 

I did run the model fed with real time forex updates as a means for bactesting to see how the model performs and to my surprise it did perform good as it was able to generate $100/hr on an average considering the 1BTC was traded everytime the model executes the order. Eventhough it might seem like it is almost impossible for a regular retail trader with very less capital to use this model since it also uses the concept of both Short Selling (requires margins) and going Long on positions. 
I do believe that this model can be a game changer for Financial Institutions if it works as intended as it can generate 100% return in approximately 9 days. All of my claims and results have been clearly charted out on the ipynb file at the end of the page and if you need me to build you with an actual trading bot please do feel free to contact me on *E-mail: ajay0912.dpi@gmail.com*.

# Some of the Benefits and Drawbacks of this style of trading

1. As a worst case scenario, the model may end up trading 30 times in an hour resulting in huge Brokerage/Transactional charges.
2. The model is immune to sudden market reactions due to adverse news and speculations.
3. The model does not trade market noises which is an added benefit.
4. It does require low latency networks in order to execute orders properly.

Thanks for going through my project and I wish you to have a great day.
