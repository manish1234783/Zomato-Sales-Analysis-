#Project Title / Headline

Zomato Global Gastronomy: Strategic Market Intelligence Dashboard

📝 Short Description
Developed a comprehensive market intelligence solution analyzing a global dataset of over 9,500 restaurants across 15 countries. By engineering a structured dimensional data model from raw restaurant logistics, this project uncovers global dining trends, digital feature adoption (online delivery vs. table bookings), geographic distributions, and pricing strategies to help restaurant aggregators make data-driven decisions for expansion and partnership optimization.

#🛠️ Tech Stack
Data Transformation & Modeling: Advanced Microsoft Excel, Power Query

Analytics & Business Intelligence: Power BI / Excel Dashboard Architecture

Calculated Metrics: DAX (Data Analysis Expressions) / Custom Excel Formulas

Data Structure: Star Schema Architecture (Dimension and Fact tables)


#Data Source
Dataset Name: Zomato Global Restaurant Network (Excelr)

Data Scale: 9,551 unique restaurant listings across 15 countries and 32 data dimensions.

Core Attributes: Restaurant Logistics (ID, Name, Location Coordinates, Cuisines), Operational Metrics (Has_Table_booking, Has_Online_delivery), Financial Metrics (Average Cost for Two, Currency, Price Range/Bucket), and Engagement Metrics (Ratings, Total Votes).



#eatures & Key Highlights
Automated Data Engineering (ETL): Utilized Power Query to transform raw transactional data into an analysis-ready star schema. Formatted time metrics, extracted financial months/quarters, and built mapping tables to translate numeric country codes into geographic strings.

Geographic & Regional Performance Mapping: Built deep-dive views segmenting restaurant counts, average ratings, and average costs across global regions and major cities to pinpoint high-growth, underserved market sectors.

Operational Feature Matrix Analysis: Evaluated the market penetration of value-added digital features by cross-referencing Has_Online_delivery and Has_Table_booking statuses against total consumer engagement (Votes) and rating tiers.

Dynamic Time-Series & Launch Metrics: Analyzed historical restaurant opening trajectories by filtering data chronologically by Year, Quarter, Month, and Weekday to discover seasonal trends in food-tech adoption.

Strategic Price Segmentation: Created custom Price_bucket categories (e.g., separating low, mid, and premium cost tiers) to evaluate how consumer rating trends and restaurant density correlate with cost boundaries.

Interactive Executive Dashboard: Compiled KPIs and core analytical slices into a dynamic, unified corporate dashboard enabling stakeholder drill-downs across rating bands, localized cuisines, and regional boundaries.



#key quastions

🗺️ Geographic & Market Expansion Questions
Which countries and cities represent the highest density of restaurant partners, and where are the untapped markets?

Analytical approach: Segmenting the total count of restaurants across geographic dimensions to identify primary hubs versus growth regions.

How does the cost of dining scale globally, and what are the currency risk factors for platform revenue?

Analytical approach: Mapping Average_Cost_for_two and normalizing across different local currencies to understand market-specific purchasing power.

📱 Digital Adoption & Feature Penetration
Does enabling digital convenience features directly correlate with higher customer engagement and ratings?

Analytical approach: Comparing average ratings and total Votes between restaurants that offer Has_Online_delivery or Has_Table_booking against those that do not.

Are low-adoption outlets lagging in performance due to a lack of digital infrastructure?

Analytical approach: Isolating specific cities or price points with low online delivery penetration to identify ideal targets for sales team onboarding.

💰 Pricing Strategy & Consumer Behavior
What price segments dominate the global ecosystem, and where is the sweet spot for maximum user engagement?

Analytical approach: Bucketing restaurants into custom Price_bucket ranges and evaluating which tier captures the highest volume of user feedback (Votes).

Do premium-priced restaurants maintain significantly higher customer satisfaction ratings compared to budget options?

Analytical approach: Running an aggregation of Rating across different Price_range flags to identify performance benchmarks.

🕒 Seasonality & Operational Trajectory
What are the historical growth trajectories and seasonal timelines for restaurant onboarding on the platform?

Analytical approach: Analyzing the Datekey_Opening fields by Year, Quarter, and Financial Months to spot cyclical peaks or slowdowns in network expansion.

Are there specific weekdays where new partner launches peak, indicating optimal operational release windows?

Analytical approach: Evaluating restaurant opening trends against Weekday_name to map out developer or operational launch workflows



#Business Insights

# 1 :The "Digital Feature Premium" Matrix
 Online Delivery Impact: Restaurants that have enabled online delivery (Has_Online_delivery = Yes) sustain an average customer rating of 3.29 out of 5, outperforming offline-only listings which sit at a lower 2.75 average. Furthermore, delivery-enabled partners capture 53% higher engagement volume, averaging 211 user votes per listing compared to 138 votes for non-delivery venues.

Table Booking Revenue Multiplier: The impact of digital table reservations (Has_Table_booking = Yes) is even more profound. Restaurants offering booking services secure an impressive 3.48 average rating. More importantly, they pull in an astronomical 353 votes per listing on average—a 171% surge over non-booking venues (130 votes).

Strategic Growth Opportunity: There are 7,100 partner restaurants currently listed on the platform that do not offer online delivery. Merchant onboarding teams can utilize these metrics as a powerful B2B sales narrative, directly demonstrating to restaurant owners that activating digital features unlocks superior platform algorithm placement, customer reach, and ratings.

2. Geographic Saturation & The International "Rating Variance"
Analyzing the platform through a regional lens reveals a highly concentrated ecosystem that requires two completely different corporate growth strategies.

Severe Core Market Concentration: The network is overwhelmingly centered in its home market. 90.59% of the entire global dataset (8,652 out of 9,551 total listings) is located entirely within India. The remaining ~9.4% of international operations is led by the United States (434 listings) and the United Kingdom (80 listings).

The Domestic Delivery Dependency: In India, the presence of platform delivery services dictates a restaurant's baseline success. Indian restaurants operating without online delivery suffer from a highly critical 2.57 average rating. However, when Indian partners activate online delivery, their satisfaction scores shoot up to 3.28.

The International Quality Benchmark: Outside of India ("Rest of World"), the marketplace dynamics shift entirely. International restaurant partners maintain an exceptional organic baseline rating of 4.05 out of 5 even without online delivery.

Strategic Expansion Action: In India, Zomato’s primary mission must remain focused on operational integration—bringing smaller, low-rated vendors into standardized delivery frameworks to stabilize their metrics. Globally, the strategy must pivot to localized marketplace prestige—partnering primarily with highly established, high-end culinary venues to capture premium transaction margins.

3. Price Segment Engineering & User Interaction Sweet Spots
Segmenting the global network across localized pricing brackets clarifies exactly which cost thresholds generate volume versus where the platform extracts premium engagement value.

The Low-End Volume Trap: The platform’s network is highly saturated at the lower end, with over half of all listed partners (5,174 restaurants) sitting squarely within the lowest 0-500 price bucket. This hyper-budget segment underperforms significantly across all success metrics, bringing in the worst customer satisfaction metrics (2.61 average rating) and absolute minimal user engagement (85.9 average votes).

The High-Velocity "Sweet Spot": The optimal balance of consumer interaction and corporate scalability sits within the mid-to-high tier 1000-2000 price bucket. While it represents only 1,088 restaurants, it yields an outstanding 3.62 average rating and commands the single highest engagement volume on the entire platform, pulling in 458 votes per listing.

The Premium Cap: While ultra-premium restaurants (3000+ cost bucket) capture the highest absolute baseline satisfaction at a 3.83 average rating, their interaction drops significantly to 322 average votes due to their niche exclusivity.

Strategic Portfolio Balancing: Marketing algorithms and dynamic, high-visibility ad placements should intentionally prioritize the mid-to-high tiers (1000-2000 and 2000-3000). These mid-premium operators possess both the financial margins to sustain platform marketing ad spend and an active, vocal customer cohort that drives long-term customer retention on the application.


#Screenshorts/ Demo

Example : https://github.com/manish1234783/Zomato-Sales-Analysis-/blob/main/Zomato%20Analysis%20Dashboard
