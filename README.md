# Product-Analytics
## Project Overview
## Implementing a Performance Monitoring Dashboard to Monitor User Adoption and Engagement on VendBridge App
In this project, I explored how product analytics can be used to evaluate the performance and user engagement of VendBridge, a digital marketplace app launched by NexaLink. The aim was to understand how users are interacting with the app and identify what’s working, what’s not, and where improvements can be made. I used Tableau as the main tool for analysis and dashboard creation, working with a dataset that included daily active users, installations, sign-ups, transaction counts, app crashes, and time spent per user. I defined key product KPIs, built calculated fields, and designed a dashboard to give the product team clear visibility into how VendBridge is performing since its launch.
I used Tableau as the main tool for analysis and dashboard creation, working with a dataset that included daily active users, installations, sign-ups, transaction counts, app crashes, and time spent per user. I defined key product KPIs, built calculated fields, and designed a dashboard to give the product team clear visibility into how VendBridge is performing since its launch.

### Bsuiness Problem
NexaLink launched its new digital marketplace app, VendBridge, just three months ago, backed by a strong marketing push both before and after release. Given the scale of investment in promotions, the product team now needs clarity on how well the app is performing and whether it’s gaining traction with users.
My role as a Data Analyst Consultant was to help the team answer some key questions: 
- How has the market responded to VendBridge? Are users signing up, staying active, and completing transactions?
- Are there signs of churn or technical issues that need attention?
-  Implement an achievement-tiering system that classifies users into Gold, Silver,
Bronze, and Newbie tiers based on engagement percentiles.
- Forecast user activity for the next 30, 60, or 90
days based on historical trends and display confidence intervals to show the range of possible outcomes and account for
uncertainty in predictions.

### Data Sources
The dataset used for this project was obtained from Amdari website.
- [ Download Here](https://github.com/yiadomboakye/Product-Analytics/blob/main/VendBridge%20-%20Vendbridge.csv)

### Technical Tools Deployed
- Google Sheet: Used for data collection and preparation.
- Excel: Data validation and cleaning was done in excel to ensure accuracy, consistency and well formatted data.
- Tableau: Tableau will be used for building an interactive dashboard and
forecasting app trends.

### Exploratory Data Analysis
The Exploratory Data Analysis (EDA) focused on uncovering key insights from the Overview dashboard such as :
- KPIs
- Annually growth Rate
- Checking for spikes in crashes or uninstalls,signups.
- Time-series trends of installs, Daily Active Uninstalls, sign-ups and daily App Crashes.
- Regional and device-level breakdowns to compare engagement.

### Data Modelling
- Engagement Leaderboard: Created a dynamic leaderboard ranking regions based on DAUs, average time spent, and transaction frequency. Users were tiered into Gold, Silver, Bronze, and Newbie categories based on percentile rankings.
- Forecasting: Applied Tableau’s exponential smoothing to forecast user activity (DAUs, installs, and sign-ups) for the next 30, 60, and 90 days, including 95% confidence intervals.

 ### Results/Findings
#### Android Device Performance Report.
 - The Average Daily Active Users (DAU) has shown a growth trend, increasing by 
4.0% from July to August. This indicates that the app is maintaining or even 
improving its engagement level, which is a good sign that more users are actively 
interacting with the app daily. While the increase is positive, this growth is consistent 
with the previous month’s performance, indicating steady user engagement rather than 
a sharp rise.
- Although the number of transactions has slightly decreased by 0.9%, the drop is not 
drastic. This reduction follows a similar trend observed from the previous month’s 
slight decline of -3.1%. Despite an increase in DAU, fewer users are completing 
transactions.
- The current status of Total App Install is up by 11% from last month which means
app is experiencing strong growth in user acquisition, indicating successful market 
penetration.
- Total signups rate shows a 13.3% increase in the current month. This means the signup rate is also growing faster than app installs, suggesting that a higher proportion of 
installs are converting into active users.
- Current Status of churn rate: 1.2%, up by 3.8% from last month. The churn rate is 
increasing, which is a red flag. Higher churn could be due to app crashes, 
dissatisfaction with app performance, or lack of features that meet user needs.
- Current Status of average daily App crashes: 101 crashes, up by 17.1% from last 
month. The increase in crashes can negatively impact user retention and 
satisfaction.
#### IOS Device Performance Report.
- Current Status of Total App Install: 757,728 installs, up by 5.5% from last month.
The app is experiencing a growth trend in terms of installs, indicating a steady market 
penetration. However, the growth rate is lower compared to Android (11.4%), which 
could suggest room for improvement, especially in marketing campaigns or targeting 
specific user groups.
- Current Status of Total Sign Ups: 456,637 sign-ups, down by 1.4% from last 
month. While the app’s install rate is increasing, the slight decline in sign-ups 
suggests that fewer users are completing the registration process after installation.
- Current Status of User Signup Rate: 60.3%, down by 6.5% from last month. The 
significant drop in the user signup rate is concerning. This indicates that a larger 
proportion of users who installed the app did not complete the sign-up process.
- The increase in daily uninstalls is worrying, as it suggests that more users are 
abandoning the app.
- The increase in app crashes is a critical issue that could lead to more uninstalls and a 
higher churn rate.
- The rising number of app crashes and uninstalls suggests the app’s stability needs 
immediate attention. Addressing these technical issues will be crucial in reducing 
churn and retaining users.

##### User Acquisition Dashboard

![User Acquisition Dashboard](https://github.com/user-attachments/assets/83f8b244-f1c2-4285-b911-d2eccf89ca0e)


#### Engagement Dashboard
![Engagement Dashboard](https://github.com/user-attachments/assets/db6df630-a095-4cae-aabd-8f168666c9b2)



#### Trends
1.  Total App Installs
- There is fluctuating growth in app installs, with noticeable peaks and valleys.
- There appears to be consistent growth in installs over time, with certain spikes around 
late June, July, and August.
- End of August (around the 24th) shows a slight dip, which could represent a drop in 
installs or seasonal variation.

![Total App Installs](https://github.com/user-attachments/assets/ead0c3cf-4baa-4918-ac02-1de824cbd34f)


2. User Signups
- There are fluctuations in user signups over time, with clear spikes around late June, 
mid-August, and August 24th.
- While there are fluctuations, there’s a steady level of signups, which indicates that the 
app’s overall appeal is strong enough to bring in users consistently.

![User Signups](https://github.com/user-attachments/assets/44bd140c-e715-4c02-84b4-b1d1a5d0f5a9)

3. No of App Crashes
- The number of app crashes fluctuates significantly over the period, with sharp 
spikes around mid-June, mid-July, and late August.
- The significant spikes in app crashes are a clear indication that the app’s 
performance needs urgent attention.

![No of App Crashes](https://github.com/user-attachments/assets/d056c751-6e17-4839-903c-257906019960)

4. Total Uninstalls
- The spike on August 24th stands out, which is similar to the patterns seen in both app 
crashes and user signups. This suggests that app performance issues (e.g., crashes) 
might have led to increased uninstalls during this period.
- While the total number of uninstalls fluctuates, there seems to be an upward trend 
around certain periods, especially after app crashes or performance issues, indicating 
that these factors are influencing users to abandon the app.

![Total Uninstalls](https://github.com/user-attachments/assets/e3b356d4-78af-46d4-b688-24ba431bf302)

#### Overall Forecast Trend: Stability with Slight Decline.
- Historical Pattern: Consistent daily engagement around 2K-4K users with moderate fluctuations.
- Forecast Direction: All three timeframes (30, 60, 90 days) show a gradual declining trend.
- Confidence Level: The red confidence intervals indicate moderate uncertainty, suggesting forecasts are reasonably reliable.

####  Time-Horizon Specific Insights.
##### 30-Day Forecast
- Trend: Slight downward trajectory from current levels.
- Confidence: Narrow confidence bands indicate higher prediction accuracy.
- Range: Daily engagement expected to stay within 2K-3K range.
- Seasonality: Minimal seasonal variation detected.

##### 60-Day Forecast
- Trend: Continued gradual decline with stabilization
- Confidence: Wider confidence intervals reflecting increased uncertainty
- Pattern: More pronounced cyclical variations emerge.
- Risk: Potential for engagement to drop below 2K threshold.

##### 90-Day Forecast
- Trend: Stabilization at lower levels with persistent decline.
- Confidence: Widest confidence bands showing significant uncertainty.
- Long-term: Engagement settling around 2K-2.5K daily users.
- Volatility: Increased variability in predictions.

#### Critical Insights & Concerns: Declining Engagement Trajectory
- Consistent Decline: All forecast periods show downward trend.
- Magnitude: Approximately 15-20% decrease expected over 90 days.
- Acceleration: Rate of decline appears to stabilize in longer forecasts.

#### Uncertainty Patterns
- Increasing Uncertainty: Confidence intervals widen significantly with longer timeframes.
- Volatility Risk: 90-day forecast shows potential for significant swings.
- Prediction Reliability: 30-day forecasts most reliable for planning.

#### Forecasted Report

![Forecast Dashboard](https://github.com/user-attachments/assets/6d138ea1-7e49-4ca1-a0ca-fe5a32b3b572)


#### Leader Dashboard Report
![Leaderboard Report](https://github.com/user-attachments/assets/2d9060f2-6f2c-4507-be17-a5bb5a6c8faf)


  
