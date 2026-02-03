# Project: Predictive Analysis of Chicago Taxi Ridership & Weather Impact

## Business Context
Developed as a specialized project during the TripleTen Data Analytics Bootcamp (Data Collection & Storage Sprint), this study investigates the correlation between weather conditions and urban mobility. The core objective is to validate how adverse weather impacts travel logistics, specifically focusing on trips to O'Hare International Airport.

## 🎯 Research Objectives
The project evaluates a specific business hypothesis: "Does rainy weather on Saturdays significantly increase the duration of taxi trips from the Loop to O'Hare International Airport?"

To answer this, the analysis focuses on:

Market Share Analysis: Identifying dominant taxi companies in the Chicago area.

Geospatial Trends: Mapping the top 10 drop-off neighborhoods by trip volume.

Weather Sensitivity: Measuring the statistical variance in trip duration during rainy vs. clear weather conditions.

## 📊 Datasets Overview

The analysis integrates three primary datasets from November 2017:

Company Performance: project_sql_result_01.csv — Taxi companies and total trips (Nov 15-16).

Location Analytics: project_sql_result_04.csv — Average trips per neighborhood (Drop-off points).

Trip & Weather Logs: project_sql_result_07.csv — Time-stamped data including start times, weather conditions, and duration in seconds for airport routes.

## 🛠️ Analytical Roadmap

#### Phase 1: Exploratory Data Analysis (EDA)

Data Sanitization: Rigorous cleaning and type conversion to ensure analytical integrity.

Competitor Benchmarking: Visualizing trip distribution across taxi companies.

Neighborhood Profiling: Identifying the top 10 high-traffic drop-off zones and extracting insights from urban movement patterns.


#### Phase 2: Statistical Hypothesis TestingFramework: 

Formulation of Null ($H_0$) and Alternative ($H_a$) Hypotheses.

Statistical Methodology: Execution of T-tests to compare means between independent samples (Rainy Saturdays vs. Clear Saturdays).

Significance Evaluation: Selection and justification of the alpha ($\alpha$) level to determine the statistical weight of the results.


## 💡 Business Impact & Recommendations

The findings provide actionable intelligence for taxi fleets and dispatchers to:

Optimize Fleet Management: Adjusting supply levels based on weather-driven demand fluctuations.

Refine Pricing Strategies: Understanding how external environmental factors influence service delivery times.

Enhance UX: Providing more accurate ETA (Estimated Time of Arrival) predictions for airport commuters during inclement weather.
