# NYC Taxi Mobility and Safety Trends

This project analyzes New York City yellow taxi activity in 2024 to understand mobility demand, fare behavior, congestion patterns, and safety trends. The project combines taxi trip records, subway ridership, traffic volume, crash records, and driver availability data to build a visual story of how NYC moves.

The analysis uses Python for data preparation and Tableau for dashboard design.

## Project Objective

The goal of this project was to explore how taxi demand, pricing, traffic congestion, and safety patterns interact across New York City.

Key questions explored:

- When and where is taxi demand highest?
- Do fare patterns align with rider demand?
- How do holidays and seasonal patterns affect taxi usage?
- Which boroughs and road segments show the highest mobility pressure?
- Do higher taxi trip volumes relate to more taxi-involved crashes?

## Business Relevance

Taxi operators, fleet managers, city planners, and transportation stakeholders need better visibility into mobility patterns to improve driver deployment, pricing decisions, congestion planning, and safety monitoring.

This project turns large public transportation datasets into practical visual insights for urban mobility decision-making.

## Data Sources

The project used publicly available NYC transportation datasets:

- NYC Yellow Taxi Trip Data
- MTA Subway Ridership Data
- NYC Traffic Volume Counts
- TLC Vehicles Involved in Crashes
- Medallion Active Drivers
- Taxi Zone Lookup Data

Large raw datasets are not included in this repository because of file size. The repository includes processed summary datasets used for analysis and dashboarding.

## Tools Used

- Python
- Pandas
- NumPy
- PyArrow
- Jupyter Notebook
- Tableau
- Excel

## Repository Structure

```text
nyc-taxi-mobility-safety-trends/
├── dashboards/
├── data/
│   └── processed/
├── notebooks/
├── presentation/
├── reports/
├── tableau/
├── README.md
├── requirements.txt
└── .gitignore
