# French-Grocery-Shopping-Insights-Association-Rule-Learning-for-Complementary-Products
Understanding consumer behavior is crucial for optimizing sales and marketing strategies in the grocery retail industry. Association rule learning is a powerful technique that enables us to uncover interesting patterns and relationships between products frequently purchased together. In this analysis, we delve into French grocery shopping data to identify complementary products that are commonly bought in tandem. By leveraging association rule learning algorithms, we aim to provide valuable insights that can assist retailers in enhancing their product placement, promotions, and assortment strategies. Let's explore the fascinating world of French grocery shopping and discover the hidden connections between everyday items! 🥖🧀🍷


![]((https://github.com/A-pradeep420/French-Grocery-Shopping-Insights-Association-Rule-Learning-for-Complementary-Products/blob/main/Apriori-Association%20Rule%20Learning.jpg))

📦 Introduction 🛒

This repository contains code and documentation for a fascinating project involving transaction data from a French grocery store. The dataset encompasses the purchases made by customers over the course of a week, revealing the various items bought together. Our objective is to employ association rule learning techniques to unearth valuable insights. By identifying the top 5 items frequently purchased together, we aim to assist the French store in crafting packages or strategically placing these items together to enhance customer experience and boost sales. Let's dive into the world of grocery shopping analytics and uncover meaningful patterns! 💼🍞🧀

# Skills/Concepts Developed
Exploratory Data Analysis (EDA)
Data Analysis
Data Transformation using Transaction Encoder
Apriori Algorithm Application
Association Rules Analysis

# Problem Statement
We have to learn the Association rules to help the French store determine the top 5 items that are bought together to help them make packages or place these items together.

# Modeling
1.Exploratory Data Analysis (EDA):
Conduct an initial exploration of the dataset to understand its structure, features, and distributions. 🕵️‍♂️🔍
Perform summary statistics, visualize data distributions, and identify any anomalies or patterns. 📊📈

2.Data Analysis:
Dive deeper into the dataset to extract meaningful insights and trends. 📉🔍
Analyze customer purchasing behavior, popular items, and transaction patterns. 🛒👥

3.Data Transformation using Transaction Encoder:
Prepare the transactional data in a suitable format for association rule learning. 🔄📝
Convert the raw dataset into a transactional format where each row represents a unique transaction. 🛍️➡️📋

4.Apriori Algorithm Application:
Apply the Apriori algorithm to identify frequent itemsets in the transactional data. ⚙️🔎
Determine the support threshold and mine frequent itemsets based on this threshold. 📊🛒

5.Association Rules Analysis:
Generate association rules based on the frequent itemsets discovered by the Apriori algorithm. 📜🔍
Evaluate and interpret the association rules using metrics such as support, confidence, and lift. 📊🔢
Select and prioritize the top association rules that are most relevant and actionable for the French grocery store. ⭐📋
These tasks collectively form a comprehensive analysis pipeline aimed at uncovering valuable insights from transactional data and providing actionable recommendations for the grocery store. 🛒🔍📊
# Visualization
Visualize the Association Rule Learning for Complementary Products gain insights into its Association Rule process.⭐📋

# conclusion


Top 5 Association Rules:

/usr/local/lib/python3.10/dist-packages/ipykernel/ipkernel.py:283: DeprecationWarning: `should_run_async` will not call `transform_cell` automatically in the future. Please pass the result to `transformed_cell` argument and any exception that happen during thetransform in `preprocessing_exc_tuple` in IPython 7.17 and above.
  and should_run_async(code)

	antecedents 	consequents 	antecedent support 	consequent support 	support 	confidence 	lift 	leverage 	conviction 	zhangs_metric
770 	(ground, tea) 	(green, beef) 	0.018264 	0.017731 	0.015731 	0.861314 	48.576807 	0.015407 	7.082677 	0.997635
771 	(beef, tea) 	(ground, green) 	0.018264 	0.017731 	0.015731 	0.861314 	48.576807 	0.015407 	7.082677 	0.997635
768 	(ground, green) 	(beef, tea) 	0.017731 	0.018264 	0.015731 	0.887218 	48.576807 	0.015407 	8.704724 	0.997093
769 	(green, beef) 	(ground, tea) 	0.017731 	0.018264 	0.015731 	0.887218 	48.576807 	0.015407 	8.704724 	0.997093
975 	(fries, whole) 	(french, wheat) 	0.017864 	0.018131 	0.015731 	0.880597 	48.568810 	0.015407 	8.223154 	0.997225

# Recommendations 🚀
. Further feature engineering may improve model performance.
. Consider experimenting with different machine learning algorithms for comparison.

# How to Use
1.Clone the repository to your local machine.
2.Install the necessary dependencies (e.g., Python, pandas, scikit-learn).
3.Run the provided Googlecolab Notebook or Python script to execute the code.
4.Follow the instructions within the notebook/script to perform data analysis and train the model.

# How to Use 🛠️
Clone the repository from GitHub. Install necessary dependencies specified in the requirements file. Follow the instructions in the README to set up and run the end-to-end pipeline. Credits 🌟 This project was developed by [A.Pradeep reddy], a Data Scientist with expertise in modeling. For questions or collaborations, contact [pradeep.sms420@gmail.com].

# About the Author ℹ️

[A.Pradeep reddy] is a [Data Scientist] with expertise in [Modeling]. Feel free to reach out for any questions or collaborations [pradeep.sms420@gmail.com]. 📧

Let's acknowledge the effort and expertise behind this project! 👏
