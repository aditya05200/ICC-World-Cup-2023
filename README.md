# ICC World Cup 2023 Data Analysis using Azure Services

## Project Overview
This project is an analysis of the ICC World Cup 2023 data using Azure services. The project aims to answer various questions related to the cricket tournament, such as the performance of different teams, players, venues, etc. The project uses Azure Data Factory, Azure Databricks, Azure Synapse Analytics, and Power BI to analyze the data.

## Azure Services
Azure is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers. The project uses the following Azure services:

- **Azure Data Factory**: A data integration service that allows you to create data pipelines to move and transform data from various sources to destinations.
- **Azure Databricks**: A data analytics platform based on Apache Spark that provides a collaborative workspace for data engineers, data scientists, and business analysts.
- **Azure Synapse Analytics**: A data warehouse service that enables you to query and analyze large volumes of data using SQL and Spark.
- **Power BI**: A business intelligence service that allows you to create interactive dashboards and reports to visualize and share insights from your data.

## Data Flow
The data flow of the project is as follows:

- **Data Source**: The data is collected from various sources and stored in a data lake.
- **Data Factory**: The data is then processed and transformed using Azure Data Factory.
- **Data Lake Gen 2**: The transformed data is then stored in Azure Data Lake Gen 2.
- **Databricks**: The data is then processed and analyzed using Azure Databricks.
- **Azure Synapse Analytics**: The data is then further analyzed using Azure Synapse Analytics.
- **Power BI**: Finally, the data is visualized and presented in a dashboard using Power BI.
- !Data Flow Diagram

<img width="700" alt="icc" src="https://github.com/aditya05200/ICC-World-Cup-2023/assets/102588012/3c5e2d6f-4e42-454e-86b0-55df5df5b343">

## Data Files
The data files for the project are stored in the Data Lake Gen 2, and they are as follows:

- **Batting_Stats.csv**: This file contains the batting statistics of each player in each match, such as the number of runs, balls, fours, sixes, strike rate, etc.
- **Bowling_Stats.csv**: This file contains the bowling statistics of each player in each match, such as the number of overs, runs, wickets, economy, etc.
- **Best_Team.csv**: This file contains the ranking of the best teams in the ICC World Cup 2023, based on their points, net run rate, wins, losses, etc.
- **Point_Table.csv**: This file contains the point table of the ICC World Cup 2023, showing the points, wins, losses, net run rate, etc. of each team in each group.
- **Max_Catches.csv**: This file contains the list of the players who took the maximum number of catches in the ICC World Cup 2023, along with their country and number of catches.
- **Partnership.csv**: This file contains the list of the best partnerships in the ICC World Cup 2023, based on the runs, balls, and partnership rate.

## Research Questions
The project aims to answer the following research questions using the data:

- **Q1**: Which team had the best performance in the ICC World Cup 2023?
- **Q2**: Which player had the best performance in the ICC World Cup 2023?
- **Q3**: Which venue had the most favorable conditions for batting and bowling in the ICC World Cup 2023?
- **Q4**: How did the toss affect the outcome of the matches in the ICC World Cup 2023?
- **Q5**: What were the key factors that influenced the results of the matches in the ICC World Cup 2023?

## Analysis Results
The analysis results of the project are presented in a Power BI dashboard,
<img width="830" alt="Dashboard" src="https://github.com/aditya05200/ICC-World-Cup-2023/assets/102588012/d214ce5b-7344-4669-8bbe-afc19f4ef74b">


Power BI Dashboard

The dashboard contains the following sections:

- **Overview**: This section provides a summary of the ICC World Cup 2023, such as the number of matches, teams, players, venues, etc.
- **Team Performance**: This section provides a comparison of the performance of different teams in the ICC World Cup 2023, such as the number of wins, losses, points, net run rate, etc.
- **Player Performance**: This section provides a comparison of the performance of different players in the ICC World Cup 2023, such as the number of runs, wickets, catches, etc.
- **Venue Analysis**: This section provides an analysis of the characteristics of different venues in the ICC World Cup 2023, such as the average score, run rate, wicket rate, etc.
- **Toss Analysis**: This section provides an analysis of the impact of the toss on the outcome of the matches in the ICC World Cup 2023, such as the win percentage, decision percentage, etc.
- **Match Factors**: This section provides an analysis of the key factors that influenced the results of the matches in the ICC World Cup 2023, such as the batting order, partnership, powerplay, etc.

## Conclusion
The project demonstrates how Azure services can be used to perform a comprehensive data analysis of the ICC World Cup 2023. The project provides valuable insights into the performance of different teams, players, venues, etc. in the cricket tournament. The project also identifies the key factors that affected the results of the matches in the ICC World Cup 2023. The project can be further extended by adding more datasets, research questions, and analysis techniques. 
