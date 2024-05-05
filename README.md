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
- Create a Power BI dashboard to allow interactive exploration of the data.

## Acquired Skills ⚡
- Data analysis with Pandas and NumPy.
- Visualization using Matplotlib and Seaborn.
- Geographic visualization with Folium.
- Data preprocessing for Power BI.

## Technologies 🖥️
- Pandas
- NumPy
- Folium
- Seaborn
- Matplotlib
- SciPy
- Power BI

## Description 📋

This project focuses on analyzing crime data from Chicago to gain insights into various aspects of crime occurrences in the city, a Power BI dashboard has been created to allow interactive exploration of the data. The dashboard provides insights into various aspects of crime trends in Chicago.

<img width="606" alt="Screenshot 2024-05-05 150948" src="https://github.com/bilalfatian/Chicago-Crime-Data-Analysis/assets/92918987/3fc6222a-d624-43db-b0db-8cb7d5521248">

For data preprocessing, the `Data_Preprocessing.ipynb` Jupyter Notebook provides details on how the data was prepared for analysis and visualization. The dataset provided by the city of Chicago on crime (excluding murders) contains over 7 million rows and 22 columns. To facilitate early exploration of the data and focus on more recent, relevant trends, crimes from before 2014 were removed, along with unneeded columns and rows with nulls. The reduced dataset contained just under 3 million rows of crimes. Text columns were cleaned up by manually matching values of each column with a smaller subset of categories in Excel. Community Area IDs were mapped to their names and groups, and Community Area population sizes from the 2010 Census were added to allow for an approximated Crimes/Homicides per Capita calculation. Unfortunately, this data isn't provided year over year, the 2024 Census isn't available, which is why the 2010 population sizes were used.

For further exploration, you can view the structure of the Power BI dashboard [here](https://github.com/bilalfatian/Chicago-Crime-Data-Analysis/blob/main/Chicago_Crime_Dashboard.pdf).


Additionally, The analysis involves answering the following questions:

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
 
Here is the nbviewer for my jupyter notebook to see all visualizations : [Notebook Viewer](https://nbviewer.org/github/bilalfatian/Chicago-Crime-Data-Analysis/blob/main/Chicago-Crime-Data-Analysis.ipynb)

## Source of dataset:
[Chicago Crime Data from 2001 to present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)


## Contact Me 📨

- **LinkedIn:** [Bilal Fatian](https://www.linkedin.com/in/bilal-fatian-806813254/)
- **Gmail:** [fatian.bilal@gmail.com](mailto:fatian.bilal@gmail.com)

