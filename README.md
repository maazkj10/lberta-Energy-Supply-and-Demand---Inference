# Alberta Energy Supply and Demand Analysis

This project explores historical energy consumption data in Alberta, focusing on trends, seasonality, cyclical patterns, fuel sources for power generation, and sectoral market share changes. The analysis relies on descriptive statistics, visualizations, and modeling to uncover key insights.

---

## 1. Data Exploration and Preprocessing

### Data Sources
The dataset contains monthly energy consumption and power generation data for Alberta, with features including:
- **Date**: Year and month of energy consumption.
- **Monthly Consumption**: Energy usage for each month in GWh.
- **Fuel Types**: Breakdown of power generation by fuel type (e.g., natural gas, coal, renewables).
- **Sectoral Usage**: Market share of power consumption by different sectors (e.g., residential, industrial, commercial).

### Preprocessing Steps:
1. **Data Cleaning**:
   - Missing values were addressed.
   - Columns were renamed for clarity.
   - Data rounding was applied to improve readability.

2. **Feature Engineering**:
   - Extracted monthly and annual summaries.
   - Added columns for maximum, minimum, and average monthly consumption.
   - Calculated trends in fuel usage and sectoral market shares over time.

---

## 2. Exploratory Data Analysis (EDA)

### Key Findings:
- **Seasonality**: Monthly energy consumption exhibits cyclical patterns, with higher demand during winter months.
- **Annual Trends**: Total annual energy consumption has fluctuated across years, reflecting variations in economic activity and weather conditions.
- **Fuel Usage Trends**:
  - A visualization highlights the contributions of different fuel types (coal, natural gas, renewables) to total power generation.
  - A shift from coal to natural gas and renewables was observed over the years.
- **Sectoral Market Share**:
  - Industrial usage dominates overall consumption, with residential and commercial sectors showing stable but smaller shares.
  - Market share dynamics indicate a gradual increase in residential consumption.

### Statistical Summaries:
- **Monthly Max, Min, and Average**:
  - Maximum and minimum monthly consumption values were calculated for all months.
  - Average monthly consumption highlights consistent seasonal peaks and troughs.

### Visualizations:
- **Multi-Year Line Plot**:
  - A line plot depicts energy consumption trends for each year, showing clear seasonality and yearly variations.
- **Fuel Contribution Visualization**:
  - A detailed chart illustrates the production of power by different fuels, highlighting the transition from coal to natural gas and renewables.
- **Sectoral Share Trends**:
  - Line charts show how the market share of different sectors evolved over time.

---

## 3. Modeling

### Linear Regression for Total Power Generation:
- A linear regression model was used to analyze the trend in total power generation over time.
- **Inputs**: Year as the independent variable.
- **Outputs**: Total power generation as the dependent variable.

### Model Results:
- The model indicates a steady increase in total power generation over the years, reflecting growing energy demands.

---

## 4. Results and Insights

### Insights:
1. **Seasonal Patterns**:
   - Energy demand peaks during winter months (e.g., January and February) and drops during summer.
   - Cyclical patterns are consistent year-over-year.

2. **Fuel Dynamics**:
   - Natural gas and renewables are emerging as dominant sources of power generation.
   - Policy and infrastructure shifts have accelerated the transition away from coal.

3. **Sectoral Market Share**:
   - Industrial sectors remain the largest consumers of power, but residential usage is gradually increasing.
   - Commercial consumption shows consistent but slower growth.

### Operational Recommendations:
- **Fuel Transition Planning**:
  - Continue investments in renewable energy infrastructure.
  - Develop strategies to manage the decline of coal-based generation.

- **Sectoral Demand Management**:
  - Tailor energy efficiency programs to residential and industrial sectors.
  - Encourage demand-side management initiatives during peak seasons.

---

## 5. Conclusion
This analysis provides valuable insights into Alberta’s energy consumption patterns, power generation trends, and sectoral market dynamics. The findings emphasize the importance of understanding seasonality, fuel transitions, and evolving market shares to inform energy policy and operational planning. Future work could explore advanced forecasting methods and integrate real-time data for dynamic analysis.

---

Feel free to reach out for further assistance or collaboration opportunities!
