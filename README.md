Chicago Crime Data Analysis Project

🚀 Project Overview

This project dives into the analysis of crime data from Chicago, aiming to uncover patterns and trends. By preprocessing and analyzing the dataset, it seeks to provide meaningful insights and practical recommendations for improving public safety.

🛠️ Data Preprocessing Steps

1. Managing Duplicates

Case Number Column: Scanned for and eliminated duplicate records to ensure data consistency.

2. Exploring Missing Values

Examined dataset attributes to identify gaps in both categorical and numerical fields.

3. Addressing Missing Data

Numerical Fields (e.g., Latitude, Longitude, X Coordinate, Y Coordinate, Community Area):

Grouped data by Block and filled missing values using the median within each group.

Remaining missing entries were addressed with the overall column median.

Categorical Field (Ward):

Leveraged groupby on District and filled gaps using the mode of each group.

4. Dropping Non-Essential Columns

Removed the following: ID, Case Number, Description, X Coordinate, Y Coordinate, Location.

Reason: These fields lacked relevance for time-oriented trend analysis.

5. Feature Engineering for Temporal Data

Split the Date column into distinct Date and Time components.

Developed derived features including:

Month

Week

Hour

Season

Is Weekend

🕵️ Exploratory Data Analysis (EDA)

Through Python visualizations and Power BI dashboards, key patterns emerged:

Key Insights

1. Arrest Rates and Crime Trends

Observation: Areas with fewer arrests experienced higher crime rates.

2. Impact of Narcotics Abuse

Trend: Narcotics-related offenses surged in 2023-2024.

Link: Theft cases often fuel narcotics addiction, escalating into violent crimes like homicides.

3. Crime Timing Insights

Hot Hours: Peak theft incidents occur during evening hours and around midnight.

4. Seasonal Influence

Finding: Spring and Fall seasons see a notable rise in criminal activities.

💡 Recommendations

Raise Awareness:

Conduct campaigns on the risks of drug addiction.

Invest in initiatives to combat narcotics proliferation.

Boost Surveillance:

Deploy cameras in high-crime zones.

Enhance street lighting in poorly lit areas.

Strengthen Communities:

Offer safety workshops and self-defense training.

Build trust between residents and local law enforcement.

Strategic Policing:

Increase patrols in identified high-crime areas.

Late-Night Safety Initiatives:

Promote safer public practices during late hours.

📊 Power BI Dashboard

An interactive dashboard created in Power BI highlights key findings:

Arrest rates by crime type.

Seasonal crime fluctuations.

Hourly and daily heatmap visualizations.

📧 Contact Information

For inquiries or collaboration, feel free to reach out:

Author: Rohith V

Email: Rohithroshan047@gmail.com
