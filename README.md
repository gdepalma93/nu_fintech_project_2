# Mantis Shrimp Project
## "An Algorithmic CryptoInvestment System"

This project leverages the following skills learned in the NU Fintech Bootcamp.
    - Financial Programming
        - Python, Pandas, Matplotlib, API Interactions
    - Machine Learning Applications in Finance
        - Algorithmic Trading, Financial Modeling, 
        - Lasso Regression, LSTM Regression, Random Forest Regression
        

Objectives
    - Maximize Risk Adjusted Returns given the available python libraries, shrimpy api client for algorithm development and execution, data from cryptocompare and quandl feature selection, spyder as an IDE,  and the ML code and Engineering learnings from the NU Fintech Bootcamp. 
    - Simulate a Quant trading desk
    - Use a multi-factor regression/prediction model for signal generation
    
--- 
## ML Problem Formulation

    1. Articulate your problem
        - maximize risk adjusted algorithmic trading returns using skills learned in NU Fintech class
        - simulate a quant trading desk
        - machine learning- multi-factor Regression model (gradient boosters, random forests, logistic regression)
    2. Start Simple
        - factor research notebook 
            - universe selection
                - cryptocurrencies
                    - kraken
            - signal generation
                - btcusd Pct_change (velocity, acceleration)
                - [alt]btc pct_change (velocity, acceleration)
                
            -                 
                - sentiment calculus- (ibm-tone analyzer, nltk-intensity analyzer), event 
                - momentum cross sectional- (long only)
                - technical- ema cross, volatility cross, rsi_cross
                - fundamental- factor-based investing (crypto clustering homework)
        - algorithmic trading framework
            - initialize
            - build dashboard
            - fetch data
            - generate signals
            - execute_trade_strategy
            - evaluate metrics
            - execute backtest
            - main
        - train system with ML Model to optimize for risk adjusted returns (regularization modeling)
        - implement trading framework on AWS (Sagemaker) // deploy on spyder or visual studio or pycharm
        - automate performance reporting pipeline ()
    3. Identify Data Sources
        - Shrimpy- crypto price data
        - Quandl- 
        - crypto compare - fundamental signal
    4. Design Data For Model
        - multi-level dataframe
    5. Determine where data comes from
        - shrimpy, newsapi, twitter
    6. Determine easily designed inputs
        - shrimpy, newsapi, twitter
    7. ability to learn
        - random forest, gradient boosters, logistic regression, 
    8. Potential bias
---
## Solution
    1. Data Pre-processing
    2. ML Research and Feature Selection
    3. Algorithmic Trading Dev
    4. Performance Testing
    5. Ux
        
---     
## Presentation Slides
    1. Goal: Maximize Risk Adjusted Returns given the available python libraries, shrimpy api client for algorithm development and execution, data from cryptocompare and quandl feature selection, spyder as an IDE,  and the ML code and Engineering learnings from the NU Fintech Bootcamp. 
    2. Differentials -[projected risk adjusted returns(back tests, research goals(12wk Performance Test)), Dynamic Risk Management, Automation, Multi-Factor Signaling]
    3. Methodology- [1. Data Prep 2.ML Research and Feature Selection 3.Algorithmic Trading Development 4. Performance Testing, 4. Software UX]
    4. Software Architecture Diagram, Data Flow Diagram
    6. Strategy Diagram
    7. Areas to improve- [data prep, Factor research, algo dev, Performance Testing, Software UX]\
    8. Ask...? investment? funding? 
        - 100k gradient funding x 2% mgmt fee and 25% profitshare from Prop Trading Desk  where k=2 , n=12, 
        - 400k seed funding for crypto web app (Start Up)
        - 1 cohort of 10 clients at 50% profitshare (Consultant)
      
---
## Resources
### NU Fintech Notebooks
    - random forest trading (Signal, training, trading)
    - logistic regression notebooks
    - gradient booster notebooks
    - lstm-tensorflow-keras notebooks


## Links

## Northwestern Fintech Resources

[NU Fintech Project 1: A Quantitative Trading System](https://github.com/gdepalma93/quantitative_trading_system)  
[NU Fintech Curriculum](https://media.trilogyed.com/Northwestern/pdf/fintech/NU_FinTech_curriculum_102419.pdf)  
[LSTM Predictor Hw solution](https://www.youtube.com/watch?v=7zwCrBMwIUA&feature=youtu.be)  


### Machine Learning Resources
---
[problem formulation](https://developers.google.com/machine-learning/problem-framing/formulate)
[python pandas multiindexing](https://pandas.pydata.org/pandas-docs/stable/user_guide/advanced.html)
[iterate over rows in pandas](https://stackoverflow.com/questions/16476924/how-to-iterate-over-rows-in-a-dataframe-in-pandas)   
[l1 and l2 regularization methods](https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c)   
[stock prediction: random forest regressor](https://github.com/ThomasRochefortB/SP1500stockPicker/blob/master/SP1500stockPicker.ipynb)    
[regularization methods](https://towardsdatascience.com/how-to-improve-a-neural-network-with-regularization-8a18ecda9fe3)  
[lasso, ridge, elastic net ML](https://www.geeksforgeeks.org/lasso-vs-ridge-vs-elastic-net-ml/)   
[nueral networks for regression](https://missinglink.ai/guides/neural-network-concepts/neural-networks-regression-part-1-overkill-opportunity/)  

[random forest regression](https://www.geeksforgeeks.org/random-forest-regression-in-python/)   
[multivariate forecasting with LSTM Keras](https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/)  
[time series forecasting with LSTM](https://machinelearningmastery.com/time-series-forecasting-long-short-term-memory-network-python/)   
[multi-step forecasting with LSTM](https://machinelearningmastery.com/multi-step-time-series-forecasting-long-short-term-memory-networks-python/)   
[tuning hyper parameters of estimators](https://scikit-learn.org/stable/modules/grid_search.html)  
[BTC LSTM Prediction](http://www.quantatrisk.com/2020/04/01/how-to-predict-bitcoin-price-deep-learning-lstm-network-python/#:~:text=Design%20and%20train%20the%20LSTM,the%20entire%20test%20data%20sample.)  
[Weight regularization with lstm forecasting](https://machinelearningmastery.com/use-weight-regularization-lstm-networks-time-series-forecasting/)   
[Tune LSTM Hyperparamets with Keras for Forescasting](https://machinelearningmastery.com/tune-lstm-hyperparameters-keras-time-series-forecasting/)  
[Different Batch Sizes whe training and predicting with lstms](https://machinelearningmastery.com/use-different-batch-sizes-training-predicting-python-keras/)  





### Quantitative/algorithmic Trading Resources
---
[shrimpy github](https://github.com/shrimpy-dev/shrimpy-python)  
[shrimpy developer](https://developers.shrimpy.io/docs/?python#rebalancing) 
[shrimpy](https://www.shrimpy.io/)  
[shrimpy x coinbase](https://blog.shrimpy.io/blog/python-scripts-for-coinbase-pro-market-data)  
[shrimpy trading bot](https://blog.shrimpy.io/blog/how-to-make-a-crypto-trading-bot-using-python)  
[shrimpy api](https://blog.shrimpy.io/blog/how-to-make-a-crypto-trading-bot-using-python)  


[alphalens](https://www.quantopian.com/docs/api-reference/alphalens-api-reference#alphalens.utils.get_clean_factor_and_forward_returns) 
[blueshift](https://blueshift.quantinsti.com/research/strategies/3a32abeec97fa9cd5b7ee4f038d208d8/edit) 
[kraken](https://www.kraken.com/)  
[bittrex](https://bittrex.com)  
[coinbase pro](https://pro.coinbase.com/)  
[3 line backtest](https://towardsdatascience.com/backtest-your-trading-strategy-with-only-3-lines-of-python-3859b4a4ab44)  

[trading view](https://www.tradingview.com/chart/ZCmPZo4J/)  





### Crypto Research Resources
---
[cryptocompare](https://www.cryptocompare.com/)  
[s2f](https://medium.com/@100trillionUSD/modeling-bitcoins-value-with-scarcity-91fa0fc03e25)  
[heart capital research](https://github.com/gdepalma93/heartcap/blob/master/Market_Research.ipynb)  







