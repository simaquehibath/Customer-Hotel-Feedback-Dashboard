# Customer Feedback-Dashboard

## Problem Statement

This dashboard enables hotels to gain a deeper understanding of their customers. By analyzing feedback, it helps management evaluate customer satisfaction levels and identify areas for improvement. The dashboard highlights ratings for various hotel services and facilities, providing actionable insights to enhance the guest experience. Additionally, metrics such as check-in delays and service ratings are analyzed, enabling hotels to address inefficiencies effectively.

Currently, the data indicates that neutral/dissatisfied customers account for 57%, while satisfied customers make up 43%. This shows a pressing need for service improvements.


### Steps followed 

- Load Data into Power BI Desktop
	•	Imported the hotel customer feedback dataset (CSV format) into Power BI Desktop for analysis.
- Data Profiling in Power Query Editor
	•	Enabled Column Distribution, Column Quality, and Column Profile under the Data Preview section in the View tab.
	•	Changed the default profiling to Column Profiling Based on Entire Dataset to ensure all rows were included.
- Handling Missing Data
	•	Checked for missing or erroneous data across all columns. Identified null values in the “Check-in Delay” column.
	•	Excluded these null values from calculations since they accounted for less than 1% of the dataset.
- Theme Selection
	•	Applied a theme in the Report View under the View tab to ensure a visually appealing and consistent design.
- Adding Ratings Visuals
	•	Added a new visual for customer ratings using the visualization pane. This included ratings for:
	•	Room Cleanliness
	•	Front Desk Service
	•	Food and Beverage Quality
	•	Online Booking Experience
	•	Check-in and Check-out Convenience
	•	Amenities (e.g., Gym, Spa, Pool)
- Creating Visual Filters (Slicers)
	•	Added slicers for key fields such as:
	•	Room Type
	•	Customer Type
	•	Booking Channel
	•	Stay Duration
- Card Visuals for Key Metrics
	•	Added two card visuals to display:
	•	Average Check-in Delay (minutes)
	•	Average Check-out Delay (minutes)
	•	Used visual-level filters to exclude null values from these calculations.
- Bar Chart for Satisfaction Levels
	•	Created a bar chart to display the count of satisfied and neutral/dissatisfied customers.
	•	Added “Gender” as a legend to categorize customer satisfaction levels by gender.
- Handling Non-Applicable Values in Ratings
	• Ignored values marked as “0” in the ratings dataset, representing non-applicable parameters for specific customers.
- Adding Hotel Branding
	•	Inserted two text boxes in the report canvas to display the hotel’s name and tagline.
	•	Used the “Shapes” option to add a decorative rectangle and uploaded the hotel’s logo using the “Image” option.
- Publishing the Report
	•	After designing and refining the report, published it to Power BI Service for sharing and collaboration.

These steps resulted in a dynamic and interactive customer feedback dashboard, empowering the hotel to make data-driven decisions and enhance guest satisfaction.

       
# Snapshot of Date of Birth

![Screenshot 2024-12-31 102608](https://github.com/user-attachments/assets/e9728722-23f3-449d-8fae-ab960d4b7052)
 
 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard (Power BI Service)

![Customer Feedback Dashboard](https://github.com/user-attachments/assets/418bb6d5-bfb7-4677-89c6-fd136b800ed4)


# Insights

Total Number of Customers: 129,880
	•	Satisfied Customers (Male): 21.68%
	•	Satisfied Customers (Female): 21.76%
	•	Neutral/Unsatisfied Customers (Male): 27.58%
	•	Neutral/Unsatisfied Customers (Female): 28.97%
           
### [2] Average Ratings

    a) Room Cleanliness - 3.63/5
    b) Front Service - 3.31/5
    c) Food & Beverages - 3.29/5
    d) Online Booking Experience - 2.88/5
    e) Amenities(Gym, Spa, Pool) - 3.21/5
    f) Check-in/Check-out Convenience - 3.36/5
    
  
  ### [3] Average Delay 
  
      a) Average check-in Delay(minutes) - 15.09
      b) Average check-out Delay(minutes) - 14.71

 ### [4] Key Customer Demographics
 
 ### Class
 
Customer Type
	•	Returning Customers: 81.69%
	•	First-Time Customers: 18.31%
 
 ### Age Group
 
 0–25 Years: 21.69%
	•	25–50 Years: 52.44%
	•	50–75 Years: 25.57%
	•	75+ Years: 0.31%

### Room Type Preference
	•	Standard: 47.87%
	•	Deluxe: 44.89%
	•	Suite: 7.25%
         
### Customer Type

3.1) 18.31 % customers have customer type 'First time'.

3.2) 81.69 % customers have customer type 'returning'.
