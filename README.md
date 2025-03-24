# Project Movie Dashboard
## Table of content
- [Project](#Project-Overview)
- [Data Source](#Data-Source)
- [Tools](#Tools)
- [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
- [Questions for Data Analysis](#Questions-forData-Analysis)
- [Dashboard](#Dashboard)
- [Results and Findings](#Results-and-Findings)
- [Challenges](#Challenges)
### Project Overview
 This data analysis project aims to provide insights into the performance and trends of movies from 2012 to 2016 to the team of creative directors of Apple TV. By analyzing  various aspects of the movie data, we seek to identify patterns, make data-driven recommendations, and gain a deeper understanding of the industry's dynamics.
 ### Data Source
 Movie Data : The primary dataset used for this analysis is the "Movie Data Homework.xlsx" file, containing detailed information about each movie's performance (box office and budjet), actors, directors etc.[Find original Data Soures Hier](https://github.com/user-attachments/files/19413515/Dashboard.xlsx)

 ### Tools
- Power Query - I used Power Query for Data Cleaning
- Excel-I used for Data Analysis
  - Pivot Tables - for creating dashboard and Visualizations
### Data Cleaning and Preparation
- Data loading and inspection.
- Handling errors, missing values.
- Data cleaning and formatting. The excel file after the data cleaning & preparation process can be downloaded here [Movies Readi for Dashboard](https://github.com/user-attachments/files/19412126/Dashboard.xlsx)
###  Questions for Data Analysis
1. Which top 10 genres were the most successful (Box)  these years?
2. Which to 5 actors were the most successful?...
3. Top 5 movies by Box and Budget?
4. Seasonaliti
### Dashboard
<img width="409" alt="Carture 2" src="https://github.com/user-attachments/assets/38e71614-38f2-4a71-9385-d23ed5325d42" />

### Results and Findings
As an example: Best profitable movie was: with Budget of... Box Office Revenue was 102,000,000 USD. The genre of this movie was horror

<img width="152" alt="Carture 1" src="https://github.com/user-attachments/assets/04900384-222c-4e62-a1bf-260581d77590" />

### Challenges
= Table.AddColumn(#"Renamed Columns1", "TodayOrNotToday", each if [appointment_date] =DateParameter then "Today" else "NotToday")
