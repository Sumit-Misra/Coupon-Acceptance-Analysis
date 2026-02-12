Project: Driving Coupon Acceptance Analysis
Executive Summary
This project analyzes survey data from the UCI Machine Learning Repository to investigate the factors that influence whether a driver accepts a mobile coupon for a local business. By utilizing Python, Pandas, and visualization libraries (Seaborn/Matplotlib), we identified key behavioral and contextual patterns that differentiate "accepters" from "non-accepters".
Key Findings
1. The Power of Habit
The strongest predictor of coupon acceptance is the driver's existing visit frequency to that type of establishment.
Bar Coupons: Drivers who visit bars more than 3 times a month accepted the coupon at a rate of 76.17%, compared to only 37.27% for infrequent visitors.
Coffee House Coupons: Regular coffee house patrons (visits > 1/month) accepted coupons at a rate of 65.90%, while infrequent visitors accepted at only 34.03%.
2. Social and Demographic Influences
Passenger Context: For bar coupons, acceptance rates are highest (70.94%) when the driver is in a social setting (friends or partners) without children present.
Age Factors: Drivers under the age of 30 who are already bar-goers show a high acceptance rate of 71.95%.
Budget Sensitivity: Interestingly, drivers who frequently visit cheap restaurants and have lower incomes were actually less likely to accept bar coupons (43.62%) compared to the core social demographic.
3. Environmental Impact
Time of Day: Coffee house coupons perform best during the mid-morning (10 AM) and mid-afternoon (2 PM) windows.
Temperature: Higher temperatures correlate with higher overall coupon acceptance across most categories.
Recommendations for Marketing Strategy
Target by Frequency: Prioritize coupon delivery to "known users" of a category rather than attempting broad acquisition of non-users.
Optimize for Social Settings: Focus "Bar" and "Expensive Restaurant" coupons on drivers traveling with friends or partners.
Time-Sensitive Coffee Promos: Schedule "Coffee House" pushes specifically for the 10 AM - 2 PM window to maximize conversion.
Repository Contents
Practical_Application_1.ipynb: The complete Jupyter Notebook containing data cleaning, exploratory data analysis (EDA), and visualizations.
data/coupons.csv: The raw dataset used for analysis.
README.md: This non-technical summary of findings and recommendations.
