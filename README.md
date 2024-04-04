# Predict Customer Clicked Ads Classification by Using Machine Learning
Classification Model for Customer Clicked Ads Prediction

## Background
In the continuously evolving digital marketing world, understanding user behavior is crucial. Understanding how users interact with online advertisements is key to the success of campaigns. The project "Predict Customer Clicked Ads Classification in Python" aims to develop a classification model using machine learning techniques to predict ad clicks. The data used includes various features such as demographics, viewing time, and ad content. Through comprehensive data analysis processes, it is expected that the resulting model can provide valuable insights for companies. Thus, companies can enhance the effectiveness of their ad campaigns and optimize ad budget allocation more accurately.

## Objectives
The objective of this project is to develop a classification model using machine learning to predict ad clicks, enhance understanding of user behavior towards digital ads, and provide valuable insights for companies to optimize ad campaigns and marketing budget allocation.

## Research Questions
1. How can we use machine learning techniques to predict user behavior in clicking digital ads and what are the biggest factors that make people click on ads?
2. What insights can be gained from this dataset and machine learning, and what business recommendations can be provided?
3. What Business Simulations can be provided to provide an overview of the benefits of this machine learning model?

## Data and Assumptions
The dataset used can be downloaded from [dataset source](https://drive.google.com/file/d/1WwLxmK8PMLjjgG_Zh1Nkh02ZN2-3Wiyl/view). The assumption in this research is that the processed data belongs to one of the Companies in the world, although I cannot confirm whether the data is valid or not because here I ONLY process the dataset.

## Data Analysis
In this project, several Python libraries such as Pandas, NumPy, and Matplotlib are used to perform data analysis. The file `Predict Customer Clicked Ads Classification.ipynb` presents the detailed analysis steps. However, here I will only display the results of the data analysis according to the research questions that have been made, and for the analysis steps, it can be seen in the file `Predict Customer Clicked Ads Classification.ipynb`.

1. Machine Learning
   - Data Cleaning

      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%201.png)
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%202.png)

   - Changing Data Types
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%203.png)

   - Changing feature names
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%204.png)
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%205.png)
   
   - Performing Feature Encoding
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%206.png)
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%207.png)
      
   - Performing Feature Extraction
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%208.png)

   - Selecting features for modeling
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%209.png)

   - Performing train-test split
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2010.png)
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2011.png)

   - Performing Normalization
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2012.png)

   - Modeling
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2013.png)

   - Creating Confusion Matrix 
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2014.png)
      
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2015.png)

   - Finding out Feature Importance

      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2016.png)

2. Insights
   - Relationship between Age and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2017.png)

      Conclusion: From the above graph, it can be observed that older individuals are more likely to click on ads than younger individuals, possibly because younger individuals are more cautious in clicking on ads.

   - Relationship between Daily Internet Usage and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2018.png)
   
      Conclusion: People who spend less time on the internet tend to have a higher tendency to click on ads compared to those who spend more time on the internet.
   
   - Relationship between Daily Time Spent on Site and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2019.png)
   
      Conclusion: People who spend less time on the Company's Site tend to have a higher tendency to click on ads compared to those who spend more time on the Company's Site. This is because people who spend more time on the company's site usually visit the site directly rather than clicking on ads, so their percentage of ad clicks is likely lower.
   
   - Relationship between Area Income and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2020.png)
   
      Conclusion: There are two groups, individuals with an income of approximately +-450 million per year and individuals with an income of approximately +-350 million per year. The first group has a higher click percentage.
   
   - Relationship between Daily Internet Usage, Daily Time Spent on Site, and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2021.png)
   
      Conclusion: People who fall into the category of spending less time on the internet and less time on the company's site tend to have a higher tendency to click on ads than vice versa.
   
   - Relationship between Daily Internet Usage, Age, and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2022.png)
   
      Conclusion: Individuals who spend less time on the internet and have a tendency to click on ads are predominantly older individuals (+- 40 years old), while individuals who spend more time on the internet and have a tendency not to click on ads are dominated by younger individuals (+- 30 years old).
   
   - Relationship between Daily Time Spent on Site, Age, and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2023.png)
   
      Conclusion: Individuals who spend less time on the Company's Site and have a tendency to click on ads are predominantly older individuals (+- 40 years old), while individuals who spend more time on the company's site and have a tendency not to click on ads are dominated by younger individuals (+- 30 years old).
   
   - Relationship between Area Income, Age, and Clicked on Ad
   
      ![Data Results](https://github.com/AzamFath/predict-customer-clicked-ads-classification/blob/main/fig%2024.png)
   
      Conclusion: Individuals with an income of +-300 million per year and have a tendency to click on ads are predominantly older individuals (+- 40 years old), while individuals with an income of +-400 million per year and have a tendency not to click on ads are dominated by younger individuals (+- 30 years old).

3. Business Simulation

   Conversion Rate with No Model: 147/300 = 49%

   Conversion Rate with Model: "[Confusion Matrix]" : 144/148 = 97.3%

   In the business simulation, we will consider two scenarios based on the results of the machine learning model. The first scenario is without using the machine learning model (baseline), and the second scenario is by implementing the recommendations generated from the machine learning model. We will consider the impact of increasing the conversion rate on the profit from the marketing campaign. Let's assume the marketing costs remain constant, and we want to evaluate how the increase in the conversion rate can affect business outcomes.
   
   We will use the following parameters in the simulation:
   
   - Number of Users (Visitors): Here we use the test data as a simulation tool, which is 300 Users.
   - Marketing Cost: The allocated marketing cost is Rp.10,000 per User.
   - Conversion Rate: The conversion rate is the percentage of visitors who click on the ad. The baseline value is 49%, and the estimated value based on the model results is 97.3%.
   - Revenue per Conversion: The revenue earned per conversion (visitor who clicks on the ad) is Rp.14,000.
   
   Scenario 1 (Without Machine Learning Model):
   
   - Number of Users: 300
   - Marketing Cost: Rp.10,000
   - Conversion Rate (Without Model): 49%
   - Revenue per Conversion: Rp.14,000
   - Revenue: Number of Users x Conversion Rate x Revenue per Conversion
   - Cost: Marketing Cost
   - Profit: Revenue - Cost
   
   Scenario 2 (With Machine Learning Model):
   
   - Number of Users: 300
   - Marketing Cost: Rp.10,000
   - Conversion Rate (With Model): 97.3% based on model results
   - Revenue per Conversion: Rp.14,000
   - Revenue: Number of Users x Conversion Rate x Revenue per Conversion
   - Cost: Marketing Cost
   - Profit: Revenue - Cost
   
   With these parameters, we can calculate the cost, revenue, and profit for both scenarios:
   
   Scenario 1 (Without Machine Learning Model):
   
   - Revenue = 300 x 49% x Rp.14,000 = Rp.2,058,000
   - Cost = 300 x Rp.10,000 = Rp.3,000,000
   - Profit = Rp.2,058,000 - Rp.3,000,000 = -Rp.942,000 (loss)
   
   Scenario 2 (With Machine Learning Model):
   
   - Revenue = 300 x 97.3% x Rp.14,000 = Rp.4,086,600
   - Cost = 300 x Rp.10,000 = Rp.3,000,000
   - Profit = Rp.4,086,600 - Rp.3,000,000 = Rp.1,086,600 (Profit)

## Conclusion
The analysis results indicate that:

1. From the above analysis, it can be seen that the biggest factors determining whether someone will click on an ad from this dataset are Daily Internet Usage, Daily Time Spent on Site, Area Income, and Age.

2. From the above analysis, it can be seen that there are 2 groups in this dataset:
   1. A group aged around 30 years old who spend more time on the internet, spend more time on the company's site, and have an income of around 400 million per year. This group is less likely to click on ads.
   2. A group aged around 40 years old who spend less time on the internet, spend less time on the company's site, and have an income of around 300 million per year. This group is more likely to click on ads.

3. From the above analysis, it can be seen that in the first scenario, there is a loss, but in the second scenario with the machine learning model, we gain profit. **This indicates that by implementing the model recommendations, we can gain profit in marketing campaigns.**

## Recommendations
Based on the analysis results, some recommendations that hotel business owners can consider are:

1. Focus on the older age group around 40 years old, as they are the group that frequently clicks on ads.
2. Create more appealing ads for the younger age group around 30 years old (targeted ads) to encourage them to click on ads.
