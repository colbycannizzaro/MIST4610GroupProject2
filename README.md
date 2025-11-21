# Group 5 Mist 4610 Group Project 2

## Team Name: 
62755 Group 5

## Team Members:

## Team Members:
1. Armaan Bhasin [@armaanbhasin](https://github.com/ArmaanBhasin698/Group5_ArmaanBhasin/tree/main)
2. Colby Cannizzaro [@colbycannizzaro](https://github.com/colbycannizzaro/MIST4610GroupProject1)
3. Evan Liu [@evanliu](https://github.com/evanl0l/4610)
4. Theresa Nguyen[@theresanguyen](https://github.com/theresaanguyen/MIST4610)
5. Allison Ramirez Diaz [@allisonramirezdiaz](https://github.com/agr56264/MIST4610-Group-Project-2/tree/main)
   
## Description of dataset:

This dataset consists of the total number of arrests and their characteristics in NYC by the NYD(New York Police Department) from January 1, 2025 to November 1, 2025.  The data is obtained from data.gov(https://catalog.data.gov/dataset/nypd-arrest-data-year-to-date) and reviewed by the Office of Management Analysis and Planning. Each record in the data is assigned an arrest key, which has a number(whole) data type. Following the arrest key is the arrest date with a date data type. There is also a 3-digit classification code(PD_CD) and a general 3-digit classification code(KY_CD), both of which are a number(whole) data type. Next are descriptions of the classification associated with each code(PD_DESC and OFNS_DESC) that are both String data type. There is also information on the law code charge, level of offense, and borough of arrest; these columns have String data types. Following this is the precinct the arrest occurred in and the jurisdiction code, both having number(whole) data type. Additionally, there are demographic columns covering the perpetrator’s age group, sex, and race that all have String data type. The dataset also includes the location of each offense by x-coordinate, y-coordinate, latitude, longitude, and point location. Both coordinates have a data type number(whole), latitude and longitude with data type geographic(latitude and longitude), and point location in data type String.

## Question 1:

Question: What is the relationship between borough and crime severity in New York City?

Importance: 

Understanding the relationship between borough and crime severity is important because it reveals not only how much crime occurs across New York City, but what types of offenses are driving those differences. Our analysis shows that misdemeanors make up the majority of arrests in every borough, suggesting a consistent citywide emphasis on lower-level enforcement. At the same time, meaningful variation emerges when we compare severity levels: for example, Brooklyn records more felony arrests than Manhattan, while Manhattan has relatively fewer serious offenses but a different mix of lower-level crimes. These differences likely reflect variations in population density, daily activity patterns, and borough-specific policing practices. By examining severity rather than total arrests alone, we gain a clearer understanding of how community characteristics and enforcement strategies shape public safety outcomes across the city. By knowing which boroughs have the highest rate of felonies, we can better allocate our resources to the areas that need it the most.

<img width="356" height="533" alt="image" src="https://github.com/user-attachments/assets/64507411-23a0-44f2-abdf-7405959978af" />


Our first graph illustrates the breakdown of each borough's crime rate by crime seveerity. The Bronx had the highest crime rate and highest number of felonies, while Staten Island had the lowest crime rate, and Queens had the lowest number of felonies. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 29 PM" src="https://user-images.githubusercontent.com/128402101/235008185-d248e12e-49bf-4666-a8d2-fa6aaeb646b9.png">

We excluded Saturday and Sunday because of their low incident reports and analyzed Monday - Friday. In this visualization, we look at how these different days experience drug violation incidents throughout the year. Our results represent similar trends between all five days, where there’s a spike in incidents in March, followed by a decline in April, leading to a steady increase throughout the summer, where drug violations reach their peak for all days in July/August. Then, the number of violations declines steadily throughout the remainder of the year. This information is useful to know so the police department ensures they have adequate staff for the higher demand on the job during the summer. Additionally, it is helpful for the public to be more aware of the fact that drug violations are more likely to occur during the summer so the public takes adequate safety measures and avoids areas that have a lot of drug violations likely to occur.

## Question 2:

Question: During what hours and in which districts does Boston have the most drug violations? For the district and hours with the most drug violations, what street is the most popular location for drug violations? 

Importance: 

This question is important because it enables the police and public to be aware of the districts that are most likely to have drug violations occur as well as the most popular times for drug violations to occur. With this information, the police department could deploy more officers to districts that are more likely to have drug violations as well as during peak hours likely for drug violations. It is more effective to deploy more officers during peak hours to efficiently utilize their services and economically be more worthwhile. Additionally, the public would feel safer if they know more extensive measures are being taken to keep them safe during peak hours in popular districts for drug violations. The second question builds on the last question’s revelations that district A1 has the most drug violations occurring between 14-22 hours (2 PM - 10 PM). From this insight, it is important to find the streets within district A1 that are most likely to have drug violations occur on. This would further help the police department to target streets to keep officers on during 14-22 hours. Additionally, the public would be more informed of what streets to avoid during 14-22 hours to be safer and further away from any possible drug violations. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 42 PM" src="https://user-images.githubusercontent.com/128402101/235008200-aa0fd1c7-8407-4eec-8faf-7e8458dc66f3.png">

In analyzing the count of drug violations by district and hour of day, we found that there is a peak in the trend line of most districts between the 14th and 22nd hour of the 24 hour period. This indicates that across virtually all districts, drug offenses spike between 2:00 pm and 10:00 pm, and the district with the most drug offenses during this time is district A1. 

<img width="1680" alt="Screen Shot 2023-04-27 at 6 57 50 PM" src="https://user-images.githubusercontent.com/128402101/235008216-fd327af8-4b38-4e01-8d4d-7dca8255246f.png">

After delving deeper into this finding, we found that of the streets in district A1 between the times of 2:00 pm and 10:00 pm, the street with the most drug violations is Boylston Street- with Washington, Tremont, and Beach streets trailing behind it. Thus, an appropriate course of action would be to increase police presence on Boylson St, Tremont St, and Beach St between 2:00 pm and 10:00 pm These findings are important and useful in that they can help law enforcement narrow down in which areas and during what times they should patrol more often or dispatch more units to, to help eradicate drug-related crime. Without this analysis, law enforcement may be wasting resources by patrolling the wrong areas or patrolling areas during times drug offenses are not even likely to occur. Utilization of these findings would improve the efficiency and effectiveness of law enforcement.

## Manupulations applied to the data set for analysis:

We did not have to manipulate any data, but we did have to standardize the data set. A standardized data set focuses on transforming raw data into usable information before it's analyzed. Our data fits that description as we have quantifiable data that can be measured and adheres to the standard of being meaningful, interpretable data. Our data also has no duplicate data, irrelevant data, redundant data, inaccurate data, or low-quality data. We also have cleansed the data, ridding it of any incomplete, irrelevant, or inaccurate data. On top of all of this, we have formatted our data and it contains no 3rd party imports.

## Tableau packaged workbook

The packaged workbook containing the visualizations shown above is attached to this repository.
