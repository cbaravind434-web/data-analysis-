# Project Title: Zomato Dataset Analysis for Restaurant Insights

## 1. Project Overview
This project focuses on analyzing Zomato restaurant data using Pandas for data cleaning and analysis, and Matplotlib and Seaborn for data visualization. The objective is to understand restaurant performance, customer rating patterns, pricing trends, and service availability such as online delivery. The analysis explores how factors like price range, location, and delivery options influence customer ratings and overall restaurant popularity, providing insights that can support business decisions in the food service industry.

## 2. Tools Used
* **Pandas** - Data cleaning and manipulation
* **NumPy** - Numerical operations
* **Matplotlib** - Basic data visualization
* **Seaborn** - Advanced and statistical visualizations

## 3. Dataset
* **Source**: UCI Machine Learning Repository
* **Description**: The dataset includes restaurant-level data from Zomato such as location, cuisines, pricing, ratings, votes, and service features, allowing analysis of restaurant performance and customer behavior.
*  key columns:
 Restaurant Name – Name of the restaurant

* City / Location – City or area where the restaurant is located

* Cuisines – Types of cuisines offered

* Average Cost for Two – Estimated cost for two people

* Currency – Currency used for pricing

* Has Table Booking – Availability of table booking (Yes/No)

* Has Online Delivery – Availability of online delivery (Yes/No)

* Is Delivering Now – Current delivery status

* Price Range – Cost category of the restaurant

* Aggregate Rating – Overall customer rating

* Rating Color – Color representation of rating

* Rating Text – Textual rating description

* Votes – Number of customer votes

## 4. Steps Followed
1. Imported the Zomato restaurant dataset using Pandas.
2. Cleaned the data by:
* Handling missing values (e.g., filling missing cuisines or locations with appropriate placeholders).
* Converting numeric columns such as ratings, votes, and average cost for two into proper formats.
* Standardizing categorical values like price range, online delivery, and table booking indicators.
3. Performed exploratory data analysis (EDA) using Pandas to understand distributions and patterns.
4. Created visualizations using Matplotlib and Seaborn, such as:
* Bar charts showing restaurant distribution by country, city, and year.
* Charts comparing customer ratings across price categories and service types.
* Analysis of the relationship between ratings, votes, and pricing.
5. Interpreted the results to extract meaningful insights related to customer satisfaction, pricing trends, and service quality.

## 5. Key Insights
* Recent years show a noticeable increase in the number of restaurants listed, indicating platform growth.
* Budget and mid-range restaurants are more prevalent than premium and luxury restaurants.
* Restaurant distribution varies significantly by country and city, with higher concentration in urban and metropolitan areas.
* Restaurants offering online delivery and multiple services tend to receive better customer ratings.
* Customer ratings are influenced more by popularity (votes) and service quality than by pricing alone.

## 6. Visualizations
* Bar charts showing restaurant distribution by country, city, and year.
* Charts comparing customer ratings across price categories and service types.
* Analysis of the relationship between ratings, votes, and pricing.
## 7. Files Included
* `zomato_data.csv - Raw dataset`
* `DA_Main_Project_file.ipynb` - Pandas analysis and visualizations
* `README.md` - Project description and usage instructions

## 8. How to Use
1. Open `Main_Project.ipynb` using Jupyter Notebook or JupyterLab.
2. Run the notebook cells step by step to view data cleaning, analysis, and visualizations.
3. Modify the code to explore additional insights if needed.

## 9. Conclusion
This project demonstrates how Python libraries such as Pandas, Matplotlib, and Seaborn can be effectively used for real-world data analysis to uncover global dining trends. By examining market distribution and customer sentiment, the analysis reveals that while India remains the dominant hub, international success is driven by service reliability and menu variety rather than price alone. The insights gained from this study can help restaurant owners and stakeholders understand the current landscape of the food industry and optimize their service strategies for better customer satisfaction.

