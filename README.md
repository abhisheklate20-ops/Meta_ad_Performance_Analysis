# Meta ad Performance Analysis

## 1.	Description
"This is a Meta Ad Performance Dashboard that tracks the effectiveness of ad campaigns across key KPIs such as impressions, clicks, engagements, conversions, and budget. It provides a complete funnel view—from awareness to engagement to purchases along with demographic, geographic, and time-based insights."

## 2.	Tech Stack
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

## 3. Walk through of key visuals

•	Impressions → Number of times ads were displayed.
• Clicks → Number of times users clicked ads.
•	Shares → Number of times ads were shared.
•	Comments → User comments on ads.
•	Purchases → Conversions after seeing ads.
•	Engagements → Total interactions (Clicks + Shares + Comments).
•	CTR (Click Through Rate) → % of impressions that resulted in clicks.
•	Engagement Rate → % of impressions that resulted in engagements.
•	Conversion Rate → % of clicks that resulted in purchases.
•	Purchase Rate → % of impressions that resulted in purchases.
•	Total Budget → Total spend allocated to campaigns.
•	Avg. Budget per Campaign → Average budget allocation per campaign.

•	Target Gender - Donut Chart
  1. Displays performance split by gender.
  2. Metric (Impressions, Clicks, Purchases, etc.) changes dynamically.
  3. Purpose: Identify which gender segment contributes most to the selected metric.

•	Target Age Group - Bar Chart
  1. Shows engagement across age groups.
  2. Purpose: Highlight which age group is most responsive.

•	 Country - Map Visualization
  1. Geographic view of campaign reach and engagement.
  2. Bubble size or color intensity represents the selected metric.
  3. Purpose: Understand performance distribution by country.

•	 Calendar Month - Heat Map
  1. Monthly performance plotted using ad event timestamps.
  2. Darker shades = higher activity.
  3. Purpose: Detect seasonal trends, peak months, and low-activity periods.

•	 Weekly Trend - Stacked Column Chart
  1. Weekly performance trends by ad type.
  2. Purpose: Compare ad type contributions over weeks.

•	 Hourly Trend - Area Chart
  1. Shows activity by hour of day (0–23).
  2. Purpose: Understand user activity patterns throughout the day.

•	 Ad Type - Matrix Visualization
1. Compares performance across ad types and platforms (Facebook vs Instagram).
2. Purpose: Side-by-side comparison of formats and platforms.

## 4. Business impact & Insights

### KPI Metrics
• Impressions: 216K: Total times the ads were shown. Good reach.
• Clicks: 25.4K: Number of people who clicked on the ads.
• Shares: 1.3K, Comments: 2.6K: Indicators of organic engagement (beyond paid reach).
• Purchases (Conversions): 1.3K: Real customer acquisitions from ads.
• Engagements: 29K: Sum of clicks, likes, shares, comments.
• CTR (Click-Through Rate): 11.76%: Strong performance (above industry average ~1-2%). Ads are very attractive.
• Engagement Rate: 13.56%: Very healthy; content resonates with the audience.
• Conversion Rate: 5.21%: Out of all clicks, 5.21% converted into purchases. Good but could improve with landing page optimization.
• Purchase Rate: 0.61%: Out of impressions, only 0.61% resulted in purchases. Low conversion funnel efficiency (room to optimize).
• Total Budget: 2.5M: Total ad spends.
• Avg Budget per Campaign: 50.7K: Suggests multiple campaigns were run.
→ Insight: Ads are performing strongly in visibility and engagement, but actual purchase
efficiency is weak: need to optimize targeting/landing pages.
• High CTR (11.76%) and Engagement Rate (13.56%) → clearly indicate that the ad creatives, messaging, and targeting at the top of the funnel are very effective.
→  People are interested enough to click, like, share, or comment.
• Low Purchase Rate (0.61%) and only 1.3K conversions out of 216K impressions
→ shows a sharp drop-off in the lower funnel. This is a classic case of "awareness and interest" being strong but "action (purchase)" being weak.

### Engagement Breakdown
• By Gender (Donut Chart)
    Female: 13K (43%)
    Male: 6K (22%)
    Other/Not Specified: 10K (35%)
→ Females engage more than males; campaigns could be tailored toward female audiences.
• By Target Age (Bar Chart)
    Peak engagement: 20–30 age group (especially early 20s).
    Drops significantly after 35+.
    Primary audience = Young adults.
→ Insight: Target ads towards females aged 18–30 for better ROI.
### Geographic Distribution
• Top Engaged Countries
    US, India, Brazil, Germany, UK are major contributors..
→ Insight: Focus campaigns in India & US (high potential, high engagement), and premium campaigns in Germany/UK (better conversion potential due to higher purchasing power).
### Time-Based Trends
• Weekly Engagement Trend (Stacked Bar)
    Fairly consistent across weeks, with no sharp drop.
    Steady engagement shows ads maintain attention.
• Hourly Engagement Trend (Line Chart)
    Peaks around late afternoon & evening (~15–20 hours).
    Lowest engagement early morning (~0–5 hours).
→ Insight: Schedule ad delivery during afternoons & evenings for maximum impact.

### Analysis by Ad Type (Bottom-Right Table)
Ad Type Impressions Clicks CTR Purchase Rate Conversion Rate Engagement Rate
Carousel 48K 6K 11.7% 0.59% 5.1% 13.4%
Image 51K 6K 11.7% 0.57% 4.9% 13.5%
Stories 72K 8K 11.8% 0.65% 5.2% 13.6%
Video 46K 5K 11.9% 0.62% 5.2% 13.7%
    Video ads have the highest CTR, CR, ER (best-performing).
    Stories ads also perform strongly with higher impressions.
    Images/Carousels have decent performance but slightly lower conversions.
→ Insight: Focus budget more on Video & Story ads for better ROI.

## 5.	Screenshots / Demos
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/the-mansi-goel/Ski-dashboard/blob/main/Snapshot%20of%20the%20Dahbaord.png)# Meta_ad_Performance_Analysis
