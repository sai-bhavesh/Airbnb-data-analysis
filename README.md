# Airbnb-data-analysis
🏙️ Airbnb NYC 2019 Dataset Analysis – Summary
✅ Dataset Info
Dataset: NYC Airbnb Listings (bnb)
Key columns: price, room_type, neighbourhood, neighbourhood_group, availability_365, number_of_reviews, minimum_nights, host_id
📌 Key Analyses Performed
1. Most Reviewed Listings
Sorted by number_of_reviews
Identified top 10 most reviewed listings
Checked their availability_365
2. Expensive but Rare Listings
Filtered listings where price > $500 and availability_365 < 30
Identified listings that are premium but barely available
3. Superhost Detection
Found hosts with more than 10 listings
Calculated total and average availability for those hosts
4. Costliest Neighbourhoods
For each neighbourhood_group, found the neighbourhood with the highest average price
5. Review Distribution by Price Segment
Compared average number_of_reviews between listings priced < $100 and > $500
6. Room Type Availability
Found room types most frequently available over 300 days/year in each borough
Calculated and compared proportions
7. Long-Term Listing Zones
Filtered listings with minimum_nights > 30
Identified top neighbourhoods focused on long-term rentals
8. Correlation Matrix
Analyzed relationships between price, number_of_reviews, minimum_nights, availability_365
Visualized with a heatmap
🧼 Data Cleaning
Removed rows with missing or inconsistent values
Stripped extra spaces in neighbourhood_group
Handled outliers in price and minimum_nights
Converted data types where needed
📈 Visualizations Used
Bar charts (horizontal & vertical)
Heatmaps (correlation)
Line and scatter plots
Grouped bar charts for comparative insights
✅ Final Outcome
You have:

Performed deep exploratory data analysis (EDA)
Uncovered host behaviors, pricing patterns, and guest trends
Used advanced filtering, grouping, and visual storytelling
Built a solid analytical foundation for Airbnb business insights
🔥 Amazing work wrapping this up!
