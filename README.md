# Olympics Dataset Analysis Using PowerBI

<div align="center">
  <img src="https://github.com/user-attachments/assets/6c0e1cc1-9f41-41ba-9da1-e6d6647307f7" alt="Olympics Dataset Analysis" />
</div>

## Introduction

This project delivers an in-depth analysis of the Olympics dataset using Microsoft Power BI. The objective was to meticulously clean, transform, and visualize the data to uncover valuable insights into Olympic performances. By examining various dimensions such as gender, countries, sports, and age groups, this analysis provides a nuanced understanding of Olympic trends and highlights patterns that are essential for sports analysts, historians, and enthusiasts.

## Project Overview

This project involves a comprehensive analysis of the Olympics dataset using Microsoft Power BI. The goal was to clean, transform, and visualize the data to derive meaningful insights about Olympic performances across various dimensions such as gender, countries, sports, and age groups.

**Project Author:** [Jibrin Tijjani Isiaka](https://github.com/Adnanisme)

## Skills Utilized

- Data Cleaning and Transformation using Power Query
- Advanced Data Visualization techniques in Power BI
- Data Analysis and Insight Generation
- Dashboard Design and User Experience Optimization

## Dataset

The dataset used for this analysis comes from kaggle.com, it can also be found here : 

- [Olympics Dataset](https://drive.google.com/drive/folders/1Sr-sl_HdM-_crELlkHuaWAMuFaTnsva_)

## Data Preparation and Cleaning

### Data Import and Initial Transformation

1. Imported two tables directly into Power BI
2. Used Power Query Editor for data transformation

### Data Cleaning Steps

1. Set the first row as header

![367116601-2182dd14-5e13-4b6d-8bb3-26ce425e9228](https://github.com/user-attachments/assets/7054edb1-477c-4884-9a4c-7f19fdd77430)

3. Removed unnecessary columns (e.g., Notes, Height, Weight, Team, Games, Cities, Event)
4. Merged country definitions table with athletes events table using the NOC (Name of Country) column

![367116598-92785678-99a5-4608-a07a-9bd4881d22a4](https://github.com/user-attachments/assets/8611f94f-d446-4263-81d6-3e653158c9f7)

5. Expanded the merged column and removed redundant NOC information
6. Renamed columns for clarity (e.g., 'Sex' to 'Gender')
7. Standardized gender values (M to Male, F to Female)
8. Removed null values to ensure data quality
9. Named the final cleaned table as "Olympics_final"

## Visualizations and Insights

### 1. Distribution of Medals by Gender

![367122861-cab260fe-f357-4c54-b6a8-dde51ee5240f](https://github.com/user-attachments/assets/94e91be7-ba8f-45e1-81f5-e9c96780440c)

- Used a pie chart to visualize medal distribution between male and female athletes
- Customized colors: Bronze for male, Gold for female
- Positioned legend at the top center for better readability

### 2. Top 10 Countries by Medal Count

![367122867-ed62d386-a14e-4f39-8e79-4b9479a68955](https://github.com/user-attachments/assets/5d4cb354-7ed4-4470-b93a-24b7b91f708e)

- Utilized a matrix visualization
- Displayed countries in rows and medal types in columns
- Applied conditional formatting with data bars for easy comparison
- Sorted data by total medal count

### 3. Distribution of Medals Among Top 15 Athletes

![367122871-7823347a-234f-4775-950c-e1c44b8bf867](https://github.com/user-attachments/assets/ba420200-ae96-46d4-8902-e053da55b175)

- Created a column chart showing medal counts for the top 15 athletes
- Color-coded medals (Bronze, Silver, Gold)
- Added data labels for precise values

### 4. Distribution of Medals by Sports

![367122874-6bcc45f2-03a7-40ed-8c64-ed3de7924ce1](https://github.com/user-attachments/assets/b42a01f4-4994-4a80-bcdd-ec4353eb9389)

- Implemented a treemap visualization
- Used gradient coloring from dark blue to light blue to represent medal counts

### 5. Count of Medals by Age

![367122875-e28af9f7-3d9c-4acb-8b30-119ba8d60717](https://github.com/user-attachments/assets/39df1026-05ab-4ec7-ba69-57fe0aa1e49a)

- Created a ribbon chart to visualize medal distribution across different age groups
- Focused on ages 15 to 40 for most relevant data
- Revealed peak performance age ranges in Olympic sports

### 6. Participant Count by Year and Gender

![367122881-379728dd-2c5e-4073-ac25-5b48007e9fe6](https://github.com/user-attachments/assets/8dd72897-0594-43a3-9971-63c7c2b2a5f9)

- Utilized a line chart to show the trend of participation over the years
- Separated lines for male and female participants
- Highlighted the historical gender gap in Olympic participation

## Key Metrics (Card Visualizations)

- Distinct Sports: 66
- Participating Countries: 207
- Medals Awarded: 39.77k

![367119617-00704bfa-8c84-4567-9fe8-2734db2afdbe](https://github.com/user-attachments/assets/3ed4885b-4e9e-49d6-8a39-189f2325cfe3)

## Interactive Features

- Added filters for sports and countries to allow users to drill down into specific data points
- Ensured all visualizations are interconnected for a cohesive user experience

## Project Outcome

This Power BI project presents a thorough visual analysis of Olympic data, offering valuable insights into gender participation, country performance, age demographics, and sports distribution. The interactive dashboard is designed to facilitate a deep dive into Olympic trends and patterns, serving as an essential tool for sports analysts, historians, and Olympic enthusiasts alike. With its comprehensive visualizations and user-friendly interface, this project enhances the ability to explore and interpret Olympic data effectively.

## Future Enhancements

- Incorporate more recent Olympic data as it becomes available
- Add time-based analysis to track changes in trends over different Olympic eras
- Implement predictive analytics for future Olympic performance forecasting
