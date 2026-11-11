# Insights from City Supply and Demand Data

## About the Assignment
This is a Data Science take-home assignment that has been used in the recruitment process for Data Science positions at Uber.

The assignment focuses on analyzing city supply and demand data over a two-week period to understand ride requests, completed trips, driver availability, and demand patterns.

## Dataset Description
The dataset (`dataset_1.csv`) contains hourly information about Uber ride activity.

**Columns:**
- `Date` – Date of the recorded data.
- `Time (Local)` – Local hour of the day.
- `Eyeballs` – Number of people who opened the Uber app.
- `Zeroes` – Number of people who could not find an available car.
- `Completed Trips` – Number of successfully completed trips.
- `Requests` – Total number of ride requests.
- `Unique Drivers` – Number of available drivers.

**Dataset size:** 336 rows and 7 columns.

## Questions & Answers

The assignment covers the following 11 questions:

| No. | Question | Answer |
|---|---|---|
| 1 | Date with the most completed trips | 22 September 2012 (248 trips) |
| 2 | Highest completed trips in 24 hours | 278 trips |
| 3 | Hour with the most requests | 11 PM (184 requests) |
| 4 | Weekend percentage of total zeroes | 44.86% |
| 5 | Weighted average ratio of completed trips per driver | 82.83% |
| 6 | Busiest rolling 8-hour period | 207 requests |
| 7 | Does driver supply always increase with demand? | False |
| 8 | Highest Zeroes-to-Eyeballs ratio in 72 hours | 29.30% |
| 9 | Best hour to add 5 drivers daily | 11 PM |
| 10 | Is there exactly two weeks of data? | True |
| 11 | Suggested end of the day | 4 AM – 5 AM |

## Tools & Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

## Analysis Techniques
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Grouping and Aggregation
- Time-Based Analysis
- Rolling Window Calculations
- Weighted Average
- Data Visualization

## Notebook
The complete assignment was performed using **Google Colab**.

The notebook includes Python code, data cleaning, calculations, and visualizations used to answer all 11 questions.

## Conclusion
This assignment provided practical experience in analyzing real-world ride-sharing data and understanding the relationship between rider demand and driver supply using Python.
