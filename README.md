# Zomato-Analysis Data Analyst (Creating interactive dashboard using Excel & Power BI)

## Project Objective
The objective of the Zomato analysis is to extract insights from restaurant data, It explores customer preferences through ratings, reviews, and cuisine trends,By studying pricing, location, and delivery options, it reveals market patterns, The project helps understand what drives customer satisfaction and loyalty, It identifies top-performing restaurants and competitive advantages, This analysis supports better marketing and business strategies, It can guide restaurants in improving visibility and performance. Overall, the goal is to make data-driven decisions using Zomato’s platform.

# Dataset Used
- <a href="https://github.com/Soumya-2102/Zomato-Analysis/commit/08f6e84d3aa7a64342f2e9f31b95c7240a54185a">Zomatoanalysisdata</a>

## Questions(KPI'S)
1. Build a Data Model using the Sheets in the Excel File
2. Build a Calendar Table using the Columns Datekey_Opening ( Which has Dates from Minimum Dates and Maximum Dates)
  Add all the below Columns in the Calendar Table using the Formulas.
   A.Year
   B.Monthno
   C.Monthfullname
   D.Quarter(Q1,Q2,Q3,Q4)
   E. YearMonth ( YYYY-MMM)
   F. Weekdayno
   G.Weekdayname
   H.FinancialMOnth ( April = FM1, May= FM2  …. March = FM12)
   I. Financial Quarter ( Quarters based on Financial Month FQ-1 . FQ-2..)
3. Convert the Average cost for 2 column into USD dollars (currently the Average cost for 2 in local currencies
4.Find the Numbers of Resturants based on City and Country.
5.Numbers of Resturants opening based on Year , Quarter , Month
6. Count of Resturants based on Average Ratings
7. Create buckets based on Average Price of reasonable size and find out how many resturants falls in each buckets
8.Percentage of Resturants based on "Has_Table_booking"
9.Percentage of Resturants based on "Has_Online_delivery"
10. Develop Charts based on Cusines, City, Ratings ( Candidate have to think about new KPI to analyse)
11. Build a Dashboard for the KPI's Above.

## Process
1. Data Collection
Restaurant data from Zomato covering 15 countries and 9,551 restaurants was collected.
Information includes:
Location (country, city)
Ratings, average cost
Cuisines
Online delivery & table booking availability
Year and month of opening

2. Data Cleaning & Preprocessing
Countries and cities were standardized.
Missing values were likely handled (e.g., in ratings or cost).
Ratings were categorized into ranges (0-1, 1.1-2, etc.).
Prices were bucketed into ranges (e.g., 0–300, 301–600, etc.).
Dates were broken down into Month, Year, Financial Quarter, and Quarter.

3. Data Transformation
New metrics were created:
Buckets for average pricing
Rating bands
Boolean values for “Online Delivery” and “Table Booking”
Grouped data to find top 10 cities with the most restaurants.
Created calculated fields like Total USD Rate, Average Rating, Number of Tables Booked, and Successful Deliveries.

4. Dashboard & Visualization (Power BI/Tableau/Excel)
KPIs shown on top: Total Restaurants, Countries, Avg Rating, etc.
Key visual insights include:
Country-wise distribution of restaurants (India has the most).
Monthly and yearly trends of restaurant openings.
Top 10 cities by restaurant count (New Delhi highest).
Rating distribution (most restaurants fall in 3.1–4).
Cuisine analysis by city and rating.
Pie charts showing:
Online Delivery % (74.34%)
Table Booking % (12.12%)

5. Insights Derived
India leads with 8652 restaurants—vastly ahead of other countries.
Most restaurants opened in September and March.
New Delhi, Gurgaon, Noida are top-performing cities.
Only 25.66% of restaurants offer online delivery.
Only 12.12% support table booking—potential growth area.

6. Business Recommendations
Zomato can focus on expanding table booking and delivery services.
Cities like New Delhi and Gurgaon show high restaurant density—good for promotions or partnerships.
Ratings improve with higher price brackets, suggesting cost correlates with customer satisfaction.

## Key insights
India Dominates the Dataset
India has the highest number of restaurants (8,652), significantly more than any other country in the dataset.

Top Performing Cities
New Delhi leads with 5,473 restaurants, followed by Gurgaon (1,118) and Noida (1,080).
These cities are the core focus areas for Zomato operations.

Most Common Ratings Range
Majority of restaurants (4,509) fall under the 3.1 – 4.0 rating range, showing an overall moderate customer satisfaction.

Opening Trends
Most restaurant openings occurred in March and September, suggesting peak months for new launches.

Yearly Growth
Highest number of restaurants were opened in 2018 (1,102) and 2011 (1,088), indicating strong growth during these years.

Pricing Buckets
Most restaurants fall in the 301–600 price range, suggesting a preference for mid-range dining.
Only a small portion is in the high-price bucket (1001–45000).

Online Delivery
Only 25.66% of restaurants offer online delivery, while 74.34% do not—indicating a large untapped potential for online delivery services.

Table Booking Availability
Just 12.12% support table booking; 87.88% do not—this could be an area for strategic expansion.

Cuisine Insights
North Indian and Chinese cuisines dominate across major cities like New Delhi, Noida, and Gurgaon.

Currency Rate Consideration
The dashboard also tracks the USD conversion rate (3.76) for price normalization across countries.

## Conclusion
Zomato has firmly positioned itself as a leading food-tech company in India, offering restaurant listings, user reviews, and efficient food delivery services. Through strategic acquisitions like Uber Eats India and Blinkit, it has expanded its market reach while competing against rivals like Swiggy. The company continues to innovate with ventures such as Hyperpure, catering to the B2B segment, and quick commerce to meet evolving consumer needs. Increasing smartphone adoption and demand in smaller cities further drive its growth. Financially, Zomato has faced challenges, including profitability concerns and adapting to post-pandemic market shifts, but its diversified business model and strong brand recognition provide a competitive edge. Its long-term success will depend on its ability to navigate industry trends, enhance unit economics, and sustain customer engagement in an ever-changing digital landscape.


