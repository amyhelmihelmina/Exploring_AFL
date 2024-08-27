# Exploring AFL
## Project Details
Aim: An interactive dashboard that offers insights to game, player, and team metrics.

Dashboard dynamics:
  1. Segregation between overall, player, team, and venue sections.
  2. All charts can be used as filters.
  3. Additional show/hide filter panel that allows user to filter contents by season, rounds, team name, player name, and position.

Skills gained:
  1. Excel: Data cleaning, data formatting, data sorting and filtering
  2. Database management: Data modelling, database maintenance
  3. SQL:
  4. Tableau

The complete project guideline is attached in a PDF file.

## The data
### Source
Data was obtained from Kaggle. Whilst they were quite cleaned in terms of the columns required, the values themselves were not. I performed cleaning with Excel, then SQL and Tableau.

### Data Modelling
Before setting up a database, it's important to visualise the relationship between the datasets. Using draw.sql website, I modelled my AFL database, which was then exported to pgAdmin4.
<img width="532" alt="datamodel" src="https://github.com/user-attachments/assets/bdf0729d-3957-44e0-9561-dd38f2296d00">

### Data Exploration
Based on the project quideline requirement, I compiled several key questions to explore using SQL.

The complete SQL EDA is attached in a PDF file.

## Data Visualisation
### Dataset for Tableau
I pulled the required columns and tables from the dataset using postgreSQL. The tables are then modelled once again using Tableau's built-in modeller. Just to be safe.

### Mockup
A dashboard mock-up is built using Apple's built-in Freeform app. Having a mock-up is super useful for placing containers, which is crucial for perfect alignment of every element on a dashboard.
<img width="570" alt="Screenshot 2024-08-27 at 16 11 14" src="https://github.com/user-attachments/assets/24f7f353-50ab-4b17-b0f4-bbf02923c47f">

## Dashboard
![AFL Dash](https://github.com/user-attachments/assets/51fb45d5-c01e-462c-b694-24b615509c89)
Link to dashboard:
https://public.tableau.com/app/profile/amy.kamaruzaman/viz/AFL_DSAU_submission/AFLDash 
