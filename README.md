# IPL-Auction-Dashboard-Using-Tableau

## Overview

This repository contains a Tableau dashboard that provides insights into the Indian Premier League (IPL) using data from ball_data.csv and match_data.csv. The dashboard includes visualizations for total runs and wickets season-wise, IPL winners, highest run scorer, and highest wicket taker. Top 10 batsmen and bowlers are displayed in tables, with dynamic images for an interactive experience.
<img width="802" alt="Dashboard 1" src="https://github.com/user-attachments/assets/f86a7114-d95b-4be1-9d2b-0537140d8c1e">
<img width="802" alt="Dashboard 2" src="https://github.com/user-attachments/assets/13d48244-8f18-4503-b444-4d885c8d8e76">

## Objectives

The dashboard aims to:

- Display the total runs scored in each IPL season
- Display the total wickets taken in each IPL season
- Show the winners of each IPL season
- Identify the highest run scorer in IPL history
- Identify the highest wicket taker in IPL history
- Rank the top 10 batsmen based on total runs scored
- Rank the top 10 bowlers based on total wickets taken
- Use dynamic images to enhance the user experience

## Dashboard Features

### Season-Wise Runs and Wickets

- Line charts displaying the total runs scored and wickets taken in each IPL season.

### IPL Winners

- A table listing the winners of each IPL season.

### Highest Run Scorer and Wicket Taker

- Cards displaying the highest run scorer and highest wicket taker in IPL history, with dynamic player images.

### Top 10 Batsmen and Bowlers

- Tables ranking the top 10 batsmen and bowlers based on total runs scored and wickets taken, respectively.
- Dynamic player images are used to make the tables more engaging.

## Data Sources

The dashboard uses the following data sources:

- ball_data.csv: Contains detailed information about each ball bowled in IPL matches.
- match_data.csv: Contains metadata about each IPL match, including the season, venue, and winner.

## Usage

To use the dashboard, open the Tableau workbook (.twbx) file in Tableau Desktop. The dashboard will load automatically, and you can interact with the visualizations and tables to explore the data.

## Limitations

The dashboard does not include any real-time data or predictions for future matches. It is based solely on historical data up to the point of data collection.

## Instructions

To run the queries and generate the dashboard, you can follow these steps:

1. Install PostgreSQL and Tableau Desktop.
2. Import the `match_data.csv` and `ball_data.csv` files into a PostgreSQL database.
3. Create the queries as shown above and execute them in the database.
4. Connect Tableau Desktop to the database and create the dashboard based on the query results.

The dashboard can be used to analyze the performance of teams and players in the IPL over the years.

## Conclusion

The Tableau dashboard created using the IPL ball data and match data CSV files provides a comprehensive overview of the tournament's history and performance. It allows users to easily explore and analyze data to gain insights into various aspects of the IPL.
