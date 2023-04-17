# SQL_With_COVID_Data

I explore a dataset that contains COVID data from all over the world from "Our World in Data (OWID)", a scientific online publication.
<br>[Source](https://ourworldindata.org/covid-deaths) 

Using Pandas and SQLite, I gain insight about COVID cases, vaccinations, and deaths.


To visualize my findings, I built a dashboard in Tableau. 
<br> [Link to Tableau dashboard](https://public.tableau.com/app/profile/alexander.bandurin/viz/Covid_Data_16815071012620/Vaccinesmillion)
<br>
<br>
<br>
Notes: 

The dashboard consists of several parts. These are:
- **Top 10 population**: Shows the top 10 total country populations by continent
- **Top 10 cases**: Shows the contries with the top 10 most total covid cases as reported by continent
- **Top 10 vaccinations**: Shows the contries with the top 10 most vaccinations as reported by continent
- **Top 10 deaths**: Shows the contries with the top 10 most deaths as reported by continent
- **New Cases/million**: Shows the smoothed 7-day average of new COVID cases per 1 million people
- **New Vaccines/million**: Shows the smoothed 7-day average of new COVID vaccines per 1 million people
- **New Deaths/million**: Shows the smoothed 7-day average of new COVID deaths per 1 million people

The dashboard is interactive such that the user can select which countries and or continents to view. There is also a date filter by month of date. 

Three countries have been highlighted from the rest. These are Chine (red), USA (blue), Canada (green), and Germany (yellow).
