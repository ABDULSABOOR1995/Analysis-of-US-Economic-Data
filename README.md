# Analysis of US Economic Data & Building Dashboard Using Python
 ## Overview:
Extracting essential data from a dataset and displaying it is a necessary part of data science; therefore individuals can make correct decisions based on the data. In this assignment, we will extract some essential economic indicators from some data and then display these economic indicators in a Dashboard. We can then share the dashboard via a URL.

<b>Gross domestic product (GDP)</b> is a measure of the market value of all the final goods and services produced in a period. GDP is an indicator of how well the economy is doing. A drop in GDP indicates the economy is producing less; similarly an increase in GDP suggests the economy is performing better. In this project, we will examine how changes in GDP impact the unemployment rate by using data visualizations such as Line and Bar Charts or by finding a correlation between GDP & unemployment rate.

## Explanation:
Now we explain every step of our project in detail with screenshots.

## Table of Content:
[1. Data Collection](#l1)<br>
[2. Data Understanding](#l2)<br>
[3. Data Cleaning](#l3)<br>
[4. Data Visualization](#l4)<br>
[5. Comparison between GDP V/S Unemployment](#l5)<br>
[6. Creating Dashboard](#l6)<br><br>
[Conclusion](#conclusion)<br><br>

<a id='l1'></a>
### 1. Data Collection: 
First of all, we collect data from the given source. Since this project belongs to <b> Coursera Project</b>, So we use link provided by Coursera to read both csv files(gdp & unemployment).<br>

![Screenshot_8](https://user-images.githubusercontent.com/46135898/67658114-7d002a80-f97a-11e9-8c41-6d5d4bee485e.png)

![Screenshot_9](https://user-images.githubusercontent.com/46135898/67658125-838ea200-f97a-11e9-9c97-03fc833db071.png)
<a id='l2'></a>
### 2. Data Understanding:
Then we start understanding data by applying basic pandas statistical methods on dataframe.

![Screenshot_11](https://user-images.githubusercontent.com/46135898/67658138-8ee1cd80-f97a-11e9-9a5f-82df8497085e.png)

![Screenshot_12](https://user-images.githubusercontent.com/46135898/67658141-92755480-f97a-11e9-8bc6-c150ce48251a.png)
<a id='l3'></a>
### 3. Data Cleaning:
Now we prepare data for analysis by removing unnecessary columns exist in both tables(dataframes).

![Screenshot_13](https://user-images.githubusercontent.com/46135898/67658145-94d7ae80-f97a-11e9-983d-a36c
<a id='l4'></a>
### 4. Data Visualization:
Now its time to visualize data by creating Line and Bar charts for gdp and unemployement table.

![Screenshot_14](https://user-images.githubusercontent.com/46135898/67658147-96a17200-f97a-11e9-87ee-245410c2f955.png)

![Screenshot_15](https://user-images.githubusercontent.com/46135898/67658152-999c6280-f97a-11e9-8730-a8c3b2b7ed25.png)
<a id='l5'></a>
### 5. Comparison between GDP V/S Unemployment:
In this stage we compare both tables by visualizing them in line or bar charts and observe the result.

![Screenshot_16](https://user-images.githubusercontent.com/46135898/67658169-a620bb00-f97a-11e9-902f-f66416693723.png)

![Screenshot_19](https://user-images.githubusercontent.com/46135898/67658234-d0727880-f97a-11e9-8d29-ed71ae7845e4.png)
<a id='l6'></a>
### 6. Creating Dashboard:
In the end, we create dashboard of the result and save it with the name index.html.

![Screenshot_18](https://user-images.githubusercontent.com/46135898/67658216-c486b680-f97a-11e9-8ad3-0cc6b6e467bd.png)
<a id='conclusion'></a>
## Conclusion:
From the above data analysis, we can clearly observe that <b>when GDP goes over the Unemployment comes down and when GDP comes down, Unemployment goes over.</b> So the conclusion of <b> US Economic Data Analysis </b> is that <b>"Uemployment is inversely proportional to GDP"</b> 






