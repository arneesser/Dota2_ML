# Dota2_ML
This mini project investigated a personally curious research question: Can we accurately predict the outcome of dota matches after 15 minutes of gameplay based off of team networth, experience (xp) gain, and last-hits alone? 

Dota 2 is a multiplayer online battle arena (MOBA) video game in which two teams of five players compete to collectively destroy a large structure defended by the opposing team known as the "Ancient", whilst defending their own. The dataset used is available on Kaggle at: https://www.kaggle.com/devinanzelmo/dota-2-matches?rvi=1

Several ML models were used to predict the outcome of the matches including: random forest, support vector machines (SVM), and logistic regression. The best models were found to achieve an F-1 score of 0.70 demonstrating that the nominated features do accurately predict match outcomes to a certain extent. Despite that, there is certainly room for more features that could improve the performance of the model which were not accounted for such as the heroes played, items bought and more. 

Feature importance extracted from logistic regression revealed that networth was most pertinent in determining winrate, followed by xp. Interestingly last-hits is a marginally negative co-efficient in predicting winrate.  
