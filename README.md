# Airlines-python-EDA-Seaborn

# Overview
This project explores an airline dataset containing information about passengers, flights, airports, and flight statuses. The goal is to gain insights and answer relevant questions through data visualization and statistical analysis.


## The dataset includes the following features:
**Passenger details** (e.g., age, gender)
**Flight information** (e.g., departure time, arrival time)
**Airport details** (e.g., location, IATA code)
**Flight statuses** (e.g., delayed, on time)

# Key Questions
## How much number of males and females passengers in the dataset?
By compared the number of males and females in a dataset. It shows that the numbers are comparable, with males being slightly higher. Specifically, there are 49,598 males and 49,021 females. This data could be useful for demographic analysis or understanding gender distribution within the dataset.
The code uses the seaborn library to create a KDE plot for an ‘Age’ feature in a dataset, with separate curves for each gender. The plot has ‘Age’ on the x-axis and ‘Density’ on the y-axis, with two curves peaking around the same age, indicating a similar age distribution for both genders. The blue and orange curves represent male and female genders, respectively. This type of plot is useful for visualizing the distribution of a variable and comparing groups within the data. 
## What are the top 10 nationalities represented in the dataset ?
Table of nationalities and their corresponding counts. The table lists the top 9 nationalities by count, with China having the highest count at 18,317, followed by Indonesia with 10,559, and so on down to the United States with 2,105. This data represents the frequency of different nationalities within a particular dataset and could be used for demographic analysis or other statistical studies.

## Which nationalities have the lowest number of passengers in the dataset?
A list of countries or territories with corresponding counts next to them, ranking from 237 to 234. It appears to be part of a larger dataset tracking statistics by nationality. The list includes less commonly known places like Norfolk Island and Svalbard and Jan Mayen, indicating a comprehensive dataset that includes small or remote locations. The counts range from 1 to 2 for the nationalities shown in this excerpt.

## Which airports have the highest number of passengers in the dataset?
Listing airports and their corresponding passenger counts. The airports are ranked from 0 to 9, with San Pedro Airport at the top with 43 passengers and Bathurst Airport at the bottom with 27 passengers. The counts suggest the frequency or volume of passengers handled by these airports. This data could be useful for analyzing airport traffic or planning logistics.

## Which nationalities have the smallest number of passengers in the dataset?
Listing various airports with a count next to each, which likely represents a certain quantity related to the airports, such as the number of flights or passengers. The table includes airports like Falcon State Airport, Hiroshima Airport, and Camaxilo Airport, with counts ranging from 1 to 2. This data could be useful for analyzing airport activity or for geographic studies.

## Which countries have the most total airline passengers?
List of countries ranked by a numerical count, likely representing a specific metric or quantity related to each country. Here’s the summary in words:
**United States:** Has the highest count of 22,104.
**Australia:** Follows with a count of 6,370.
**Canada:** Is third with 5,424.
**Brazil:** Fourth with 4,504.
**Papua New Guinea:** Fifth with 4,081.
The list continues with China, Indonesia, Russian Federation, Colombia, and India, which has the lowest count of 1,486 among the top ten listed. This data could be used for various analyses, such as comparing the metric across these countries or understanding the distribution of a particular phenomenon.

## What is the distribution of airline passengers by continent?
a table of data listing various continents along with a numerical count for each. Here’s the information conveyed in the table, presented in words:
**North America:** Has the highest count with a value of 32,033.
**Asia:** Follows with a count of 18,637.
**Oceania:** Is next with a count of 13,866.
**Europe:** Has a count of 12,335.
**Africa:** Comes after with a count of 11,030.
**South America:** Has the lowest count among the listed continents with a value of 10,718.
This data could represent a variety of metrics such as population, number of events, or other continent-specific statistics. 

## Which airport had the highest number of arrivals?
Arrival Airport Distribution: The table displays the top 10 arrival airports based on the count of arrivals. The airport codes are listed in descending order, with the highest arrival count being 873. Other airports include ‘JNB’ (37 arrivals), ‘PHM’ (36), ‘MPT’ (32), ‘PCO’ (27), ‘YTY’ (27), ‘ZRZ’ (26), ‘DZI’ (25), and ‘AHT’ (25).
Data Analysis: Descriptive statistics summarize and organize data characteristics.
In this case, we have a frequency distribution of airport arrivals. Descriptive statistics help us understand patterns and trends in the data.

# Analysis Steps

## Data Cleaning and Preprocessing:
Handle missing values, duplicates, and outliers.
Merge relevant tables (e.g., passenger data, flight data).

## Exploratory Data Visualization:
Use scatter plots, bar charts, and heatmaps.


