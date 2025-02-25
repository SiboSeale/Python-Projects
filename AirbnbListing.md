# Paris Airbnb Listings Analysis

## Project Overview
This project focuses on analyzing Airbnb listings in Paris, France. The analysis involves data profiling, quality assurance, data preparation for visualization, and data visualization to derive insights, including the potential impact of the 2015 regulations on new hosts and pricing trends.

## Objectives

### Objective 1: Profile & QA the Data
1. **Import and Open Data:** Load the `Listings.csv` file.
2. **Data Formatting:** Cast any date columns to a datetime format.
3. **Filtering:** Retain only rows where the city is `Paris` and keep the following columns:
   - `host_since`
   - `neighbourhood`
   - `city`
   - `accommodates`
   - `price`
4. **Quality Assurance:**
   - Check for missing values.
   - Calculate the minimum, maximum, and average for each numeric field.

### Objective 2: Prepare the Data for Visualization
1. **Neighborhood-Based Pricing:** Create a table `paris_listings_neighbourhood` grouping Paris listings by `neighbourhood` and calculating the mean price, sorted from low to high.
2. **Accommodation-Based Pricing in the Most Expensive Neighborhood:** Create a table `paris_listings_accommodations`, filter down to the most expensive neighborhood, group by `accommodates`, and calculate the mean price for each value, sorted from low to high.
3. **Host Activity Over Time:** Create a table `paris_listings_over_time` grouped by `host_since` year, calculating:
   - The average price.
   - The count of rows representing the number of new hosts.

### Objective 3: Visualize the Data and Summarize Findings
1. **Neighborhood Price Analysis:** Create a horizontal bar chart displaying the average price by neighborhood in Paris, including a title and updated axis labels.
2. **Accommodation Price Analysis in the Most Expensive Neighborhood:** Create a horizontal bar chart of the average price by `accommodates`, including a title and updated axis labels.
3. **Trends Over Time:** Create two line charts:
   - One showing the count of new hosts over time.
   - One showing the average price over time.
   - Adjust the y-axis limit to `0`, add a title, and update axis labels.
4. **Regulation Impact Analysis:** Analyze the findings to determine the effect of the 2015 regulations on new hosts and pricing trends.
5. **Bonus Visualization:** Create a dual-axis line chart to visualize both new hosts and average price trends over time.

## Requirements
- Python (>=3.7)
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (Optional for interactive analysis)

## How to Run the Project
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the script: `python analysis.py`
4. Open `visualizations.ipynb` for interactive visualization (if using Jupyter Notebook).

## Insights & Findings
- **Pricing Trends:** Neighborhoods with higher accommodation prices and affordability variations.
- **New Host Trends:** The impact of Airbnb regulations on the number of new hosts post-2015.
- **Correlation Between Price & Accommodations:** Understanding the price distribution based on the number of accommodations.

## Future Enhancements
- Extend analysis to other cities for comparative insights.
- Incorporate external datasets for deeper market trends.

## Author
Sibongile Seale

## Acknowledgements:
https://app.mavenanalytics.io/guided-projects/4fee7ee7-4c04-46e7-9f3e-99b987980842

