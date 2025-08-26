# YouTube_Trending_Videos_Analytics_Dashboard
This project involves creating an automated Tableau dashboard for analyzing YouTube trending video patterns to support advertising content strategy decisions at Sterling & Draper advertising agency. The dashboard replaces manual weekly reporting with real-time analytics for advertising campaign planning.
Business Context
Role: Video Advertising Analyst
Challenge: Weekly manual analysis of YouTube trending videos for marketing content recommendations
Solution: Automated dashboard providing self-service analytics for advertising managers
Key Stakeholders

Primary Users: Melanie and Ashok (New employees requesting weekly trend reports)
Target Audience: Video advertising campaign planning managers
Usage Frequency: Daily (minimum once per day)

**Dashboard Components & Specifications**
1. Historical Trends Analysis
Chart Type: Area Charts (Two variations)

"Historical Trends" Chart #1: Absolute values showing video trends over time by category
"Historical Trends" Chart #2: Percentage of total values showing relative distribution by category
Purpose: Track trending video volume patterns across different content categories over time

2. Geographic Distribution Analysis
Chart Type: Pie Chart

"Video Trends by Country" Chart: Relative values showing percentage distribution of trending videos by geographic region
Purpose: Understand regional preferences and market opportunities for advertising content

3. Category-Country Cross Analysis
Chart Type: Highlighted Data Table

"Video Trends by Country and Category" Table:

Structure: Countries as columns, trending categories as rows
Values: Absolute numbers of trending videos
Formatting: Cells highlighted based on value intensity (conditional formatting)


Purpose: Identify which content categories perform best in specific markets

4. Interactive Controls

Date and Time Filter: Enable temporal analysis and period comparisons
Country Filter: Focus analysis on specific geographic markets
Dashboard Title and Description: Context and usage instructions

**Technical Specifications**
Data Architecture
Database: youtube (dedicated database for trending video analytics)
Primary Table: trending_by_time (aggregated data table)
Data Structure:
record_id: Primary key identifier
region: Geographic country/region
trending_date: Date and time of trending status
category_title: Video content category
videos_count: Number of videos in trending section


**Data Management**
Update Frequency: Daily refresh at midnight UTC
Data Retention: Historical trending data for trend analysis
Data Quality: Pre-aggregated data ensures consistent performance

Key Analytics Questions Addressed

"What categories were trending last week?" - Historical trends charts show category performance over time
"How were trends distributed across regions?" - Geographic distribution chart reveals market variations
"Which categories were particularly popular in the United States?" - Country filter + category table provides US-specific insights

**Dashboard Design Principles**
Equal Importance: All charts weighted equally in layout and visual hierarchy
Self-Service Analytics: Eliminates need for manual weekly reports
Interactive Filtering: Users can drill down into specific time periods and regions
Visual Clarity: Multiple chart types optimize data comprehension for different analysis needs

**Business Value & Impact**
Automation: Replaces time-intensive manual weekly reporting process
Real-Time Insights: Daily data updates enable agile content strategy decisions
Strategic Planning: Historical and cross-regional analysis supports advertising campaign optimization
Scalability: Dashboard serves multiple users simultaneously without analyst bottleneck

**Technical Skills Demonstrated**
Business Intelligence Dashboard Design: User-centric layout and functionality
Data Visualization: Multiple chart types optimized for different analytical purposes
Interactive Analytics: Filter controls and cross-chart functionality
Database Integration: Connection to production data warehouse systems
Stakeholder Management: Translation of business requirements into technical specifications

**Expected Outcomes**
Operational Efficiency: Reduced manual reporting workload for analyst
Decision Speed: Faster access to trending video insights for campaign planning
Data Accessibility: Democratized access to YouTube trending analytics across the advertising team
Strategic Insights: Enhanced understanding of content performance patterns across markets and categories
