# Football-training-and-Performance-Optimization
This project involves utilizing StatsBomb football performance data to optimize training and performance in Football. Business Intelligence and Machine Learning Techniques were employed.
Tools involved: `Power BI`, `Python`, `DAX`, `Power Query`,  `JupyterLab`, `K-Means`, e.t.c

## Aim:
- to enhance decision-making processes related to athletic training, injury prevention, and overall performance improvement through the application of business intelligence and machine learning techniques.

## Achieved Objectives:
- Collect and clean StatsBomb football performance data to ensure its accuracy and consistency for subsequent analysis.
- Apply appropriate business intelligence and machine learning techniques to analyze the data, identifying key trends, patterns, and relationships.
- Based on the data analysis, identify key performance indicators (KPIs) that are most effective in assessing and monitoring individual and team performance.
- Develop data visualizations and interactive dashboards using Power BI to effectively communicate the identified KPIs and trends to stakeholders within the sports science industry.
- Evaluate the effectiveness of the proposed business intelligence and machine learning methods in optimizing training and performance, demonstrating their potential value and impact on the sports science industry.

## Dataset:

StatsBomb's GitHub repository offers a vast collection of football event data. This project uses StatsBomb data from the La Liga 2015/2016 season, focusing on Atlético de Madrid, who finished third with 88 points, just behind Real Madrid. The dataset originally includes two tables:

1. All events data from Atlético Madrid's matches during the 2015/2016 La Liga season.
2. Data on each match played that season.

[StatsBomb Open-source Repositiory](https://github.com/statsbomb/open-data)


## Dashboard Design
The dashboard consists of the following pages:
•	Home Page
•	Team Performance Overview
•	Decision Making Analysis
•	Possession Management Analysis
•	Injury Risk Assessment
•	Player Management

The Analysis Report document in this repo details report on BI and ML techniques used,  each dashboard page including key visuals/functions, metrics and KPIs.

## Some Key Findings:
For normal playing conditions:
- The average Decision-making Index of a player in the team is 0.68, indicating a relatively balanced performance in decision-making. However, the average shooting Decision Index is notably low at 0.32, suggesting suboptimal decision-making in shooting scenarios. Conversely, the average Passing Decision Index is relatively high at 1.04, indicating quicker and more successful decision-making in passing situations. This discrepancy sheds light on the team's poor shooting efficiency observed in the Team Performance Page of the Dashboard.
- Antoine Griezeman emerges as a standout performer with the highest Passing and Shooting Decision Indices (1.07 and 0.67, respectively), along with the highest overall Decision-making score of 0.87. This highlights Griezeman's exceptional ability to execute successful passes and shots on target swiftly, making him a crucial asset to the team.
- In contrast, Fernando Jose Torres Sanz exhibits slower decision-making tendencies, with a Passing Decision Index of 0.7 and a Decision-making score of 0.35, indicating potential areas for improvement in his performance.

For conditions in which passes and shots were executed under pressure:

- The team's average Decision-making score and Passing Decision Index decrease to 0.46 and 0.92, respectively. Additionally, it was observed that the average team player fails to hit the target when taking shots under pressure.
- Jackson Arley Martinez Valencia emerges as the standout decision-maker under pressure. With a Decision-Making Score of 0.82 and a Passing Decision Index of 1.65, the Left Centre Forward proves to be instrumental in the team's attacking prowess, showcasing exceptional skills in making quick decisions during the team's offensive buildup, potentially leading to goals or scoring opportunities.
- Conversely, Juan Francisco Torres Belen appears to be the slowest decision-maker when executing successful passes under pressure, with a Passing Decision Index of 0.67 and a subpar Decision-Making Score of 0.33.

These insights can inform strategic decisions aimed at optimizing player performance and enhancing overall team effectiveness. The insights gleaned from this dashboard offer valuable guidance for coaches, managers, or training teams at Athletico De Madri, suggesting tailored training programs aimed at bolstering athletes' cognitive abilities. These programs can target key areas such as situational awareness, anticipation, reaction time, and decision-making, particularly in shooting, and high-pressure scenarios.


