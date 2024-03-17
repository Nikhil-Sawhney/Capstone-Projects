Business Task: 
Leverage Fitbit data to understand user behavior and identify growth opportunities for the company's marketing efforts.

Data Acquisition:
Kaggle dataset containing anonymized Fitbit user data (steps, sleep, heart rate, activity intensity) from 30 individuals.
Selection: Five relevant CSV files chosen for further analysis.

Data Preprocessing:
Cleaning-  No duplicates or missing values found. Unnecessary columns removed, date formatting adjusted. "Text to Columns" function used to separate date and time when needed.
Feature Engineering: A new "TotalActiveMinutes" column was added to the "daily_Activity" table by summing "VeryActiveMinutes," "FairlyActiveMinutes," and "LightlyActiveMinutes."

Data Modeling (Power BI):
New calculated column "Week Day" added to relevant tables for weekday-based analysis.
Two additional tables ("Date" and "ID") created to establish relationships among all data sets.

Data Analysis:

Statistical Findings:
-Average daily steps: 7638 (approx. 5.5 km)
-Average sedentary time: 991 minutes (16 hours 31 minutes)
-Average active time: 228 minutes (3 hours 8 minutes)
-Average daily calorie burn: 2304 (equivalent to 0.3 kg)

Activity Status:
-Users spend most of their time (81%) sedentary, with minimal time in very active categories.
Busiest Time of Day:
Activity starts around 6 AM.
Peak hours are noon-2 PM and 5-7 PM.
Activity levels drop significantly after 8 PM, reaching a low between midnight and 5 AM. 

Most Active Time of Day:
Both average steps and calories burned follow a similar pattern, with a rise after 6 AM and a significant decrease after 6 PM. This suggests a correlation between activity levels and working/studying hours.

Active Time of Week and Heart Rate:
Saturdays show the highest average heart rate (80 bpm) and longest active minutes (244.27, or 4.1 hours), indicating increased activity on weekends.

Most Active Days of the Week:
Tuesdays and Saturdays are the most active days, while Sundays are the least active. 
Average calorie expenditure mirrors the trend of average steps throughout the week. 

Factors Affecting Calories Burned:
A positive correlation exists between calories burned and factors like total steps, distance covered, and total active minutes.

Relationship Between Sleep Time and Time in Bed:
A strong correlation exists between sleep duration and time spent in bed. However, some outliers indicate occasional periods of wakefulness in bed. (Image 8 & 9)

Key Insights:
-Users are largely inactive (81.2%).
-A positive correlation exists between steps taken and calories burned.
-Users are most active between 6 AM and 8 AM, noon-2 PM, and 5-7 PM. Activity levels drop significantly after 8 PM.
-Average sleep duration is 7 hours per night, with Sundays having the longest sleep times.

Marketing Recommendations:
-Inactivity Timer: Implement a timer within the app to remind users to move after extended periods of inactivity.
-Fitness Challenge Groups: Introduce a feature allowing users to compete with friends or family in achieving weekly goals, especially on weekends. Offer digital rewards for winners to incentivize participation.
-Short Exercise Integration: Develop a feature suggesting short, intense exercises or jogging routines, particularly in the mornings (between 6 AM and 7 AM) when users tend to become active.
-Customer Satisfaction Surveys: Conduct weekly surveys based on tracked data to understand reasons behind user inactivity. This can help identify potential issues like illness.
-"User Nearby" Premium Feature: Introduce a premium feature allowing users to search for running partners in their vicinity. This fosters a sense of community and generates additional revenue.

By implementing these recommendations, Fitbit can address user behavior patterns and promote a more active lifestyle, ultimately leading to a more successful marketing strategy.
