## Overview
This project analyzes sales data from the fourth quarter of 2020 for an apparel retail business. The analysis includes data cleaning, exploratory data analysis, and visualization of sales patterns across different customer segments, states, and time periods.

## Data Description
- **Source**: AusApparalSales4thQrt2020.csv
- **Time Period**: October-December 2020
- **Key Variables**: Date, Time, State, Group, Unit, Sales

## Project Structure
1. **Data Wrangling**
   - Data cleaning and validation
   - Handling missing values
   - Date/time formatting

2. **Data Analysis**
   - Descriptive statistics
   - Group-wise sales analysis
   - Time-based sales patterns
   - State-wise performance

3. **Data Visualization**
   - Bar plots for sales distribution
   - Box plots for unit analysis
   - Distribution plots for sales patterns

## Key Findings
- Total sales are relatively evenly distributed across customer groups (Men, Women, Kids, Seniors)
- Men's segment shows slightly higher total sales at 85,750,000
- Morning sales show highest performance followed by afternoon and evening
- Sales data shows normal distribution with some right skewness

## Technologies Used
- Python 3.x
- Libraries:
  - pandas: Data manipulation
  - seaborn: Statistical visualization
  - matplotlib: Basic plotting

## Setup and Usage
1. Install required dependencies
\`\`\`python
import pandas as pd
import seaborn as sns
\`\`\`

2. Load and analyze data
\`\`\`python
df = pd.read_csv('AusApparalSales4thQrt2020.csv')
\`\`\`

3. Run analysis modules sequentially as per notebook structure

## Future Improvements
- Add predictive analytics
- Implement interactive visualizations
- Include customer segmentation analysis
- Add geographical visualization for state-wise analysis;
