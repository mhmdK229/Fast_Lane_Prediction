# Fast_Lane_Price_Prediction

This project provides an in-depth analysis and prediction of Israel's fast lane pricing, identifying key factors that influence demand and prices across days and times:

Data Preparation: Data was aggregated to a 5-minute interval, and specific days (e.g., weekends, holidays) were excluded to focus on variable pricing periods. New features included surge pricing indicators, school schedules, and weather data (temperature, humidity).

Exploratory Analysis: The data revealed peak hours from 6:00 to 11:00 AM when prices increased significantly. Pricing also varied by day, with Tuesdays showing the highest averages and Thursdays the lowest.

Modeling & Prediction: Using both linear and logistic regression, we trained models to predict standard and surge prices, employing cross-validation to optimize performance. Clustering techniques helped isolate peak hours, and scenario-based modeling enabled adjustments for school and holiday effects.

Business Application: The analysis included a cost-benefit estimation of fast lane usage based on time saved and provided insights for strategic pricing adjustments to balance demand, particularly during high-use periods.

This project offers actionable recommendations to optimize pricing and maximize fast lane utilization by adapting to demand patterns and external factors.
