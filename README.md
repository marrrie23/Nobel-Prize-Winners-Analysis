# Collecting Data (Assignment 3a)

# Dataset Overview

## Description

The Download Nobel Prize Winners data contains information about 957 Nobel Prize winners from 1901 to 2017. This information includes the Nobel laureate’s name, birth and death date (if applicable), birth and death location (plus latitude and longitude coordinates for the locations), the year they won the Nobel Prize, the category of the Nobel Prize, and the “motivation” for the Nobel Prize.

Nobel laureates include Marie Curie, Johannes Stark, Woodrow Wilson, Jane Addams, Rabindranath Tagore, John Steinbeck, Gabriel Garcia Marquez, Karl Ziegler, Toni Morrison, and many more.

The dataset, contains detailed information on 957 Nobel Prize winners from 1901 to 2017. The comprehensive dataset encompasses various aspects of each laureate's background and achievements. Key data points include:

- Name: The full name of the Nobel laureate.
- Birth and Death Dates: Dates of birth and death of the laureates, when applicable.
- Birth and Death Locations: Geographic locations where the laureates were born and died, including latitude and longitude coordinates.
- Nobel Prize Details: Year of winning the Nobel Prize, the category of the prize (such as Peace, Literature, Medicine, etc.), and the motivation behind awarding the prize to the laureate.

For more details, see the table of variables below.

# Question 1: Nobel Peace Prizes Trends

Objective: To analyze the trends in the Nobel Peace Prize awards over the years. This includes identifying patterns in awarding the Peace Prize, understanding fluctuations and gaps in awards, and correlating these trends with historical events.

Methodology: Grouping the data by year and category, particularly focusing on the Peace category, and visualizing the data to observe trends in the awarding of the Nobel Peace Prize.

# Question 2: Geographic Distribution of Nobel (Peace) Prize Laureates
Objective: To investigate the geographical distribution of Nobel laureates, with a special emphasis on the Peace Prize category. The aim is to understand which countries or regions have produced the most laureates.

Methodology: Filtering the dataset by the Prize category, grouping data by year and number of prizes, and visualizing the results using the barplots.


## Table of Variables

| Variable Name           | Description                                   |
|-------------------------|-----------------------------------------------|
| name                    | Name of the individual                        |
| born                    | Date of birth                                 |
| bornCountry_original    | Original country of birth                     |
| bornCountry_now         | Current name of the country of origin         |
| bornCity_original       | Original city of birth                        |
| bornCity_now            | Current name of the city                      |
| bornLocation            | Specific birth location                       |
| bornLong                | Longitude coordinate of birthplace            |
| bornLat                 | Latitude coordinate of birthplace             |
| diedLong                | Longitude coordinate of place of death        |
| diedLat                 | Latitude coordinate of place of death         |
| diedCoordinates         | Combined longitude and latitude of deathplace |
| gender                  | Gender of the individual                      |
| year                    | Year of the relevant event or recognition     |
| category                | Category of achievement or recognition        |
| motivation              | Reason for recognition or award               |
| institutionName         | Name of affiliated institution                |
| institutionCity         | City of the affiliated institution            |
| institutionCountry      | Country of the affiliated institution         |



- **Source**:  The European Data Portal and the official Nobel Prize API
