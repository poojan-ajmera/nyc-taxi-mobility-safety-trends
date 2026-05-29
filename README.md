
# NYC Taxi Mobility and Safety Trends

This project analyzes New York City yellow taxi activity in 2024 to understand how urban mobility patterns shift across time, boroughs, pricing behavior, congestion, and safety. The analysis combines taxi trip records, subway ridership, traffic volume, crash records, and driver availability data to build a visual story around how NYC moves.

The project was completed as a data visualization and business dashboarding project using Python for data preparation and Tableau for dashboard design.

## Project Objective

The main goal was to explore how taxi demand, fare behavior, traffic congestion, and safety patterns interact across New York City.

Key questions explored:

- When and where is taxi demand highest?
- Do fare patterns align with rider demand?
- How do seasonal and holiday patterns affect taxi usage?
- Which boroughs and road segments show the highest mobility pressure?
- Do higher taxi trip volumes relate to more crash incidents?

## Business Relevance

Taxi operators, fleet managers, city planners, and transportation stakeholders need clear visibility into mobility patterns to improve driver deployment, pricing decisions, congestion planning, and public safety monitoring.

This project uses visual analytics to turn large public transportation datasets into practical insights for urban mobility decision-making.

## Data Sources

The project used publicly available NYC transportation datasets, including:

- NYC Yellow Taxi Trip Data
- MTA Subway Ridership Data
- NYC Traffic Volume Counts
- TLC Vehicles Involved in Crashes
- Medallion Active Drivers
- Taxi Zone Lookup Data

Large raw datasets are not included in this repository because of file size. The repository includes processed summary datasets used for dashboarding and analysis.

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
Dashboard 1: Citywide Mobility Overview

This dashboard gives a broad view of NYC taxi movement in 2024. It highlights daily trip patterns, holiday dips, monthly taxi versus subway trends, pickup and drop-off behavior by borough, and highly congested road segments.

Key insight: Taxi demand follows a strong weekday rhythm, with visible drops during major holidays such as July 4, Thanksgiving, and Christmas. Manhattan dominates both pickups and drop-offs, while Queens shows higher pickup activity, likely connected to airport travel.

Dashboard 2: Hourly Demand vs Fare

This dashboard compares hourly taxi trip volume with average fare patterns.

Key insight: Taxi demand peaks around 6 PM, but average fare does not peak at the same time. The highest average fare appears around 5 AM, when demand is lower but driver availability and trip type may influence pricing.

Dashboard 3: December 13 Peak-Day Taxi Behavior

This dashboard zooms into December 13, 2024, which was identified as a peak day in the taxi data. It analyzes trip volume, fare trends, and trip distance throughout the day.

Key insight: Evening demand rises sharply, while fare and trip distance patterns show unique spikes during early morning and evening periods.

Dashboard 4: Mobility vs Safety

This dashboard compares monthly taxi trip volume with taxi-involved crash counts.

Key insight: Higher mobility months such as May and November also show higher crash counts, while August shows a dip in both trip volume and crashes. This suggests a possible relationship between mobility intensity and safety risk.

Key Findings
Taxi demand follows strong daily, weekly, and seasonal patterns.
Holiday periods create sharp drops in trip volume.
Manhattan remains the central taxi activity zone in NYC.
Queens shows a pickup-heavy pattern, likely connected to airport-origin trips.
Fare patterns do not always match demand peaks.
Early morning fares are unusually high despite lower trip volume.
Crash counts appear higher during some high-mobility months.
Congested road segments such as Cross Bronx Expressway and Long Island Expressway remain major pressure points.
Skills Demonstrated
Large dataset handling
Parquet to CSV conversion
Data cleaning and transformation
Time-series aggregation
Dashboard design
Data storytelling
Business problem framing
Transportation and urban mobility analysis
Tableau visualization
How to Use This Repository
Review the dashboard screenshots in the dashboards/ folder.
Open the processed summary datasets in data/processed/.
Review the notebooks in order:
00_parquet_to_csv_conversion.ipynb
01_combining_datasets.ipynb
02_dec13_peak_day_analysis.ipynb
03_dec13_half_hour_analysis.ipynb
Open the final report in the reports/ folder for the full project explanation.
Open the presentation in the presentation/ folder for the storytelling version of the project.
Future Improvements

Future versions of this project could include:

Predictive modeling for crash risk
Zone-level fare optimization
Integration of Uber and Lyft ride-share data
Interactive public Tableau dashboard publishing
Real-time taxi demand forecasting
