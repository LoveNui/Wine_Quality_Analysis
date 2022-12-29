
## Wine Quality Analysis with Python, AWS and Tableau

Wine quality is an important factor for both producers and consumers. The goal of this analysis is to explore which factors have the most impact on wine quality for a given dataset. The dataset includes a variety of features that may influence wine quality, such as pH, alcohol content, and the presence of certain chemicals. By analyzing the data, we aim to identify the key factors that contribute to high wine quality, as well as any potential correlations or trends. This analysis will be useful for wine producers who want to improve the quality of their wines, as well as for consumers who want to make informed purchasing decisions.


## Data Description
The data for this analysis was sourced from the UCI Machine Learning Repository. It includes 12 variables and 6495 rows that may influence the target "wine quality(0-10)", such as pH, alcohol content, and the presence of certain chemicals.

## Project Structure
  - Extract data from UCI ML Repo and store data to an S3 bucket on AWS
  - Using Python to identify the top 3 variables that have the strongest relationship with wine quality
  - Transform Data using AWS Glue and Athena using SQL
  - Load cleaned data from Athena to Tableau to perform analysis and make dashboards
  - Host a website on S3 to showcase analysis results and dashboards  

<img width="1089" alt="Screen Shot 2022-12-28 at 23 03 34" src="https://user-images.githubusercontent.com/89816441/209901972-190e51b4-f0d8-4463-b14f-1589adb401c0.png">
