# Melbourne Housing Market EDA(Exploratory Data Analysis) and Forecast (by Multiple Regression)

# General Information
>
>Author: Lucas Lobianco De Matheo
>
>Title: **Melbourne Housing Market**  
> - Melbourne housing clearance data from Jan 2018  
>  
>*This dataset was obtained from Kaggle*
>
> **Kaggle Context:**  
> This data was scraped from publicly available results posted every week from domain.com.au, I've cleaned it as best I can, now it's up to you to make data analysis magic. The dataset includes Address, Type of Real estate, Suburb, Method of Selling, Rooms, Price, Real Estate Agent, Date of Sale and distance from C.B.D.
>
>**Extension:** .csv
>
>**Source:** https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market  
>
>**Date:** 04-08-2022
>
> **Main Skills of this project:**  
> ***Part I***
> - **Exploratory Data Analysis - EDA**
> - **Data Cleaning**  
> - **Data Wrangling**  
> - **Data Visualization**  
> ## Objective:  
> Demonstrate important EDA processes  
> Understand the behavior of the realestate market  
>
> Prepare data to be analysed (Generating two datasets):  
>  - One for analytics and further analysis in PowerBI  
>  - Another for Machine Leraning Models  
>  
> ***Part II***
> - **Machine Learning**  
> - **Forecasting**   
> - **Time Series**  
> - **Regression**  
> - **Data Visualization**  
> 
> ## Objective:  
> Understand the behavior of the realestate market   
> Predict future prices  

![EDA](https://user-images.githubusercontent.com/10830272/183896945-a7daeea0-2dac-48a5-89f6-52362be7cdeb.png)  

>**At the end of EDA**  
>- Data types checked and corrected  
>- Distribution of data were analyzed  
>- Duplicate were removed  
>- Fixed anomalies  
>- Uninteresting attributes dropped  
>- Missing values fixed  
>- Clean data  
>- Outlier analysis  
>- Data transformation   
>- Correlation analysis performed  
>
>**Main Notes:**  
> - Two datasets were generated: One for analytics and another for Machine Learning  
>> As long the purposes are different the **data transformations** made in each dataset were also different, but both containing the same information.  
> - A lot of data were **missign** for important variables, including the target attribute.  
>> **paths used to handle missing data:**  
1 - Assess the importance of the attribute over the primary outcome.  
2 - Observe the percentage amount of missing data  
3 - Analyze the apparent reasons for the missing data  
4 - Choose a method to exclude data or impute values  
4|1 - For the target variable (Price) imputation by KNN was used, an interesting method of imputation, which I consider in many cases, more accurate than the mean, median or constant values.  
4|2 - It is still possible to use the values obtained by multiple regression, carried out in the other notebook of M.L. (not done here) 
>
> - Outliers were observed and excluded.
>> There are several ways to deal with outliers, they often carry important meanings for insights. However, more information is needed for such an analysis.  
>
> - Inconsistencies / Integrity of data
>> Some dates contained strange errors, such as building construction dates before the city's founding age. 

#Analytics | Business Intelligence  

![BI_1](https://user-images.githubusercontent.com/10830272/183897493-1cedcf5d-def0-4f2f-9ab6-ec99f21b383e.png)

![BI_2](https://user-images.githubusercontent.com/10830272/183897518-80ed70cb-0fde-4b79-81dd-fb96a59ae85b.png)

#Previsão por Regressão Múltipla

![Forecasting_ML](https://user-images.githubusercontent.com/10830272/183897800-6bef95a4-2ee8-4e82-8d88-2800d04a2f32.png)
