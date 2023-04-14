# Audrey Arocha

This portfolio is a summary of the analytics projects I have accomplished and contributed to while pursuing my Master's Degree in Business Analytics.

For a full view on all my public projects, you can access the same [here](https://github.com/audreyanne96).

---

# [Analytics Report on Expansion for European Sports Brand](https://github.com/audreyanne96/Hult-MBAN-Projects/tree/main/Python/Expansion%20Analysis%20for%20European%20Sports%20Brand)
- As part of the MBAN program in Hult, we were tasked to do an in-depth consumer analysis on a hypothetical European Sports brand.
### Business Problem and Scope
- A European sports clothes company seeks to expand its market presence beyond Europe and Central Asia. The company aims to identify potential regions and markets for its products and the most effective product types to establish brand recognition in those areas.
- **Regional Market Research** - The ideal region and country should have a sizeable and stable potential market. A specific jurisdiction within the region should be identified as a starting point.
- **Product Strategy** - The company needs a distinct strategy to establish its brand in the target region, including identifying the type of products in demand or a gap in the local market that can be taken advantage of.
### Findings and insights
- To identify the optimal regions, an analysis of *Leisure Time*, *Market Size*, and *Market Stability* were done. 
- The optimal regions were identified to be North America and the Middle East & North Africa. The United States and Canada are the optimal countries to start the expansion in North America, while the UAE is the optimal starting point in the Middle East & North Africa.

![](images/overallanalysis-regional2.png)

- For the North American market, California was the state with the most activity. Here, the most in-demand products are sports apparel, fan apparel for various sports teams, and golf apparel for women. The company should position its prices similarly to its competitors in the market.

![](images/uscademand.png)

- For the Middle East & North Africa market, the company should establish good relationships with existing platforms such as noon and Namshi, and focus on filling the gap for cotton/cotton blend sports and leisure apparel for women. The company should also position its prices similarly to its competitors in the market.

![](images/meuaedemand.png)

---

# [Analytics Report on Analyzing Customer Churn](https://github.com/audreyanne96/Hult-MBAN-Projects/tree/main/Python/Analyzing%20Customer%20Churn)
- This was a team project we did in Hult's MBAN program. Specifically to use machine learning to predict customer churn of a telecom company.
- Credit due goes to my other team members as well, namely: Pablo Guala, Maria Turbi, Artyom Blazko, Ayowole Delegab, and Cedric Sollie.
### Business Problem and Scope
- Company wants to improve customer retention by increasing the number of customers who exceed the current average of 32 months.
- Marketing Department wants to identify key factors that affect customer retention, such as personal characteristics, subscription type, and services offered.
- Goal is to develop a model to predict churn, target customers more effectively, and develop strategies to capture the right product-market fit.
- Overall objective is to reduce customer churn and increase customer retention.
### Findings and insights
- Developing the capability to predict customer churn is crucial to manage engagement terms and costs.
- **Logistic Regression**, **Decision Tree**, and **Random Forest** models were tested. A tuned **Random Forest Classification** model achieved the highest F1-score of 0.90, AUC of 0.9271 and 94% accuracy in predicting churn.

![](images/Confusion_Matrix1.png)
![](images/ROC.png)

- These were the top customer characteristics that were identified to have influenced churn the most.

![](images/top_features1.png)

- Based on the above findings, the team further recommended to focus on customers with short tenure, offering more benefits for longer contract lengths, bundling multiple services, offering additional benefits to customers with lower credit scores, and promoting loyalty among mid-high income customers.
