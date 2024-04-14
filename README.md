# Instacart-Online-Grocery-basket-Data-Analysis
## About the Project
Huge demand and potential for online ecommerce. Companies have been leveraging data analysis to understand customer behavior, market trends, and machine learning for product recommendations. 
In this project, we analyzed online grocery shopping data to gain insights about customer purchase and market trends. 
Further we built a product recommender system that recommends products for a given user based on the available order history and similar user ratings. 
![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/90329b63-9f0a-403f-8ae4-4ec48d7b7c15)
Dataset:
An online grocery shopping dataset is taken from Kaggle for the project.  This can be found at: [link to dataset](https://www.kaggle.com/yasserh/instacart-online-grocery-basket-analysis-dataset)

The dataset consists of 5 CSV files, each file describing a different aspect of the data including aisles, departments, orders, products and order behavior.

Size of the dataset is 1.28 GB with around 3.4 Million user transactions recorded. However, after merging the data files in Spark, the size of the dataframe is 3.6+ GB.
## Tools used
![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/99845811-b705-48c5-9e48-76bd4affdbac)
![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/99000455-5665-4eae-b273-8d636d9b263a)
![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/a84814fc-b1c1-4eeb-a714-d8366e9d5b11)
![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/1314742e-2ec7-4c0b-a67c-640ab87a1fad)

## Phases of project
1.Import CSV files to MongoDB
2.Import data from MongoDB to Spark
3.Perform Exploratory Data Analysis (Last stage mentioned in the Progress Report)
4.Build a Recommender System based on the user purchase history and similar user ratings
5.Create visualizations using Tableau

## Results
![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/c0177a65-918d-4def-8e0b-98352ae78793)


![image](https://github.com/BhuvanaTerala/Instacart-Online-Grocery-basket-Data-Analysis/assets/159866484/848f5246-9662-4c5a-a66b-52334a67bb68)


## Conclusion
1. Consumer trends were identified by performing EDA on the data using PySpark and SparkSQL
2. A rating system was developed to generate user ratings for the available products
3.Based on these ratings, a recommender system was built using the Collaborative filtering method in Spark MLlib
4. A dashboard of consumer trends was built on Tableau





