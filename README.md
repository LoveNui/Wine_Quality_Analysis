
## Wine Quality Analysis with Python, AWS and Tableau

Wine quality is an important factor for both producers and consumers. The goal of this analysis is to explore which factors have the most impact on wine quality for a given dataset. The dataset includes a variety of features that may influence wine quality, such as pH, alcohol content, and the presence of certain chemicals. By analyzing the data, we aim to identify the key factors that contribute to high wine quality, as well as any potential correlations or trends. This analysis will be useful for wine producers who want to improve the quality of their wines, as well as for consumers who want to make informed purchasing decisions.


## Data Description
The data for this analysis was sourced from the UCI Machine Learning Repository. It includes 12 variables and 6495 rows that may influence the target __"wine quality(0-10)"__, such as pH, alcohol content, and the presence of certain chemicals.

## Project Structure
  - Extract data from UCI ML Repo and store data to an S3 bucket on AWS
  - Using Python to identify the top 3 variables that have the strongest relationship with wine quality
  - Transform Data using AWS Glue and Athena using SQL
  - Load cleaned data from Athena to Tableau to perform analysis and make dashboards
  - Host a website on S3 to showcase analysis results and dashboards  

<img width="1089" alt="Screen Shot 2022-12-28 at 23 03 34" src="https://user-images.githubusercontent.com/89816441/209901972-190e51b4-f0d8-4463-b14f-1589adb401c0.png">

## 1. Data Extraction and storage
In this section, the data for red wine will be stored in the "red" bucket and white wine data in the "white" bucket
<img width="1264" alt="Screen Shot 2022-12-29 at 22 08 17" src="https://user-images.githubusercontent.com/89816441/210030475-f0a2b634-f1ad-4b74-ae27-269097277fe6.png">
## 2. Create Data Schema using AWS Glue
<img width="1307" alt="Screen Shot 2022-12-29 at 22 14 30" src="https://user-images.githubusercontent.com/89816441/210030771-a9a639b1-8d56-45df-8918-98d05668a7fb.png">

## 3. Transform Data using AWS Athena with SQL
<img width="1145" alt="Screen Shot 2022-12-29 at 22 17 25" src="https://user-images.githubusercontent.com/89816441/210030912-261b56cd-7cfa-450f-8346-b6c8a2bccfbe.png">

## 4. Connect AWS Athena with Tableau and build dashboards
<img width="1002" alt="Screen Shot 2022-12-29 at 22 24 32" src="https://user-images.githubusercontent.com/89816441/210031259-2db8199d-7b97-4ef6-8bb3-34f7cf8f322b.png">
<img width="1002" alt="Screen Shot 2022-12-29 at 22 24 58" src="https://user-images.githubusercontent.com/89816441/210031293-1360eeca-537d-4bb2-bf9c-603435af2e64.png">

## 5. Save dashboards into notebook and host website on S3 to showcase analysis results  
<img width="1132" alt="Screen Shot 2022-12-29 at 22 27 46" src="https://user-images.githubusercontent.com/89816441/210031478-b8c805fd-d686-4689-b2a8-6dd8999094b0.png">





