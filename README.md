# Final-Project-Tableau

## Project/Goals
The objective is to identify the attributes that FIFA prioritizes when calculating players' overall ratings. I chose the overall rating as the primary data for analysis, considering its significance to FIFA players, media, and the players themselves. This metric often takes center stage in FIFA marketing during each game release. This would be a way to get a behind-the-curtain view into their calculations.  

## Process
Step 1: Conducted extensive Exploratory Data Analysis (EDA) in Python, utilizing functions such as .describe(), .info(), etc.
Step 2: Cleaned the data in Python by dropping columns like photos, flags, and club logos. Selected only the first preferred position for accuracy. In Tableau, transformed Nationality into country/region to leverage map features.
Step 3: Created 5 charts for the overall data.
Step 4: Categorized preferred positions into attackers, midfielders, defenders, and goalkeepers.
Step 5: Constructed visualizations of regression models for each position.
Step 6: Consolidated findings into dashboards and a tableau story.


## Results 
Option 2: FIFA18 data. Developed various visualizations including maps for player nationality based on overall, histograms for overall ratings distribution, clusters for wage vs value, scatter plots for position-wise overall ratings vs value, and line graph: check age vs overall between defenders and non-defenders. Key findings: Top 3 attributes with the highest R-Squared for overall ratings vary by position—attackers: Ball Control, Position, and Reactions; defenders: Interceptions, Marking, and Reactions; goalkeepers: Diving, Positioning, and Reflexes. Overall ratings exhibit a bell curve, suggesting FIFA maintains this distribution to balance ratings across positions. This suggests that FIFA might intentionally adhere to the bell curve distribution, ensuring a balanced distribution of ratings to not give too many low or high ratings.

## Challenges 
The abundance of columns and attributes posed a challenge, particularly in identifying attributes with the highest R-Squared for each position. Deciding which columns to focus on and which to overlook added complexity.

## Future Goals
Future analysis could involve examining each position individually to pinpoint the most influential attribute for overall ratings. Additionally, exploring the impact of age, value, and wage on overall ratings could provide deeper insights.

