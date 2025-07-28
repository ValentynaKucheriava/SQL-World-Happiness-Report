# SQL-World-Happiness-Report

The data used in this project is the [World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness) dataset from Kaggle. The goal of this project is to create data visualizations using **Power BI** and to write queries using **SQL Server**.

#### Question 1:  Top 10 Happiest Countries in 2018
```
SELECT TOP 10 
    CountryOrRegion, Score
FROM my.dbo.HappinessData2018
ORDER BY Score DESC;
```
