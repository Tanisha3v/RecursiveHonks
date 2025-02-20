# Objective:
- Determine the busiest time windows at each venue and recommend optimal staffing levels to improve service efficiency.
- Examine how order type impacts the average bill size and tip amount.
- Build a model to forecast daily or weekly `sales_revenue_with_tax` at the venue level. Explore seasonality and venue attributes. Some venues start their “business day” early or late (`start_of_day_offset`). Explore whether this offset correlates with total daily sales, tips, or order volumes, potentially indicating different peak operational hours.
- Identify which waiters (`waiter_uuid`) have the highest average check sizes or tip percentages. This can be done primarily with bill-level data (who closed the bill, how much was paid, tip amount).
- Correlate daily sales or traffic with external weather data (e.g., temperature, precipitation) for each venue city. For instance, do rainy days yield more delivery orders? Do sunny days boost dine-in traffic?
- Examine how total daily sales vary during different holidays or days of the week. Also explore whether weekends generate higher net sales, tips, or gratuities compared to weekdays.
- Investigate how tipping behaviors vary across different geographic locations. Compare average tip amounts or tip percentages (`tip ÷ billed amount`) by city and country to see if there are notable regional differences. Look for correlations with venue attributes, order types, and other factors that might influence tipping culture.
- Evaluate how changes in local or national inflation rates (from publicly available data) correlate with sales revenue, average check size, or net revenue. Explore whether venues in regions with higher inflation rates see different spending patterns, such as smaller average bills or lower tip percentages.

# Given Items:
- **Bills.csv**: approximately 3 million rows  
- **Venom.csv**: approximately

# Tools:
- Jupyter Notebook / VS Code
- Python
- Pandas
- Numpy
- Scikit-learn
- Pytorch
- Matplotlib (`plt`)
- Seaborn
- SQLite3
- Microsoft Power BI
- Excel
- Azure Virtual Machine (subject to change)
- Generative AI (to generate dataset to train model)

# Breakdown:
1. **Load data into SQL**, merge two datasets into one using table functionality, perform basic data cleaning, and select relevant columns.  
2. **Clean the dataset** using Pandas and Numpy, then save the cleaned dataset as a CSV file.  
3. **Analyze dataset** using Pandas and Numpy, conduct explanatory data visualization.  
4. **Build models** using Scikit-learn and Pytorch, select an appropriate machine learning model, split dataset into 75% (training) and 25% (QA).  
5. **Conduct data visualization** using Microsoft Power BI.  

# Assigned Work:
- **Christopher Jiang**: Deadline management, Data analysis, Model building, Data visualization  
- **Yue Yang**: Model building, Data analysis, Debugging  
- **Tanisha Dhami**: Model building, Data visualization, Debugging  
- **Guangyu Yang**: Data cleaning, Data analysis  

*(Subject to change)*
