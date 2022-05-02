# School_District_Analysis
## Overview of the school district analysis:
Maria, the chief data scientist for a city school, is working on the analysis of the standardized test performance of students from the schools in the district.
This data and analysis will be used by a School Board to make their decisions about budget allocation and other important matters.

There was a report that there was a fraud with the test performance of 9th grade students from Thomas High School so we corrected the dataset by replacing the corresponding scores with NaN.

## Results:
### Corrected Data Results
This is the summary of the data after the correction of replacing Thomas High School 9th Graders' scores with NaN

#### District Summary
![image](https://user-images.githubusercontent.com/99149443/166173538-726da35f-92c9-4e72-803d-4b3f825c80ad.png)
#### School Summary
![image](https://user-images.githubusercontent.com/99149443/166173804-cbb318eb-a329-4fa2-88f2-d0fe9cfb6823.png)

#### Top School and Bottom School
* Top 5 Schools  
![image](https://user-images.githubusercontent.com/99149443/166173817-b0e9932b-63e4-44d0-9374-b085e817eb62.png)

* Bottom 5 Schools  
![image](https://user-images.githubusercontent.com/99149443/166173825-4ee834f1-bf84-4d2f-beff-6cc79816d135.png)

#### Grade & Score
* Math  
![image](https://user-images.githubusercontent.com/99149443/166173848-08f64b40-90ef-4ffc-899c-b6fd2a961fa2.png)

* Reading  
![image](https://user-images.githubusercontent.com/99149443/166173879-4e17460b-451c-4e23-8231-9c34f78a95c3.png)

#### Budget & Score
![image](https://user-images.githubusercontent.com/99149443/166173925-839c6678-bf10-4eba-8eab-07bd96d8bd9a.png)

#### School size & Score
![image](https://user-images.githubusercontent.com/99149443/166173939-962e0378-38c8-4311-adb2-d615c3cbb236.png)

#### School type & Score
![image](https://user-images.githubusercontent.com/99149443/166174017-79bf1782-eae3-4c1d-87e6-531e13805d07.png)


### Trends & Insights
Based on the corrected dataset, the below trends were found.
* We can't see strong correlation between scores and grades, which means that higher grade students don't necessarily score higher than lower grade students.
* Regarding the spending per capita and scores, schools with lower budget seem to perform better at tests, which means that allocating more budget doesn't boost the performance and we should think of better ways to improve performance.
* Regarding the school size and scores, we can observe that there is no much difference between small and medium schools, however large schools score lower than small and medium schools especially at a math test. This probably is because that bigger schools cannot provide personalized and thorough support with each student because there are too many students.


## How does replacing the ninth graders score of Thomas High School affect the result?
Thomas High School's ninth graders' scores were fraudulently modified and as a result, the data before the correction was incorrect, and the correction affected the information available from the data.

#### Thomas High School's own performance
* The below is the comparizon of Thomas High Schools's performance before and after the correction.
* Thomas High School was the 2nd higest performer at overall pass % before the correction, however its place dropped.
* Even though Thomas High School is not in the top 5 anymore, it still shows quite high overall passing %, which is about 25% higher than the district average. 

|   |  Math  |　Reading |
| ---- | ---- |---- |
|  Before correction|83.418349|83.848930|
|  After correction|83.350937	|83.896082|

#### Scores by school spending
There is no much effect as the number of 9th graders from THomas High School is relatively small compared to the all students in the district.
* After the correction ![image](https://user-images.githubusercontent.com/99149443/166175984-f1ed58a8-cee1-454a-8105-ba6c32e4471b.png)

* Before the correction ![image](https://user-images.githubusercontent.com/99149443/166175974-70551278-f182-4c45-b3b8-bba8c8708fc4.png)

#### Scores by school size
There is no much effect as the number of 9th graders from THomas High School is relatively small compared to the all students in the district.
* After the correction![image](https://user-images.githubusercontent.com/99149443/166173939-962e0378-38c8-4311-adb2-d615c3cbb236.png)

* Before the correction ![image](https://user-images.githubusercontent.com/99149443/166175793-adec9aed-a481-4b8e-9023-a697f1fd1d73.png)

## Summary: 
* This correction affected Thomas High School's own performance data as its % of overall passing dropped after the correction.
* However, as the size of 9th graders of Thomas High School is relatively small compared to the total number of students in the district, thus, it didn't affect general trends that can be observed in other data.
