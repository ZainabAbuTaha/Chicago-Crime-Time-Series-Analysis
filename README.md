# Chicago Crime Time Series Analysis

## Project Overview
This project analyzes crime trends in the city of Chicago using historical crime data from 2001 to 2022.  
The goal of this analysis is to explore patterns and trends in crime over time and answer stakeholder-driven questions using data visualization and time series techniques.

This project is part of **Core Project 3 – Part 1** and serves as the foundation for future time series modeling and forecasting.

---

## Data Source
- **Chicago Data Portal**: Crimes 2001 to Present  
- The dataset contains reported crimes in Chicago, including:
  - Crime type
  - Date and time of occurrence
  - Police district
  - Arrest information

To make the data repository-friendly, the original large dataset was provided as multiple CSV files separated by year.

---

## Data Preparation
- Combined multiple yearly CSV files into a single dataset
- Converted the `Date` column to datetime format
- Set the date as the index for time series analysis
- Created two versions of the data:
  - Individual crime records (one row per crime)
  - Resampled daily crime counts for trend analysis

---

## Analysis Topics

### Topic 1: Comparing Police Districts
- Identified the police district with the **highest** and **lowest** number of reported crimes in 2022
- Visualized total crimes by district using bar charts

### Topic 2: Crimes Across the Years
- Analyzed yearly trends in total crime from 2001 to 2022
- Identified a long-term decrease in total crime
- Examined **Motor Vehicle Theft** as an individual crime type that shows a contrasting trend in recent years

### Topic 3: Comparing AM vs. PM Rush Hour
- Compared crime frequency during:
  - AM Rush Hour (7 AM – 10 AM)
  - PM Rush Hour (4 PM – 7 PM)
- Identified the top 5 most common crimes during each time period
- Determined that motor vehicle thefts are more common during PM rush hour

---

## Tools & Libraries Used
- Python
- pandas
- NumPy
- matplotlib
- seaborn

---

## Author
**Zainab Abu Taha**

---

## Notes
This project focuses on exploratory data analysis and visualization.  
Future phases will expand on this work by incorporating seasonality analysis and predictive time series models.
