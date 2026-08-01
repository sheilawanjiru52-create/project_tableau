# Prevalence of Overweight and Obesity among Women across Kenyan Counties
## Introduction

Overweight and obesity have become major public health concerns in Kenya, particularly among women, increasing the risk of non-communicable diseases such as diabetes, hypertension, and cardiovascular disease. Recent evidence indicates that obesity prevalence varies considerably across counties, highlighting the need to understand the factors contributing to these differences. Among these factors, dietary habits play a significant role in influencing body weight and overall nutritional status. This project analyses county-level obesity and dietary consumption data to identify dietary patterns associated with overweight and obesity among women in Kenya. The findings aim to support evidence-based nutrition interventions and inform county-specific public health policies.

## Aim 

This project explores the relationship between dietary consumption patterns and overweight and obesity among women across Kenyan counties. By comparing healthy and unhealthy food consumption in counties with high and low obesity prevalence, the analysis seeks to identify dietary patterns that may be associated with obesity.

## Objectives

1.	To analyse the prevalence of overweight and obesity among women across Kenyan counties. 

2.	To compare healthy food consumption between counties with high and low obesity prevalence. 


3.	To compare unhealthy food consumption between counties with high and low obesity prevalence. 

4.	To identify dietary patterns associated with high and low obesity prevalence among women across Kenyan counties.


## Main Research Question

What is the relationship between dietary consumption patterns and the prevalence of overweight and obesity among women across Kenyan counties?

## Specific Research Questions

1.	How does the prevalence of overweight and obesity vary among women across Kenyan counties?

2.	How does the consumption of healthy food groups differ between counties with high and low obesity prevalence? 

3.	How does the consumption of unhealthy food groups differ between counties with high and low obesity prevalence? 

4.	Which dietary patterns are associated with high and low obesity prevalence among women across Kenyan counties?

## Method

### Microsoft Excel
•	Extracted county-level data from the 2021 survey report (PDF) into Excel. 
•	Cleaned and organised the data into structured tables. 
•	Created separate datasets for: 
o	Nutritional Status 
o	Food Analysis 
o	Diet Analysis 
o	Drink Analysis 
•	Checked for consistency in county names, removed errors, and saved each worksheet as a CSV file for SQL import. 

### SQL
•	Imported the CSV files into SQL as separate tables. 
•	Cleaned and validated the imported data. 
•	Joined the datasets using County as the common key. 
•	Created a consolidated dataset containing obesity prevalence and dietary variables. 
•	Queried the data to verify accuracy before exporting it for visualisation in Tableau. 

### Tableau
•	Connected Tableau to the processed SQL dataset. 

•	Built interactive dashboards to analyse overweight and obesity among women across Kenyan counties. 

•	Created: 

o	KPI cards (Highest county, Lowest county, Average obesity prevalence) 

o	County ranking bar charts 

o	Dynamic Top/Bottom county analysis 

o	Parameter-driven food selection for healthy and unhealthy food groups

o	Interactive filters to compare high-, middle-, and low-obesity counties 

•	Designed an interactive dashboard and a Tableau Story to present the findings. 

•	Analysed dietary patterns and identified relationships between healthy foods, unhealthy foods, and obesity prevalence across counties.

## Success Criteria

The project will be considered successful if it:

•	Successfully integrates county-level obesity and dietary data into a single dataset. 

•	Identifies counties with the highest and lowest prevalence of overweight and obesity among women. 

•	Compares healthy and unhealthy dietary consumption patterns across counties. 

•	Identifies dietary patterns associated with high and low obesity prevalence using interactive visualisations. 

•	Produces an interactive Tableau dashboard and story that allow users to explore county-level obesity and dietary trends. 

•	Generates evidence-based insights and recommendations to support county-specific nutrition and public health interventions.
