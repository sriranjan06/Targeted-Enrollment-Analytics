# Targeted Enrollment Analytics

## Project Overview
**Targeted Enrollment Analytics** is a data-driven project aimed at enhancing enrollment at UVW College by analyzing U.S. Census Bureau data. The primary objective is to identify key demographic and socioeconomic factors that influence income levels, focusing on individuals earning $50,000 or less. By leveraging these insights, the project aims to create targeted marketing profiles that effectively attract potential students.

## Objectives
- **Analyze**: Examine U.S. Census data to understand demographic and socioeconomic factors affecting income levels.
- **Visualize**: Use data visualizations to reveal patterns and correlations.
- **Target**: Develop actionable marketing strategies based on the insights to increase enrollment at UVW College.

## Assumptions
- The dataset is clean, accurate, and free from significant missing values or erroneous data.
- The data structures used for analysis are appropriate for the operations performed.
- Individuals with an income of $50,000 or less are a key demographic for UVW College.
- Socioeconomic factors such as education, age, and occupation significantly influence income levels.

## Data Source
The project uses the census dataset from the 1994 U.S. Census database cleaned by [Barry Becker and Ronny Kohavi](https://www.census.gov/data/datasets.html). This dataset includes attributes such as age, workclass, education, occupation, and income, which are crucial for the analysis.

## Data Preparation
1. **Data Cleaning**: Handled missing values and standardized column names.
2. **Feature Engineering**: Created a `salary-bin` column to categorize income levels.
3. **Exploratory Data Analysis (EDA)**: Conducted to understand the distribution and relationships between variables.

## User Stories & Visualizations
### User Story 1: Education Level and Income
- **Requirement**: Understand the distribution of education levels by income.
- **Visualization**: A count plot showing the distribution of education levels by income range.
- **Conclusion**: Higher education is more prevalent among individuals earning above $50,000.

### User Story 2: Age and Hours per Week by Income
- **Requirement**: Determine the relationship between age, hours worked per week, and income.
- **Visualization**: A scatter plot of age versus hours worked per week, colored by income range.
- **Conclusion**: Higher incomes generally correspond to older individuals who work more hours.

### User Story 3: Correlation Matrix of Key Variables
- **Requirement**: Examine the correlation between age, education, capital gain, hours per week, and income.
- **Visualization**: A heatmap showing the correlation matrix of these key variables.
- **Conclusion**: Education and age positively correlate with higher incomes.

### User Story 4: Capital Gain by Income
- **Requirement**: Analyze the distribution of capital gain across income groups.
- **Visualization**: A box plot of capital gain by income range.
- **Conclusion**: Significant variance in capital gains among higher-income groups indicates higher investment returns.

### User Story 5: Native Country, Education, and Income
- **Requirement**: Understand the relationship between native country, education, and income.
- **Visualization**: A scatter plot of education and age, with hue by native country and columns for income range.
- **Conclusion**: Certain native countries are associated with specific income levels, indicating cultural or educational influences.

## Technology Stack
- **Python**: Core programming language used for data manipulation and visualization.
- **Pandas**: Data analysis and manipulation.
- **Matplotlib & Seaborn**: Libraries used for creating visualizations.
- **Statsmodels**: Used for creating mosaic plots.

## How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sriranjan06/Targeted-Enrollment-Analytics.git
   ```
2. **Install Dependencies**:
   Ensure you have Python installed, then install the required packages:
   ```bash
   pip install pandas matplotlib seaborn statsmodels
   ```
3. **Run the Analysis**:
   Execute the Python script to generate the visualizations:
   ```bash
   python abc.ipynb
   ```

## Results & Insights
The analysis successfully identifies key socioeconomic factors influencing income levels. Insights gained may aid in crafting targeted marketing campaigns that appeal to specific demographic groups, ultimately enhancing enrollment.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
