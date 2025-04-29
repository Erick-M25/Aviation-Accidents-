# Business Understanding

The aviation industry has been experiencing servere risks that require data-driven insights to inform operational decisions. 

This analysis leverages the National Transportation Safety Board's aviation accident dataset (2012-2022) to assess risk levels and patterns that will on making data driven decisions and recommendations for entering the aviation industry. 

The dataset includes critical parametrs such as accident timelines, aircraft purpose, weather conditions, make, ngine configurations, and injury severity, which will be analyzed to identify low-risk aircraft profiles.

## Data Pre-processing

I extracted data, Cleaned and Manipulated to fully understand our data set before diving into root course analysis. Thereafter, we will draw busines actionable insights and recommendations from the data analysed and advise the company on the possible risks and how to avoid them.

I downloarded The Aviation Accident Database & Synopses from Kaggle website. 
The data was provided by  the National Transportation Safety Board(NTSB).

It contained aviation accident data from 1962 to 2023 about aviation accidents in the U.S and aviation waters.The Aviation data was later loaded to Jupyter notebook as a data frame for further cleaning, manipulation and analysis.

I loaded the aviation dataset and :
1.Cleaned the column names, fixing date formats, and adding extracted data between 2012 and 2022
2.Drop missing values for critical columns then replaced nulls with with zero(0) for numerical columns and replaced missing values for non-numerical columns.3.
4.standardized the categories, Checked and dropped duplicates
5.Prepared a clean, well-structured dataset ready for trend analysis and studying flight risks.
6.Finally imported the cleaned data as 'Cleaned_aviation_data' 

**View Dashboard**: [**Interactive Dashboard**](https://public.tableau.com/views/Book1_17459315941030/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


 **Source**: [**Dataset**] (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)

# Business Goal
The business aims at:
# 1.Risk Profiling:
This would be helpful to Quantify how factors like weather instrumentation, engine count, and flight purpose correlate with accident likelihood and severity to prioritize safer aircraft models.

# 2.Understanding the trends hence need for proper Trend Analysis
Identify historical patterns in accidents such as  major causes, geographic hotspots to avoid high-risk operational conditions.

# 3.Obtaining Actionable Recommendations:
We will Provide evidence-based guidance for selecting low-risk aircraft and optimizing operational protocols.



### Questions to Address:
1. Has the number of accidents decreased over the last 10 years due to technological or regulatory improvements?
2. Which is the safest make and aircraft?
3. Do Instrument Meteorological Conditions (IMC) contribute to accidents compared to Visual Meteorological Conditions (VMC)?


# Key Findings
For the past 10 years number of accidents have been declining. Most of the accidents have been caused by VMC (94%)  compared to IMC with 5% contribution. Root cause analysis depicted some makes like Cessna and Piper contributing aboutb 74% of the total VMC.

Besides, airplanes prone to higher fatalities due to large number of people carrying capacity as compared to Helicopters. However, the high accident rate among personal-use aircraft is more concerning. It hints at deeper systemic issues such as lax maintenance routines, less formal pilot training, older aircraft technology, and potentially more relaxed attitudes toward flight safety.

#### Key Recommendations


 1. Aircraft Selection: 
 Prioritize  investing in aircrafts categories with the lowest accidents and fatality rates.
 2. Consider Helicopters to Airplanes
 3. Weather Conditions:
 Choose aircraft with strong IMC performance.
 Training: Reinforce pilot preparedness for weather and landing/takeoff risk.
 
