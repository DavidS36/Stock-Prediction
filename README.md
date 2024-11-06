# Stock Predictions
This is an "end-of-phase" project that I am conducting within the Flatiron School curriculum. For this project, I  will use the yahoo finance API to collect stock data and from there do the necessary research and modeling to create a stock projection model.


## Descriptive Analysis

My descriptive questions all have a relative theme, the idea was to find the most important sectors in the S&P 500 and then the most important companies within that those sectors

This can be seen quite clearly when taking a look at the questions that I asked:
- What sectors account for the most amount of companies on the S&P 500?
- What is the total Market Capitalization for each sector?
- What is the relation between Market Capitalization and the number of companies for each sector?
- What companies in the Technology sector account the most Market Capitalization?
- What companies in the Financial Services sector account the most Market Capitalization?
- What companies in the Healthcare sector account the most Market Capitalization?
- What companies in the Industrials sector account the most Market Capitalization?
- What companies in the Consumer Cyclical sector account the most Market Capitalization?
- What companies in the Communication Services sector account the most Market Capitalization?
- What companies in the Consumer Defensive sector account the most Market Capitalization?
- What companies in the Energy sector account the most Market Capitalization?
- What companies in the Real Estate sector account the most Market Capitalization?
- What companies in the Utilities sector account the most Market Capitalization?
- What companies in the Basic Materials sector account the most Market Capitalization?


## Inferential Analysis

Continuing onto my Inferential Analysis, I was curious to see if there were any significant relations between publicly available financial metrics and the closing price. So I performed the following hypothesis tests and got the following results
- Sector ANOVA
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company in each sector is equal. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company in each sector in NOT equal
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.
- High Trailing P/E Ratio vs Low Trailing P/E Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high trailing P/E Ratio is equal to a company with a low trailing P/E Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high trailing P/E Ratio is NOT equal to a company with a low trailing P/E Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Forward P/E Ratio vs Low Forward P/E Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high forward P/E Ratio is equal to a company with a low forward P/E Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high forward P/E Ratio is NOT equal to a company with a low forward P/E Ratio.
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.  
- High PEG Ratio vs Low PEG Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high PEG Ratio is equal to a company with a low PEG Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high PEG Ratio is NOT equal to a company with a low PEG Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.    
- High Trailing PEG Ratio vs Low Trailing PEG Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high trailing PEG Ratio is equal to a company with a low trailing PEG Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high trailing PEG Ratio is NOT equal to a company with a low trailing PEG Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Price-To-Book Ratio vs Low Price-To-Book Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Price-To-Book Ratio is equal to a company with a low Price-To-Book Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Price-To-Book Ratio is NOT equal to a company with a low Price-To-Book Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Debt-To-Equity Ratio vs Low Debt-To-Equity Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Debt-To-Equity Ratio is equal to a company with a low Debt-To-Equity Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Debt-To-Equity Ratio is NOT equal to a company with a low Debt-To-Equity Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Trailing EPS Ratio vs Low Trailing EPS Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high trailing EPS Ratio is equal to a company with a low trailing EPS Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high trailing EPS Ratio is NOT equal to a company with a low trailing EPS Ratio.
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.    
- High Forward EPS Ratio vs Low Forward EPS Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Forward EPS Ratio is equal to a company with a low Forward EPS Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Forward EPS Ratio is NOT equal to a company with a low Forward EPS Ratio.
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.  
- High ROE vs Low ROE
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high ROE is equal to a company with a low ROE. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high ROE is NOT equal to a company with a low ROE.
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.  
- High Gross Margin vs Low Gross Margin
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Gross Margin is equal to a company with a low Gross Margin. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Gross Margin is NOT equal to a company with a low Gross Margin.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Operating Margin vs Low Operating Margin\
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Operating Margin is equal to a company with a low Operating Margin. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Operating Margin is NOT equal to a company with a low Operating Margin.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Profit Margin vs Low Profit Margin
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Profit Margin is equal to a company with a low Profit Margin. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Profit Margin is NOT equal to a company with a low Profit Margin.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Quick Ratio vs Low Quick Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Quick Ratio is equal to a company with a low Quick Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Quick Ratio is NOT equal to a company with a low Quick Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Current Ratio vs Low Current Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Current Ratio is equal to a company with a low Current Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Current Ratio is NOT equal to a company with a low Current Ratio.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Enterprise-To-EBITDA Ratio vs Low Enterprise-To-EBITDA Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Enterprise-To-EBITDA Ratio is equal to a company with a low Enterprise-To-EBITDA Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Enterprise-To-EBITDA Ratio is NOT equal to a company with a low Enterprise-To-EBITDA Ratio.
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.  
- High Enterprise-To-Revenue Ratio vs Low Enterprise-To-Revenue Ratio
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Enterprise-To-Revenue Ratio is equal to a company with a low Enterprise-To-Revenue Ratio. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Enterprise-To-Revenue Ratio is NOT equal to a company with a low Enterprise-To-Revenue Ratio.
    - Result: We reject the null hypothesis. 
        - Although we are able to observe a significiant enough difference to reject the null hypothesis, we do not know the exact reason why this relation exists. We simply observe that it does exist.  
- High Free Cash Flows vs Low Free Cash Flows
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Free Cash Flows is equal to a company with a low Free Cash Flows. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Free Cash Flows is NOT equal to a company with a low Free Cash Flows.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
- High Total Cash Per Share vs Low Total Cash Per Share
    - The Null Hypothesis ($H_0$) states that the mean closing price for a company with a high Total Cash Per Share is equal to a company with a low Total Cash Per Share. The Alternate Hypothesis ($H_A$) states that the mean closing price for a company with a high Total Cash Per Share is NOT equal to a company with a low Total Cash Per Share.
    - Result: We fail to reject the null hypothesis. 
        - While there is a slight observed difference, it is not significant enough to attribute it to anything except chance.
     
## Modeling Process

### Step 1: Data Acquistion
The most simple step of my process. Using the S&P 500 Data, I was able to collect the tickers that I wanted to use for the modeling process. After that the S&P 500 data can be put away as the rest of my dat wwas collected via the yahoo finance API `yfinance`

### Step 2: Shotgun Method

Now that we have the data, lets perform some base line models and get a starting accuracy that we can eventually work our way up with. 

Introduction the shotgun method, the shotgun method is simply using a number of different basic machine learning models to preform relatively simple task. For my model, I used 3 different regression based models, RandomForestsRegressor, KNeighborsRegressor and LinearRegression. With these 3 models I established a base from which to work up from.

Although, this is also where my work with basic machine learning models comes to an end for this notebook, while I was able to get good a good base accuracy from the RandomForestsRegressor, that model won't help me predict new data (unsupervised learning) so from here I move onto deep learning and neural networks


### Step 3: Building a Neural Network

Obviously, if you read through the entire notebook you'd know that there was a lot in between the shotgun method and my working neural network but we dont have to go over that as its not related to the final result.

So the first thing to do is get your data, for me when building the model, I used Waste Management's stock WM. Now that you hav ethe historical stock data, next thing to do is scale the data so that the your model can read and predict upon it a little easier.

Once you have your data and have it scaled then starts the actual model building process. I decided to use a 5 layer model, these were my layers
- **LSTM (64 Units)**: This was my input layer, LSTMs are really useful for very noisy historical data which is exactly why I'm using two of them
- **Bidirectional LSTM (64 Units)**: The was the first 'hidden layer' in my model the idea was to continue the process sent by the input layer and then also include the bidirectional which can increase the models understanding of the data
- **Dense (64 Units)**: this was the lead into my output, To be completely honest, I'm not exactly sure why I initially added it to my model, but it worked and I wasnt going to take it out now
- **Droupout (0.5)**: Next I added a dropout layer to ideally reduce overfitting and allowed the model to get closer and closer to a well-fit model.
- **Dense (1 Unit)**: Lastly the output layer, simpley put, its time to condense all of the models results into a single number and that is exact what this layer did

Now that we have our model built, its time to train. For training I used 100 epochs and both early stopping and a learning rate reducer to acheive a well fit model. 

After fitting the model I wanted to see how close the model's predictions were to the actual stock data. So I created those predictions and grpahed them to visualize. They were looking very good so I continued on to the predictions for future stock data. 

I was able to achieve the future predictions using a rolling window. Basically the idea was that for each predicted value (1 day worth of stock in the future), the model will add that to its data that it uses to predict the next days stock. This made it so that I was able to predict however far into the future I would like and it wouldn't just continue looking at the same data.

### Step 4: Putting it All Together

Now that I have my model build and ready, the next and final step will be to create a function that can run the process from start to finish just by a push of a button, which is exactly what I did. 


## Conclusion:

This was a very difficult but real project, meaning this project had very real world implications that wouldnt just be that another bootcamp student did another project. If I was able to perfect this model, I would become a very rich person. That being said, my model isn't perfect. There is a lot of room for improvement when it comes to this project. 

All that aside, I still feel like I accomplished my goal of proving that a deep learning model can understand the trend and patterns of stock data and create semi-realistic predictions for how the stock market may continue to act in the near future.

Ideally, I would love to continue this project with more data and other daily metrics that would be feasable to use in a model like this.

Overall, I believe this project is not completed to its fullest and there is still much to be done before it this model is ready for real world implementation
