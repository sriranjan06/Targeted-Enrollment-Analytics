# Univariate-and-Multivariate-Data-Analysis-and-Visualization

## Project: Enhancing Enrollment at UVW College

## I. Objectives
The primary goal of this project is to boost enrollment at UVW College by analyzing U.S. Census Bureau data to identify key demographic and socioeconomic factors affecting income levels. By gaining insights into these factors, we aim to create targeted marketing profiles that will help attract more students from demographic groups with an income of $50,000 or less.

## II. Assumptions

- The dataset is clean and accurate, without significant missing values or erroneous data.
- The data structures used for analysis are suitable for the required operations.
- Individuals with an income of $50,000 or less represent a key demographic for UVW College.
- Certain socioeconomic factors such as education, age, and occupation strongly influence income levels.

## III. User Stories

### A. User Story 1: Education Level and Income
1. **Requirement:** Understand the distribution of education levels by income.
2. **Visualization:** A count plot showing the distribution of education levels, divided by income range.
3. **Attributes Used:** Education, Salary Range.
4. **Conclusion:** This visualization shows a clear distinction in education levels between income groups. Higher education is more prevalent among individuals with income above $50,000. This information is useful for targeting marketing efforts towards specific educational backgrounds.

### B. User Story 2: Age and Hours per Week by Income
1. **Requirement:** Determine if there’s a relationship between age, hours worked per week, and income.
2. **Visualization:** A scatter plot showing the distribution of age and hours worked per week, colored by income range.
3. **Attributes Used:** Age, Hours per Week, Salary Range.
4. **Conclusion:** This visualization indicates that higher incomes generally correspond to older individuals who work more hours. Understanding this relationship helps UVW College design marketing strategies that appeal to specific age groups.

### C. User Story 3: Correlation Matrix of Key Variables
1. **Requirement:** Examine the correlation between age, education, capital gain, hours per week, and income.
2. **Visualization:** A heatmap of the correlation matrix for these key variables.
3. **Attributes Used:** Age, Education Number, Capital Gain, Hours per Week, Salary-bin.
4. **Conclusion:** This correlation matrix reveals that education and age have a positive correlation with higher incomes. This insight guides UVW College in crafting messages that emphasize the value of education and work experience.

### D. User Story 4: Capital Gain by Income
1. **Requirement:** Analyze the distribution of capital gain across income groups.
2. **Visualization:** A box plot depicting capital gain for each income range.
3. **Attributes Used:** Capital Gain, Salary Range.
4. **Conclusion:** The box plot demonstrates a significant variance in capital gains among higher-income groups, indicating that they tend to have higher investment returns. UVW College can leverage this information to target individuals interested in courses focused on finance or investment.

### E. User Story 5: Native Country, Education, and Income
1. **Requirement:** Understand the relationship between native country, education, and income.
2. **Visualization:** A scatter plot depicting education and age, with hue by native country and columns for income range.
3. **Attributes Used:** Education Number, Age, Native Country, Salary Range.
4. **Conclusion:** This plot shows that certain native countries are more associated with specific income levels, indicating cultural or educational influences. This data can help UVW College tailor their marketing strategies to different demographic groups based on native country and education levels.

## IV. Visualizations Design Process
1. **Data Cleaning and Preparation:**
   - Handled missing values and renamed columns for clarity.
   - Created a salary-bin column to indicate income levels.
2. **Selection of Visualization Types:**
   - Chose appropriate plots for univariate and multivariate analysis.
   - Used count plots, scatter plots, heatmaps and box plots to capture a variety of data relationships.
3. **Visualization Design Principles:**
   - Ensured readability by choosing appropriate color schemes and typefaces.
   - Maintained clarity by using suitable axis labels, legends, and plot titles.
   - Prioritized information to clearly communicate insights to the marketing team.

## V. Conclusion
My analysis has successfully highlighted several critical socioeconomic factors, such as education, age, marital status, and native country, that influence income levels. By examining these factors through various data visualizations, we have derived actionable insights that can guide targeted marketing efforts. This project enhances our understanding of the demographic profiles most likely to benefit from educational opportunities at UVW College.


