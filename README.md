# 📈 Kaggle Players Visualisation


![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power_Query-005E4E?style=for-the-badge&logo=microsoftexcel&logoColor=white)

## 📖 About
Exploratory analysis of players dataser 
![Dashboard Demo](./assets/gifs/Vizualizacja_power_bi.gif)

---

## 🚀 Keeping the long story short (TL;DR)
> [!IMPORTANT]
> Showing the importance of detailed visualisation of dataset and how simple measures badly affect your opinion


---

## 📊 Data set itsels

> Analyzed Data Set concerns selected sample of players. I' ve created some measures to make analysis easier and more meaningfull. Moreover I wanted to show the importance of validation, and critical thinking when it comes to basic statistical measures interpretaion.

### 1. Data Cleaning and modeling

> The first "quality" issue that I spotted was related to irregular evaluation of selected players during a year.
> Vaule of some players were evaluated once a year wherease value of the others were evaluated 6 times a years, what could make comparisons unfair.


![Valuation issue](Multiple_valuation_per_year.png)

> To overcome that issue I ' ve decided to aggregate the players valuation in a year perioids using max value as aggregation measure.

![Players aggregation](Players_aggreagtion_by_year.png)

### 2. Final Visualisation

> Front page of players visualisation dashboard below

![Players visualisation](./assets/Pictures/Players_front_dashboard.png)



> Picture below shows the importance of detailed analysis of dataset that you are dealing with.
> Relaying just on basics simple statistical parameters like mean and average could lead to wrong conclusions
For example the average value of Portugeese clubs players is similar to the value of players playing in Budesliga or Serie A, but it's worth to highlight ther significant less players from Portugeese league are present in analyzed dataset than 



![Basic statistical parameters](./assets/Pictures/Median_count_dashboard.png)



---

<p align="center">
  Created with ☕ and data 
</p>