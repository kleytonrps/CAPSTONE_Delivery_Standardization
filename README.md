# Agronomic Data Scientist

Welcome to my portfolio, where I share my learning journey in business analytics. These projects show my growing skills in data analysis, predictive modeling, and making decisions based on data.

<details>
  <summary><strong>Education</strong></summary>
  
  <ul>
    <li><strong>Master of Science in Business Analytics</strong><br>University of Utah, Salt Lake City, UT, United States</li>
    <li><strong>MBA in Business and Entrepreneurship</strong><br>PUC RS, Porto Alegre, Brazil</li>
    <li><strong>Specialist in Soil Management</strong><br>Esalq USP, Piracicaba, Brazil</li>
    <li><strong>Bachelor's Degree in Agronomy</strong><br>UEL, Londrina, Brazil</li>
  </ul>

</details>

<details>
  <summary><strong>Work Experience</strong></summary>

  <ul>
    <li><strong>Inventory Data Manager</strong><br>The University of Utah Campus Store, April 2023-present</li>
    <li><strong>Founder/CEO/Senior Crop Advisor</strong><br>Apta Agribusiness, July 2010 - July 2023</li>
    <li><strong>Junior Crop Advisor and Precision Agriculture Analyst</strong><br>Insolo Agricultural Management, August 2004 - June 2010</li>
  </ul>

</details>
<br>
<hr>

 
## 1. Capstone Project 2025 - Delivery Standardization

[CAPSTONE Delivery Standardization RMarkdown code](https://github.com/kleytonrps/CAPSTONE_Delivery_Project/blob/main/CAPSTONE_Delivery_Standardization.qmd)

[CAPSTONE Delivery Standardization PDF](https://github.com/kleytonrps/CAPSTONE_Delivery_Project/blob/main/pdf%20files/CAPSTONE_Delivery_Standardization.pdf)


**Business problem and project objective**

The client needs a structured system to optimize logistics between its own fleet of Red Trucks and alternative delivery methods (ARTM), which include partner trucks and third-party carriers known as White Trucks. Red Trucks enhance customer relationships and contribute to revenue, while ARTM offers flexibility but limits interaction and control.

To ensure high-quality service and cost efficiency, I will establish clear fleet allocation guidelines based on customer profiles, transaction data, addresses, and delivery costs. This approach will determine the optimal truck type for each customer using a well-defined annual volume threshold. Additionally, customer segmentation will identify shared characteristics, enabling more strategic and data-driven decision-making.

Based on these insights, I will provide actionable recommendations to optimize fleet allocation and enhance operational efficiency.

 
**Analytics approach**

This analysis was conducted separately for two customer groups:

- All Customers – The broader customer base includes purchasing various product types.
- Local Market Partners Buying Fountain Only – Customers who purchase only fountain drinks, excluding CO2, cans, or bottles.

The goal was to address logistics challenges and transform decisions into data-driven solutions by combining predictive models with clustering techniques. This approach used both supervised and unsupervised learning methods to build a structured and efficient logistics framework.

Supervised learning techniques were applied to determine whether each customer should be served by Red Trucks or White Trucks (ARTM), based on a defined set of criteria. Additionally, a clustering analysis identified customer groups with similar consumption patterns, allowing for refined fleet allocation and enhanced decision-making rules.

<p align="center">
   <img src="https://github.com/kleytonrps/CAPSTONE_Delivery_Standardization/blob/main/plots/imagem%201.jpg" alt="Imagem 1" width="600" />
</p>

**Solution**

This project successfully integrated data-driven conclusions with business decisions, making the fleet assignment process one with significant potential for success. A key differentiator in this process was the feature engineering, which brought robustness to the models and generated consistent, reasonable impacts. Notably, the adaptation of RFM and the method developed for calculating customer growth stood out.

<p align="center">
   <img src="https://github.com/kleytonrps/CAPSTONE_Delivery_Project/blob/main/CAPSTONE_Delivery_Standardization/plots/imagem%203.jpg?raw=true" alt="Imagem 3" width="600" />
</p>

The established process was transparent, replicable, and simple, ensuring a clear understanding of the decisions leading up to the fleet assignment. For instance, the supervised models, Decision Tree and Multinomial Logistic Regression, were critical in explaining the variables that influenced customer segmentation. With their accuracy raised to nearly 90%, these models had the potential to predict segments for new customers, enhancing logistics efficiency and decision-making.

<p align="center">
   <img src="https://github.com/kleytonrps/CAPSTONE_Delivery_Project/blob/main/CAPSTONE_Delivery_Standardization/plots/plot%204.jpg?raw=true" alt="Plot 4" width="600" />
</p>


**Business Value**

The proposed fleet reassignment strategy has the potential to save approximately $770,000 for the company over the past two years. This is achieved by increasing the number of customers served by red trucks, optimizing their usage frequency, and reducing their volume by 3%, allowing for the eventual redeployment to strategic customers.

<p align="center">
   <img src="https://github.com/kleytonrps/CAPSTONE_Delivery_Project/blob/main/CAPSTONE_Delivery_Standardization/plots/plot%205.jpg?raw=true" alt="Plot 5" width="600" />
</p>

The proposal was fairly conservative, redesigning the delivery method for only 14% of the customers. It successfully assigned the fleet based on volume as well as several intrinsic customer characteristics. As a result, the expectation is that, after its implementation, there will be not only cost reductions but also an increase in sales, particularly for customers with greater growth potential. Furthermore, the proposal helped identify three main customer groups, two of which showed strong homogeneity.

When measuring the impacts of the new fleet assignment, the dining segment experienced the most significant changes, especially for local market partners classified as fountain-only. There was no major impact on the activities of sales representatives; however, there was a notable reduction in the volumes delivered by red trucks (-20%) when orders were placed via call centers. This outcome is favorable, as call center orders no longer have a strong connection with customers.


**Limitations, Improvements, and Lessons**

I participated in all stages of the project, leading discussions on the models and their business implications. I spent over 100 hours on it, applying my analytical skills to challenge the data.

One of the main limitations of this project was the short two-year historical data, which made it difficult to predict the future impact of the recommendation. Analytical approaches were challenging due to the wide probability ranges, meaning that any outcome was possible.

Another challenge was the asynchrony between customer orders, which made it hard to track individual customer growth tied to specific times of the year. With a longer historical series, we could have made more accurate future predictions.

The census data could have been better utilized. The way it was applied in this project didn’t deliver the expected results, but with adjustments and more historical data, it could provide valuable insights for future analysis.

It’s clear that predicting future growth, even with extensive data, is a complex task. These predictions should only be emphasized if the process is robust, with strong statistical support and a consistent range of possible outcomes. Otherwise, it might be better to refrain from highlighting them.

Looking ahead, I strongly recommend conducting further tests to measure the impact of fleet allocation and the way customers place orders. This will be crucial in validating or refining the current approach. Additionally, analyzing revenue could provide deeper business insights, especially in understanding margins across different customer segments.

A key takeaway from this project is that data doesn’t always provide all the answers we need for decision-making. In these cases, history shows that there will be both successes and setbacks, but decisions still need to be made. My role was to make responsible recommendations and take a clear stance, even when faced with uncertainties.


