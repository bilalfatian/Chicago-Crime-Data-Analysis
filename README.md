# Chicago Crime Data Analysis

This repo contains a data set from the Chicago Police department for crimes committed between 2001 to 2023 (with the exception of murders where data exists for each victim). This project is dedicated to doing some cool data analysis and visualization on this already curated dataset.

Data visualizations were created through the super awesome Python library **folium**, which I highly recommend to make map visualizations.

## Table of Contents
- [My Goals](#my-goals)
- [Acquired Skills](#acquired-skills)
- [Technologies](#technologies)
- [Description](#description)

## My Goals 🎯
- Analyze crime data from Chicago to identify prevalent crimes.
- Determine the year with the highest crime rate.
- Assess the success rate of arrests and its trend over the years.

## Acquired Skills ⚡
- Data analysis with Pandas and NumPy.
- Visualization using Matplotlib and Seaborn.
- Geographic visualization with Folium.

## Technologies 🖥️
- Pandas
- NumPy
- Folium
- Seaborn
- Matplotlib
- SciPy

## Description 📋
This project focuses on analyzing crime data from Chicago to gain insights into various aspects of crime occurrences in the city. The analysis involves answering the following questions:

1. **What crimes are most prevalent in Chicago?**
   ![Frequency of Crimes Per Crime Type](./Images/Frequency%20of%20Crimes%20Per%20Crime%20Type.png)

2. **What year had the most crime?**
   ![Frequency of Crimes Per Year in Chicago](./Images/Frequency%20of%20Crimes%20Per%20Year%20in%20Chicago.png)

3. **What percentage of arrests were successful?**
   ![Arrest Percentage](./Images/Arrest%20Percentage.png)

4. **What are the successful arrest percentages per year?**
   ![Percentages of Successful Arrests from 2001 to 2024](./Images/Percentages%20of%20Successful%20Arrests%20from%202001%20to%202024.png)



Descriptions of each map visualization is shown below:

- `map/January-2023-chicago-crimes.html` : This map is a detailed map visualization of all the crimes commited so far in the month of March (March 1, 2018 to March 19, 2018), with popup markers that display more information about each individual map, such as date, time, location, crime type, and crime description.
  
- `map/January-2023-chicago-crime-heatmap.html` : This map contains a heat map of all crimes commited so far in the month of March (March 1, 2018 to March 19, 2018).
  
- `map/Crime-per-district-choropleth.html` : This map contains a choropleth map of all the crimes from 2001 to 2023 based on Chicago Police District
 
here is the nbviewer for my jupyter notebook to see all visualizations : [Notebook Viewer](https://nbviewer.org/github/bilalfatian/Chicago-Crime-Data-Analysis/blob/main/Chicago-Crime-Data-Analysis.ipynb)








## Source of dataset:
[Chicago Crime Data from 2001 to present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

