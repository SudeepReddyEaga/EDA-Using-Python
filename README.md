📊 Crime Analytics Project - 2024
This project involves an in-depth exploratory data analysis (EDA) on crime incidents that occurred in 2024. The dataset contains detailed records of various crimes reported, including spatial, temporal, and categorical attributes. The analysis is aimed at deriving actionable insights for law enforcement planning, crime prevention, and public awareness.

📁 Dataset Overview
The dataset is sourced from an Excel file containing the following key fields:

REPORT_DAT: Timestamp of when the incident was reported.

SHIFT: Time of day the incident occurred (e.g., DAY, EVENING, MIDNIGHT).

METHOD: Method or weapon used in the crime.

OFFENSE: Type/category of crime (e.g., THEFT/OTHER, ASSAULT W/DANGEROUS WEAPON).

BLOCK: Street-level location description.

LATITUDE, LONGITUDE: Geolocation for mapping incidents.

START_DATE, END_DATE: Actual time window when the incident occurred.

CENSUS_TRACT, VOTING_PRECINCT, BLOCK_GROUP: Demographic/geographic identifiers.

BID: Business Improvement District (if applicable).

🧪 Project Goals
Analyze temporal patterns (e.g., crime frequency by month, shift, day).

Conduct spatial analysis to identify high-crime areas using maps and coordinates.

Explore crime category distributions to find most common offenses.

Assess potential correlations between time of day, location, and offense type.

Generate visualizations using matplotlib, seaborn, and plotly.

📦 Libraries Used
pandas – for data manipulation

numpy – for numerical operations

matplotlib & seaborn – for static data visualizations

plotly – for interactive maps (optional)

datetime – for time-based analysis

