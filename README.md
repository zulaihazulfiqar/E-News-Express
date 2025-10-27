# E-News-Express
Analyzed user interaction with new vs. old landing pages using A/B testing to determine engagement and conversion rates, providing actionable recommendations for increasing subscribers.
# E-News Express | A/B Test Landing Page Analysis

## Project Overview
E-News Express, an online news portal, aimed to increase new subscribers by testing a redesigned landing page. The project involved analyzing user interactions to determine whether the new page improves engagement and conversion compared to the existing page.

## Objectives
- Evaluate if users spend more time on the new landing page than the old page.
- Determine whether the new page has a higher conversion rate.
- Analyze whether conversion depends on the preferred language of users.
- Investigate if time spent on the new page differs across language preferences.

## Data Description
The dataset includes 100 users randomly split into control (old page) and treatment (new page) groups:

| Column                  | Description |
|-------------------------|-------------|
| user_id                 | Unique identifier for each user |
| group                   | Control or Treatment group |
| landing_page            | Old or New landing page |
| time_spent_on_the_page  | Time (in minutes) spent on the page |
| converted               | Whether the user subscribed (yes/no) |
| language_preferred      | Language chosen by the user (English, French, Spanish) |

## Key Findings
- Users spend significantly more time on the new page than the old page (p < 0.05).
- Conversion rate is higher for the new page (p < 0.05).
- Conversion status is independent of preferred language (p > 0.05).
- Time spent on the new page does not significantly differ across languages (p > 0.05).

## Recommendations
- Implement the new landing page to increase engagement and subscriber conversions.
- Focus on content layout and recommended material to maintain user attention.
- Language-specific variations do not require additional customization, as engagement is consistent across languages.

## Tools & Technologies
- Python (pandas, numpy, matplotlib, seaborn, scipy, statsmodels)
- Jupyter Notebook / Google Colab
- Statistical analysis: t-tests, z-tests, chi-square tests, ANOVA
