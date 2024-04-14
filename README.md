# Python-Driven CarMax Sales Analysis & Visualization

## About

This project delves into CarMax's sales data, exploring the relationship between customers' appraised vehicles and their subsequent purchases. Our analysis seeks to provide CarMax with actionable insights to refine business operations and deliver personalized shopping experiences. 
The dataset used for this analysis was sourced from Kaggle.

## Purposes Of The Project

The primary goal is to discern patterns within trade-in data that can inform strategies for inventory, pricing, and customer engagement, ultimately enhancing the customer experience and boosting CarMax's performance.

## About Data

The dataset comprises transactions from CarMax, detailing various attributes of vehicles both purchased and traded in by customers. Key columns include price, appraisal offer, mileage, make, model, and vehicle type, among others.

| Column Name              | Description                                             |
|--------------------------|---------------------------------------------------------|
| price                    | Customer's purchased vehicle price                      |
| appraisal_offer          | Appraised value of the customer's vehicle               |
| online_appraisal_flag    | Indicator of online (1) or in-person (0) appraisal      |
| model_year               | Model year of the purchased vehicle                     |
| mileage                  | Mileage of the purchased vehicle                        |
| make                     | Make of the purchased vehicle                           |
| model                    | Model of the purchased vehicle                          |
| trim_level               | Trim level of the purchased vehicle                     |
| vehicle_type             | Type of the purchased vehicle                           |
| color                    | Color of the purchased vehicle                          |
| engine                   | Engine type of the purchased vehicle                    |
| cylinders                | Number of cylinders in the purchased vehicle            |
| mpg_city                 | City mileage per gallon of the purchased vehicle        |
| mpg_highway              | Highway mileage per gallon of the purchased vehicle     |
| horsepower               | Horsepower of the purchased vehicle                     |
| fuel_capacity            | Fuel capacity of the purchased vehicle                  |
| model_year_appraisal     | Model year of the appraised vehicle                     |
| mileage_appraisal        | Mileage of the appraised vehicle                        |
| make_appraisal           | Make of the appraised vehicle                           |
| model_appraisal          | Model of the appraised vehicle                          |
| trim_level_appraisal     | Trim level of the appraised vehicle                     |
| vehicle_type_appraisal   | Type of the appraised vehicle                           |
| color_appraisal          | Color of the appraised vehicle                          |
| engine_appraisal         | Engine type of the appraised vehicle                    |
| cylinders_appraisal      | Number of cylinders in the appraised vehicle            |
| mpg_city_appraisal       | City mileage per gallon of the appraised vehicle        |
| mpg_highway_appraisal    | Highway mileage per gallon of the appraised vehicle     |
| horsepower_appraisal     | Horsepower of the appraised vehicle                     |
| fuel_capacity_appraisal  | Fuel capacity of the appraised vehicle                  |
| State                    | State where the vehicle transaction occurred            |
| days_since_offer         | Days between appraisal offer and sale to CarMax         |


### Analysis List

1. Appraisal vs. Purchase Trends:
Examine how the characteristics of appraised vehicles correlate with the vehicles purchased.
2. Pricing Strategy Insights:
Utilize regression analysis to understand the relationship between appraisal offers and purchase prices.
3. Brand Loyalty Assessment:
Analyze brand retention during the trade-in process to gauge customer loyalty.
4. Vehicle Type Preference:
Investigate trends in vehicle type changes from trade-in to purchase.
5. Color Popularity and Changes:
Identify patterns in color preferences and changes during the trade-in process.

## Approach Used

1. Predictive Modeling:
Employ regression analysis and other statistical methods to predict sales trends.
2. Customer Behavior Analysis:
Leverage trade-in data to understand customer preferences and behaviors.
3. Inventory Optimization:
Recommend strategic inventory adjustments based on data insights.
4. Visualizations:
Present findings through clear and impactful visualizations.

## Business Questions Answered

1. How do appraisal values influence purchasing decisions?
2. What vehicle attributes most significantly affect the choice of purchase?
3. How does customer loyalty manifest in brand and vehicle type preferences?
4. Can vehicle color choices in trade-ins predict purchase preferences?

## Recommendations

1. Optimize Pricing Strategy:
Implement dynamic pricing aligned with appraisal values to meet customer expectations.
2. Enhance Loyalty Programs:
Develop loyalty incentives for brands and vehicle types that show high customer retention.
3. Tailor Inventory to Customer Preferences:
Adjust inventory to reflect popular models and features derived from sales data.
4. Leverage Mileage and Vehicle Year Data:
Use mileage and model year trends to forecast customer purchasing preferences.
5. Proactive Customer Engagement:
Initiate targeted ad campaigns based on insights from vehicle color trends and customer behaviors.
