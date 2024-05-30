# Quantitative-Analysis-of-Soccer-Players-Wages

This project investigates the factors influencing soccer player wages using statistical analysis and data visualization techniques. The analysis focuses on the differences in wages based on contract length and various player attributes.

### Project Overview
#### Key Points:
**Wage Discrepancy Analysis:**

Investigated wage differences between players with long-term contracts (valid until 2026 or beyond) and those with shorter contracts.
Analyzed over 1,000 player wage records.
Conducted t-tests and variance analysis, revealing no significant wage difference (p-value > 0.05).

**Impact of Player Attributes:**

Explored the influence of age, international reputation, contract length, potential, and values on player wages.
Utilized Generalized Linear Models (GLM) to explain 65% of the variance in player wages (R² = 0.65).
Identified age, international reputation, and potential as significant predictors (p-value < 0.05).

**Data Handling and Visualization:**

Utilized a comprehensive dataset of 20,000+ records from the FIFA video game series.
Performed data cleaning and transformation on 10 key variables.
Created visualizations such as histograms, bar plots, scatter plots, and heatmaps to illustrate wage distributions and correlations, with strong correlations (r > 0.7) identified between player ratings and wages.
Dataset

The dataset used in this project is derived from the FIFA video game series, encompassing a wide array of player-specific information. Key features include:

1) Player Identification: Unique ID and name.
2) Physical Attributes: Age, height, and weight.
3) Nationality and Club Association: Nationality and club affiliation.
4) Player Performance Metrics: Overall rating and potential rating.
5) Position and Role: On-field positions and roles.
6) Wage Information: Weekly wage data.
7) Contract Details: Contract duration and release clauses.
8) Player Attributes: Performance metrics like dribbling, shooting, and defensive skills.


#### **Statistical Methods**

#### **Hypothesis 1:**

**Null Hypothesis (H0):** No difference in average wages between players with long-term and short-term contracts.
**Alternate Hypothesis (H1):** A significant difference in average wages exists between the two groups.

Methods used:

1) Shapiro-Wilk Test for normality
2) Variance Test
3) Welch’s Two Sample T-Test
4) Mann-Whitney U-Test


#### **Hypothesis 2:**

**Null Hypothesis (H0):** Age, international reputation, contract length, potential, and values do not affect player wages.
**Alternate Hypothesis (H1):** At least one of the variables significantly affects player wages.

Methods used:

1) Generalized Linear Models (GLMs)
2) Goodness of Fit (Null Deviance, Residual Deviance, AIC)
3) Model Fit Evaluation (R², p-values)

#### **Results**

**Wage Discrepancy Analysis:** No significant difference found in average wages between long-term and short-term contracts.
**Impact of Player Attributes:** Age, international reputation, and potential were significant predictors of wages, while contract length was not significant.

**Visualizations**

1) Histogram of Wage Distribution: Shows the distribution of player wages.
2) Bar Plot - Top 10 Clubs by Average Wage: Compares average wages across top clubs.
3) Scatter Plot - Wage vs Overall Rating: Illustrates the relationship between player ratings and wages.
4) Heatmap Correlation: Highlights correlations between various attributes.

#### **Contributions**

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

