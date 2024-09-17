# Zane Sorenson's Projects

Welcome to my project repository! This collection showcases my skills in SQL and Python, as well as my use of libraries such as Pandas, NumPy, Matplotlib, and Seaborn to perform data analysis, wrangling, and visualization. Each project demonstrates different techniques and approaches to solving real-world data problems. Below, you’ll find an overview of each project, including its purpose, dataset information, and instructions for exploring the associated files.

---

## SQL - DVD Rental Database Exploration

### Project Overview
This project focuses on analyzing a movie rental company's database using SQL. The goal was to run queries that uncover insights about customer behaviors, rental patterns, and store performance. Additionally, I created visualizations to represent the data findings in a clear and meaningful way.

### Dataset Information
The dataset used is the Sakila DVD Rental database, which contains information on customer demographics, rental transactions, inventory, and store operations. By querying this database, I was able to identify customer patterns across different groups, compare rental payments, and assess how individual stores performed relative to each other. A database schema (ERD) is provided for context.

### Project Files
- **Database Files**: 
  - `dvd_rental_database.tar` - This contains the Sakila database as `.dat` files, which can be imported into a DBMS for querying.
  
- **Entity-Relationship Diagram (ERD)**: 
  - `dvd_rental_sample_database_diagram.png` - A visual representation of the database structure.
  
- **SQL Queries**: 
  - `project_queries.sql` - Contains the SQL queries used to analyze the dataset.
  - `project_queries.txt` - An alternative format of the same SQL queries for easy viewing.
  
- **Analysis Report**: 
  - `project_slides.pdf` - A PDF containing the results of the analysis, including graphs and insights drawn from the queries.


## Python - Bikeshare Data Exploration

### Project Overview
This project involves analyzing bike share data from three major U.S. cities: Chicago, New York City, and Washington, DC. Using Python, I wrote code to import the data, compute descriptive statistics, and create an interactive script that allows users to explore the data by filtering based on various inputs like city, month, and day. The script outputs key insights on travel times, popular stations, trip durations, and user demographics, offering a flexible and engaging way to examine the dataset.

### Dataset Information
The dataset, provided by Motivate (a bike share system operator), contains records of bike share usage in Chicago, New York City, and Washington. The data includes details about trip durations, start and end stations, user types, and (for certain cities) demographic information like gender and birth year. The analysis focuses on uncovering patterns in travel behavior and comparing usage across these cities.

### Project Files
- **Data Files**: 
  - `chicago.csv`
  - `new_york_city.csv`
  - `washington.csv`
  
  Each file contains bike share trip data for the respective city.
  
- **Python Script**: 
  - `bikeshare_project.py` - This script can be run locally through the command line to launch the interactive analysis. Make sure the `.csv` files are in the same directory as the script. The program will prompt users to filter the dataset by city, month, or day, and then display the relevant statistics based on the selections.S



## Pandas & NumPy - Gun Data Exploration

### Project Overview
In this project, I conducted an open-ended data analysis using the FBI’s National Instant Criminal Background Check System (NICS) data and state-level U.S. census data. The goal was to explore patterns and correlations in firearm background checks across different states and time periods. Using Pandas and NumPy, I analyzed the data to answer questions about potential factors influencing gun background checks, including political and demographic variables. The findings are tentative and exploratory, as the project focuses on descriptive analysis rather than inferential statistics or machine learning.

### Dataset Information
The dataset includes:
- **NICS Data**: Contains monthly firearm background check numbers by state and firearm type. This data comes from the FBI's NICS, which is used by gun shops to verify customer eligibility for purchasing firearms or explosives.
- **U.S. Census Data**: Provides state-level demographic information from census.gov. While most variables have a single data point per state (from 2016), some variables span multiple years.

This project explores general patterns in the data, such as potential relationships between state demographics and the number of background checks, as well as whether the political party of the sitting President has any effect on the volume of checks. 

### Project Files
- **Data Files**:
  - `US_Census_Data.csv` - Contains U.S. Census data on state demographics.
  - `gun_data.csv` - Contains firearm background check data from the NICS.

- **Jupyter Notebook**:
  - `Investigate_a_Dataset.ipynb` - The Jupyter Notebook containing the full analysis. It can be viewed directly on GitHub or downloaded and run locally in a Jupyter environment.
  
- **HTML Version**:
  - `Investigate_a_Dataset.html` - An HTML version of the Jupyter Notebook, viewable in any browser if downloaded.

Both the notebook and the HTML file contain the data analysis, findings, and visualizations related to the questions explored.



## Python - NYC Basketball Courts Data Wrangling

### Project Overview
In this project, I performed data wrangling using Python to clean and analyze data on NYC basketball courts and NYPD arrest records. The goal was to assess the relationship between the availability of sports facilities and crime rates in different neighborhoods. Using Python's data manipulation libraries, I gathered, assessed, and cleaned datasets from multiple sources, then used the cleaned data to create visualizations and explore this potential connection.

### Dataset Information
The project uses two datasets:
- **NYC Basketball Courts**: Data pulled from the NYC Department of Parks & Recreation API. It contains information on the number of basketball courts at various locations across New York City.
- **NYPD Arrest Data**: Manually downloaded from the NYC Open Data portal. This dataset provides details on arrests made in NYC, including crime type, location, time of arrest, and suspect demographics.

The analysis focused on whether the availability of basketball courts in different boroughs correlates with lower arrest rates.

### Project Files
- **Raw Data**:
  - `NYC_Basketball_Courts.csv` - Contains data on basketball courts from the NYC Parks & Recreation Department.
  - `NYPD_Arrest_Data.csv` - Contains NYPD arrest data.

- **Cleaned Data**:
  - `clean_basketball_courts_data.csv` - Cleaned version of the basketball courts data.
  - `clean_nypd_arrest_data.csv` - Cleaned version of the NYPD arrest data.
  - `clean_data_by_borough.csv` - Cleaned data aggregated by borough for analysis.

- **Jupyter Notebook**:
  - `data_wrangling_project_starter.ipynb` - The Jupyter Notebook containing the full data wrangling process, including data gathering, cleaning, and analysis. This file can be viewed on GitHub or downloaded and run locally using Jupyter Notebook. Ensure the raw data files are in the same directory if running it locally.

- **HTML Version**:
  - `data_wrangling_project_starter.html` - An HTML version of the Jupyter Notebook, viewable in any browser if downloaded.

The Jupyter Notebook and HTML file document the entire wrangling process, along with visualizations and insights drawn from the cleaned datasets.



## Matplotlib & Seaborn - Airlines Data Visualization

### Project Overview
This project is split into two parts, demonstrating how data visualization is crucial in understanding and communicating data insights. The goal was to explore and visualize U.S. airline delay data using Python's Matplotlib and Seaborn libraries.

- **Part I: Exploratory Data Visualization**: Focused on systematically exploring the dataset, starting with simple visualizations of single variables and progressing to more complex visualizations that illustrate relationships between multiple variables.
  
- **Part II: Explanatory Data Visualization**: Built on the insights from Part I, transforming the exploratory visualizations into polished, explanatory visuals designed to communicate key findings effectively.

### Dataset Information
The dataset, **"Reporting Carrier On-Time Performance Data"**, covers flights within the United States, including carrier names, arrival and departure delays, and the reasons for delays from 1987 to 2022. It was sourced from the Office of Airline Information, Bureau of Transportation Statistics (BTS), and includes data from U.S. air carriers that account for at least half of one percent of domestic scheduled passenger revenues.

The investigation focused on flight delays, examining airline performance and delay types.

### Project Files
- **Raw Data**:
  - `airline_2m.csv` - The raw dataset containing flight delay information.

- **Cleaned Data**:
  - `airline_df.csv` - Cleaned dataset focusing on general flight information.
  - `delay_df.csv` - Dataset specifically focusing on delay types.
  - `top_states_df.csv` - Dataset covering state-level analysis.
  - `trim_df.csv` - A further refined version of the dataset used for visualizations.

- **Jupyter Notebooks**:
  - `Part_I_exploration_template.ipynb` - Contains the exploratory data visualizations. Can be viewed on GitHub or run locally if the raw data is in the same directory.
  - `Part_II_explanatory_template.ipynb` - Contains the explanatory visualizations, refining the insights from Part I.

- **HTML Versions**:
  - `Part_I_exploration_template.html` - HTML version of the exploratory notebook, viewable in any browser.
  - `Part_II_explanatory_template.html` - HTML version of the explanatory notebook, also viewable in a browser.

Both notebooks and HTML files contain visualizations that explore the relationships between airline carriers and delay times, providing insights for potential travelers and stakeholders.