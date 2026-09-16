# ASK A MANAGER SALARY SURVEY 2021 — CROSS-CURRENCY SALARY ANALYSIS

# TABLE OF CONTENTS

* BACKGROUND
* DATA STRUCTURE

  * DATA MODEL
  * DATA PREPARATION
* EXECUTIVE SUMMARY
* INSIGHTS DEEP DIVE
* RECOMMENDATIONS
* ASSUMPTIONS AND CAVEATS
* NEXT STEPS

## BACKGROUND

The Ask A Manager Salary Survey 2021 is a publicly available salary survey containing responses from employees across different professions, demographic groups, education levels, and experience backgrounds.

As the data analyst for this project, my objective for this analysis is to investigate how reported salary varies across key demographic, educational, and professional characteristics, identify patterns that are consistent across major currency groups, and translate these findings into meaningful insights from the survey data.

This analysis uses 28,498 survey responses across 18 columns. The dataset contains responses reported in 11 different currencies, with USD, CAD, GBP, and EUR representing the four most populated currency groups selected for the analysis.

Because salary amounts reported in different currencies are not directly comparable, each currency group was analyzed separately before comparing the resulting patterns across the four currencies.

My analysis and findings focus on the following key areas:

1. **Age:** Evaluating how reported salary varies across different age groups.

2. **Overall Professional Experience:** Examining the relationship between total years of professional experience and reported salary.

3. **Experience in the Field:** Assessing how salary varies with years of experience within the respondent's field.

4. **Education:** Examining differences in reported salary across education levels.

5. **Gender:** Comparing average reported salary across gender groups.

The analysis was conducted in Microsoft Excel using formulas, PivotTables, PivotCharts, and a dashboard to analyze and visualize the salary patterns across the selected currency groups.
 
## DATA STRUCTURE
**DATA MODEL**

The analysis was built from a single survey dataset containing 28,498 responses and 18 columns.

Unlike a relational database with multiple connected tables, this project uses a single-table Excel structure. The dataset contains the salary measure and the demographic, educational, and professional variables required for the analysis.

The key fields used in the analysis were:

Salary
Currency
Age
Gender
Education
Overall Professional Experience
Experience in the Field

The dataset was then organized into separate currency-based analysis worksheets for USD, CAD, GBP, and EUR, with PivotTables and PivotCharts used to examine the relationship between salary and the selected variables.

## DATA PREPARATION

The dataset was prepared in Microsoft Excel before the analysis was performed.

The preparation focused on making the selected variables suitable for comparison with reported salary and ensuring that the analysis could be conducted consistently across the four selected currency groups.

The main preparation steps included:

Separating the salary records by currency.
Selecting the four most represented currencies: USD, CAD, GBP, and EUR.
Grouping Age into defined age ranges.
Grouping Overall Professional Experience into experience ranges.
Grouping Experience in the Field into experience ranges.
Organizing Gender and Education categories.
Creating separate worksheets for each selected currency.
Using Excel formulas and PivotTables to calculate average reported salary across the selected variables.
Creating PivotCharts to visualize the results.

Variables with highly fragmented categories, particularly job title and occupation/job field, were excluded from the main analysis because meaningful and consistent grouping could not be established.

## EXECUTIVE SUMMARY
The analysis examined 28,498 salary survey responses to identify how reported salary varies across age, overall professional experience, experience in the field, education, and gender.

The analysis focused on the four most represented currencies — USD, CAD, GBP, and EUR — and evaluated each currency separately before comparing the resulting patterns.

Key Performance Indicators
28,498 — Total survey responses
18 — Dataset columns
4 — Currency groups analyzed
Key Findings
Experience in the field: The 21–30 years group recorded the highest average salary in USD, CAD, and EUR, while GBP peaked at 31–40 years.
Overall professional experience: Salary generally increased across higher experience levels, although the pattern was not completely linear.
Age: Older adult groups generally recorded higher average salaries than younger adult groups.
Education: Professional-degree holders recorded the highest average salary in USD, CAD, and GBP, while EUR showed a different pattern.
Gender: Men recorded the highest average reported salary across all four currency groups.

These findings highlight both consistent and varying salary patterns across the four currency groups, providing a basis for deeper analysis of the individual factors.

## INSIGHTS DEEP DIVE
1.**AGE & SALARY**

Age generally showed a positive association with average reported salary across the four currency groups.

In USD, average salary increased from $67,307 for respondents aged 18–24 to $118,885 for respondents aged 65+. The 55–64 age group recorded the highest average salary in both CAD (C$117,207) and GBP (£63,329). In EUR, the 55–64 group also recorded the highest average salary at €99,544.

The results indicate that older adult respondents generally reported higher average salaries, although the pattern was not consistently linear across every currency group.

2. **OVERALL PROFESSIONAL EXPERIENCE & SALARY**

Overall professional experience generally corresponded with higher reported salary, particularly across the early and middle experience categories.

In USD, average salary increased from $64,151 among respondents with 1 year or less of experience to $108,590 among those with 31–40 years. The 41+ category recorded an unusually high USD average of $201,220.

In GBP, the highest average salary was recorded among respondents with 21–30 years (£63,878), while EUR also reached its highest average at 21–30 years (€88,198). CAD showed a less consistent pattern across the experience groups.

Overall, the analysis suggests that greater professional experience is associated with higher reported salary, but the relationship is not perfectly linear across all currencies.

3. **EXPERIENCE IN THE FIELD & SALARY**

Experience in the field produced one of the clearest patterns in the analysis.

The 21–30 years group recorded the highest average salary in USD ($125,271), CAD (C$113,358), and EUR (€90,849). In GBP, the highest average was recorded among respondents with 31–40 years (£92,846).

Average salary generally increased from the lower experience categories toward the more experienced groups, although some later experience categories showed declines.

This indicates that substantial experience within a respondent's field is consistently associated with higher reported salary across the major currency groups.

4. **EDUCATION & SALARY**

Education showed a less consistent relationship with reported salary.

Professional-degree holders recorded the highest average salary in USD ($196,080), CAD (C$106,366), and GBP (£62,731).

EUR produced a different result, with the High School category recording the highest average salary at €80,301.

This variation indicates that education level did not produce the same salary pattern across all four currency groups.

5. **GENDER & SALARY**

Gender produced the most consistent pattern across the analysis.

Men recorded the highest average reported salary in all four currency groups:

Currency	Highest average reported salary
USD	$126,208
CAD	C$98,657
GBP	£62,868
EUR	€79,647

This consistent pattern makes gender one of the strongest cross-currency observations in the analysis. However, the results represent an association within the survey data and not causation.

## ASSUMPTIONS AND CAVEATS

**Currency**: The analysis focuses on USD, CAD, GBP, and EUR because they were the four most represented currency groups in the dataset. Salary amounts were analyzed separately by currency rather than directly compared across currencies.
Uneven currency representation: The number of responses varied substantially across the 11 currencies in the dataset. The less-represented currencies were not included in the main cross-currency analysis.

**Self-reported data**: Salary and other survey information were provided by respondents and could not be independently verified.
Association, not causation: The analysis identifies relationships between reported salary and the selected variables. It does not establish that age, gender, education, or experience directly causes salary differences.
Variable selection: The analysis focused on five variables: age, gender, education, overall professional experience, and experience in the field. Other available variables were outside the scope of the analysis.

**Highly fragmented categories** : Job titles and occupations/job fields contained many unique responses and were therefore excluded from the main analysis because consistent grouping was not practical.

**Average salary** : The analysis uses average salary, which can be influenced by unusually high or low reported salary values.
Small categories: Some categories contained relatively few responses. Their averages should therefore be interpreted with greater caution than categories with larger numbers of observations.

## RECOMMENDATIONS

Based on the findings from the salary analysis, the following recommendations are proposed:

**1. Strengthen experience-based salary benchmarking**

Organizations should consider overall professional experience and experience within the field when reviewing salary structures. The analysis shows that respondents with substantial experience generally reported higher average salaries, particularly within the 21–30-year experience range.

**2. Review compensation differences across gender groups**

The consistent difference observed across all four currency groups highlights the importance of regular compensation reviews. Organizations can use structured salary analysis to identify and investigate differences in reported pay across demographic groups.

**3. Consider relevant field experience in compensation decisions**

Experience within a specific field showed a particularly strong association with reported salary. Compensation frameworks should therefore consider relevant field experience alongside overall professional experience.

**4. Evaluate education alongside other factors**

Education should not be treated as a standalone indicator of salary. The results varied across currencies, suggesting that experience, role, industry, and other professional characteristics should also be considered when evaluating compensation.

**5. Use data-driven salary benchmarking**

Salary survey data can support compensation benchmarking and help organizations understand broader salary patterns. However, decisions should be based on sufficiently representative data and should account for differences in roles, industries, experience levels, and other relevant characteristics.

## NEXT STEPS
Expand the analysis to include the other currencies in the dataset where sufficient response volumes are available.
Investigate additional variables from the survey that may provide further context around reported salary differences.
Explore job titles and occupations by developing meaningful categories that allow for more structured comparison.
Apply additional statistical analysis to examine the strength of the relationships identified in this project.
Extend the dashboard with additional interactive views to allow users to explore salary patterns across different respondent characteristics.
