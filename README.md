Data description: 

**Final_stock_news.csv** - Created sentiment with multiple news channels and Kaggle data. Date range: 2023-2025.
Used further for matching calendar days with trading days. 

**sentiment_indicator_stock.csv** - The file contains Financial Indicators and trading day's stock sentiment based on T and T-1, where T is the last trading day. 

**requirements.txt** - Requirede files

**STEPS FOLLOWED:**
1) Stock sentiment creation as per trading days (Not calendar days)
2) Optuna Hyperband optimization to find the best params
3) Trained the TFT model with the best params.
4) SciPy optimization on the final TFT return-based model
5) Also explored other methods of optimization, like Reinforcement learning (PPO)

OUTPUT: 
<img width="819" height="839" alt="image" src="https://github.com/user-attachments/assets/82dfb77b-5871-439f-85ed-f6612a1dfb8a" />
