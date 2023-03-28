# Exploratory Analysis of Wine Testing Dataset

The case study on wine testing involves analyzing a dataset of over 100,000 wine reviews from different tasters around the world. The objective of the analysis is to understand the relationship between various attributes such as wine variety, country of origin, price range, and ratings.

The analysis involves using pivot tables, vlookup, countif, and averageif functions to group the data and calculate the average ratings, prices, and testing count of different wine varieties, tasters, and countries.

The findings of the analysis include identifying the top 10 wine varieties with the highest average ratings, the top 10 countries with the highest average wine prices, the top 10 wineries with the highest number of wine varieties, and the relationship between price ranges and ratings.

The analysis also involves creating visualizations in the form of charts and graphs to better understand the data and communicate the insights to stakeholders. Overall, the case study showcases the power of data analysis in the wine industry and how it can help improve decision-making and drive business success.


## Dataset link : https://www.mavenanalytics.io/data-playground?search=wine

### Dataset preview:
![image](https://user-images.githubusercontent.com/107685839/228315496-ab32c481-7974-4b63-a44d-ed4ed652ba43.png)


### 1. General overview of wine industry
This dataset provides information on 43 countries, 707 wine varieties, 16,757 wineries, and 19 distinct testers


![image](https://user-images.githubusercontent.com/107685839/228315811-48353ff2-397e-42f5-8289-e592647de7a8.png)

### 2. Determining the price of wine
I used the MAX and MIN functions in Excel to determine the highest and lowest prices of wines in the dataset, and used VLOOKUP to find the names of the wines with those prices. Through this process, I discovered that the price range of wines in the dataset is from $4 to $3,300, and the wine with the highest maximum price is the Bordeaux-style Red Blend.

![image](https://user-images.githubusercontent.com/107685839/228316849-14aea9fd-6f1e-4179-aaed-a00a4dd0bfd7.png)

### 3. Testing conducted by each taster
I utilized the COUNTIF and AVERAGEIF functions to determine the number of tastings conducted by each taster as well as the average rating they gave.

![image](https://user-images.githubusercontent.com/107685839/228317156-7fbae1df-9623-412b-a573-e752716e35e7.png)


### 4. Indian wines: price and rating
This table shows the average price and rating of wines from India. The average price of wines from India is $13.33 and the average rating is 90.22.

![image](https://user-images.githubusercontent.com/107685839/228318207-a77f2804-f6d5-4e45-aeb0-7de71b83aad7.png)

### 5. Top 10 countries by wine price
Used Pivot table to display the top 10 countries with the highest average price of wine.This information was then visually represented using a chart to better understand the price differences between each country. The countries are ranked based on their average wine prices, with Colares from Portugal having the highest average price followed by VÃ¢nju Mare from Romania and Switzerland. Other countries on the list include Madeira from Portugal, Moscatel do Douro from Portugal, Puente Alto from Chile, Buin from Chile, Rheingau from Germany, Champagne from France, and Santa Cruz from Argentina. These findings suggest that certain regions and countries are known for producing high-quality and expensive wines.

![image](https://user-images.githubusercontent.com/107685839/228318582-7073c9ed-aaba-4f45-86b7-1eb8e90a4fd8.png)

### 6. Top-rated wine varieties
Using a pivot table, I grouped the wines by their variety and calculated the average ratings. I then created a chart to visually represent the top-rated varieties, which include Tinta del Pais, Terrantez, and Gelber Traminer, all with a rating of 95.

![image](https://user-images.githubusercontent.com/107685839/228319123-7e12df24-704c-4de3-9fb2-7168e90bfd88.png)

### 7. Top wineries' wine variety count
I used a pivot table to count the number of wine varieties produced by the top 10 wineries in the dataset.

![image](https://user-images.githubusercontent.com/107685839/228319581-cb20e7f6-9841-4089-8759-cb0ec5d934f2.png)

### 8. Visualizing expensive wines by country
I used a pivot table to analyze the wine dataset and identify the most expensive wines along with their prices. I then created a chart to visually represent this information. To provide additional functionality, I also added a slicer to allow users to filter the data by country.

![image](https://user-images.githubusercontent.com/107685839/228319900-91fb2b46-249b-4ebf-ab32-8dd38dccc8f0.png)


### 9. Top 10 winery countries analyzed
I used a pivot table to determine the number of wineries in each country, and the result is the top 10 countries with the highest count of wineries.

![image](https://user-images.githubusercontent.com/107685839/228320171-116b28d1-6f09-4c80-bb41-9d5c941fafad.png)

### 10. Correlation between price and rating of wine
This pivot table shows the average rating of wines grouped by price range. As the price range increases, so does the average rating, with the highest average rating of 96.36 given to wines in the $800-899 price range. However, there are some exceptions, such as the $1500-1599 range, where the average rating is 100.

![image](https://user-images.githubusercontent.com/107685839/228320657-510b7e61-d33b-4817-8789-9f78cd417697.png)


### 11. Highest rated wine described
I used a pivot table to display the average rating and count of wines for each variety, specifically highlighting the Sangiovese Grosso variety. This variety was chosen as it has the highest rating among wines that have undergone more than 500 tests. Additionally, a few descriptions of wines under this variety were included in the analysis.


![image](https://user-images.githubusercontent.com/107685839/228325203-4421afcf-9a53-4eee-9994-04372a4dfb0e.png)

### 12. Lowest rated wine described
I utilized a pivot table to identify the wine variety with the lowest average rating and then narrowed it down to the least ranked wine with more than 500 tests conducted. The resulting table shows Pinot Grigio as the variety with the lowest average rating of 86.24 out of 100, with a total of 1,052 wines tested. The table also includes descriptions of some of the tested wines, which have received ratings as low as 80, indicating poor quality and flavor profile, including being overly sweet or lacking in depth and complexity.

![image](https://user-images.githubusercontent.com/107685839/228326048-eee0f2b0-3d2f-44ca-a1b7-b8f750bedf19.png)


