# DSA210_term_project
# Menstrual Cycle and Step Count Analysis

## Description

This project explores the relationship between menstrual periods and daily step counts, aiming to understand how menstrual cycles may influence physical activity. By analyzing self-tracked data from the Clue Period Tracking App and the Apple Health App, the study evaluates potential patterns and correlations between these variables.
### Hypotheses
In this project, the relationship between menstrual periods and daily step counts is examined using the following hypotheses:

Null Hypothesis (H₀):
There is no correlation between menstrual periods and daily step counts. 

Alternative Hypothesis (H₁):
There is a negative correlation between menstrual periods and daily step counts.

## Motivation
My curiosity about this subject stems from personal observations of fluctuations in my physical activity levels during certain times of the month. These changes made me wonder whether they might align with specific phases of my menstrual cycle, particularly during menstruation. By combining data from a period tracking app and daily step counts, I aim to explore this relationship and uncover any patterns that may exist.

## Dataset

This project utilizes personal data collected from the following sources:
1. **Clue Period Tracking App**: Provides data on menstrual cycle dates, including the start and end of periods.
2. **Apple Health App**: Tracks daily step count data.

Both datasets are manually exported from the apps installed on my personal device. The data is anonymized and used exclusively for educational purposes in this term project.



## Data Cleaning and Preprocessing
To ensure accurate analysis, the following steps were taken:
### Feature Engineering:
* Transformed raw step count data into daily aggregated values using feature engineering techniques to ensure consistency and comparability across the dataset.
### Menstrual Cycle Data:
* Parsed and retained only the start and end dates of menstrual periods.
### Step Count Data:
* Filtered data to retain only the date and daily step count columns.
### Merging:
* Combined datasets by aligning dates to create a unified DataFrame.
* Removed incomplete or invalid records.

## Exploratory Data Analysis (EDA)
1. Daily Trends Over Time
* Plotted daily step counts to visualize fluctuations in activity levels.
* Highlighted menstrual and non-menstrual phases to identify differences in activity patterns.
2. Step Count Distribution
* Created histograms to compare step count distributions during menstrual and non-menstrual periods.
3. Comparative Analysis
* Conducted comparisons of average step counts between menstrual and non-menstrual periods.

## Hypothesis Testing
### Statistical Analysis
**Whitman U Test:** Conducted to compare step counts between menstrual and non-menstrual periods.
* Result: No statistically significant difference (p-value: 0.87), indicating there is no significant difference in step counts during menstrual period.
### Effect Size
**Rank-Biserial correlation:** Conducted to measure the magnitude of the effect.
* Result: Minimal effect size (0.03)

### Key Findings
* Overall Relationship:
   * The test results do not support the alternative hypothesis, as the p-value is too high to conclude a significant decrease in activity during menstrual periods.
   * The effect size analysis also indicates a minimal effect, reinforcing the lack of a meaningful correlation.
      
## Conclusion and Insights
**Conclusion:**
The null hypothesis cannot be rejected, as the Whitman U Test results indicate no significant difference in step counts during menstrual periods.

**Implications:**
   * Results suggest that menstrual cycles may not strongly influence activity levels, but further exploration with more variables could be beneficial.
   * Larger datasets and additional factors like mood, sleep, and weather should be considered in future studies.


## License

This project is for academic purposes only and should not be used as medical advice. Data is self-reported and limited to a single individual, which may not generalize to others.

## Acknowledgments

Thanks to the developers of the Clue Period Tracking App and Apple Health App for providing tools that make personal data tracking accessible and insightful.
