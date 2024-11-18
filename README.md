Vehicle Data Analysis and Dashboard:

This project analyzes a vehicle dataset using Python and Tableau. After cleaning and transforming the data with Python and Pandas, 
I created an interactive dashboard in Tableau to visualize key metrics such as vehicle make, model, year, quantity, location, and MSRP. 
Additional metrics like battery type, battery range, and type of fuel were also analyzed, providing insights into vehicle energy efficiency and market trends. 

<img width="1440" alt="Screenshot 2024-11-18 at 4 35 53 PM" src="https://github.com/user-attachments/assets/1ce46283-a308-4f8e-a78d-ff4a0a73cd3e">




This dashboard enables a vehicle manufacturer to leverage data-driven insights to optimize sales strategies and maximize revenue potential.

Project Overview
Steps Involved
Data Cleaning and Transformation: Processed raw vehicle data in Python with Pandas.
Data Visualization: Created an interactive dashboard in Tableau showcasing various metrics, including energy-related insights.
Insights for Business Strategy: Illustrated how a vehicle manufacturer can use this dashboard to make informed decisions and drive profitability.
Data Description
The dataset includes the following columns:

Make: The vehicle’s brand (e.g., Toyota, Ford).
Model: The specific vehicle model (e.g., Corolla, F-150).
Model Year: Year of manufacture.
Quantity: Number of units available or sold.
Location: The state in which the vehicle is located.
Battery Type: Type of battery used (for electric vehicles).
Battery Range: Range capacity of the battery, indicating energy efficiency.
Type of Fuel Used: Specifies whether the vehicle uses gasoline, diesel, electric, or hybrid fuel.
Base MSRP: Manufacturer’s Suggested Retail Price, used as a revenue benchmark.
Data Cleaning and Transformation
Using Python and Pandas, I conducted the following steps to clean and prepare the data:

Removed Duplicates: Eliminated duplicate records to ensure accuracy.
Handled Missing Values: Addressed missing values by either filling or removing incomplete records as necessary.
Data Standardization: Standardized text fields (e.g., Make, Battery Type, and Fuel Type) for consistent categorization.
Data Type Conversion: Ensured correct data types for fields such as battery range (integer) and MSRP (float).
Calculated Fields: Derived additional insights, including potential revenue by model and total revenue by state based on quantity and MSRP.
Dashboard Creation in Tableau
After data cleaning, I imported the dataset into Tableau to design a dashboard that visualizes important metrics:

<img width="1440" alt="Screenshot 2024-11-18 at 3 27 24 PM" src="https://github.com/user-attachments/assets/88fa0b62-1e7b-4c6d-b3c2-2d5af1bf2e76">


Top Models by State and Fuel Type: Displays the highest-selling models and fuel types by state, helping manufacturers assess regional trends.
Battery Type and Range Analysis: Analyzes battery types and range by model and year, offering insights into energy efficiency and technology trends.
Revenue Potential by Model, Battery Type, and Year: Examines potential revenue across models and years, segmented by battery type and MSRP.
Location-Based Quantity and Revenue: Maps vehicle quantity and estimated revenue by state, providing a geographic view of demand.
Make vs. MSRP and Fuel Type Analysis: Visualizes MSRP by vehicle make, battery type, and fuel type, enabling cross-brand comparisons and energy insights.
Key Insights and Business Applications
The dashboard enables a vehicle manufacturer to:

Identify High-Demand Models and Fuel Types by Region: Recognize popular models and fuel preferences in specific states to target marketing and optimize inventory.
Enhance Energy-Efficiency Strategy: Understand the demand for electric or hybrid models by state and gauge interest in specific battery types and ranges.
Optimize Pricing Strategy: Evaluate how MSRP affects sales by model, region, and fuel type, guiding pricing adjustments to maximize profit.
Forecast Revenue and Target Marketing: Use state-level data on model demand, fuel type, and battery metrics to design targeted marketing campaigns or sales initiatives.
: Python scripts (or Jupyter Notebook) used for data cleaning and transformation.

<img width="1440" alt="Screenshot 2024-11-18 at 2 45 49 PM" src="https://github.com/user-attachments/assets/76733684-f114-47b5-aad7-25216630c91c">
Conclusion

This project demonstrates how a vehicle manufacturer can leverage data on vehicle make, fuel type, battery range, and location-based demand to make strategic decisions. 
The Tableau dashboard visualizes trends that help manufacturers drive revenue by adapting to market demand and energy trends.

