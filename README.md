# Monthly Active User Growth Accounting

This project analyzes the Monthly Active User (MAU) growth over 14 months (every 4 weeks is a month). It focuses on key metrics like New Users, Resurrected Users, Churned Users, Quick Ratio, and Retention Rate to understand the dynamics of user base changes and the effectiveness of user engagement strategies.

## Key Metrics

1. **New Users**: 
   - Represents the count of users who are active for the first time.
   - Peaks in the 1st month at 3849 but declines over time, reaching a low of 776 in the 8th month, before showing a recovery.

2. **Resurrected Users**: 
   - Users who were inactive in the previous month but active in some previous weeks.
   - Consistently rise over the months, peaking at 1950 in the 12th month, indicating effective re-engagement strategies.

3. **Quick Ratio**: 
   - Calculated as `(New Users + Resurrected Users) / Churned Users`.
   - Highest in the 1st month (2.03), stabilizes around 1 in subsequent months, with dips below 1 in the 7th and 11th months, suggesting periods where churn outpaced growth.

4. **Retention Rate**: 
   - Measures the proportion of users retained each month.
   - Stable overall, peaking in the 10th month (0.84), reflecting successful user retention strategies.

## Insights

1. **Early Months (m1-m4)**:
   - Strong initial growth with a peak in new user acquisition.
   - High engagement and rising quick ratios indicate effective early strategies.
   - Gradual decline in new users but stability in resurrected users shows a potential focus on user re-engagement.

2. **Mid-Period (m5-m8)**:
   - Decline in new users continues, hitting a low in the 8th month.
   - Quick Ratio stabilizes around 1, indicating a balance between new growth and churn.
   - Resurrected users remain consistent, highlighting continued efforts to bring back past users.

3. **Later Months (m9-m14)**:
   - Recovery in new user numbers, with a noticeable rebound starting from the 9th month.
   - Continued focus on resurrected users with a peak in the 12th month.
   - Steady retention efforts, reflected in a stable and sometimes rising retention rate.

## Visualization Plan

- **Stacked Bar Chart**: 
  - To display New Users and Resurrected Users stacked on top of each other, with Churned Users shown as bars extending below the baseline.
  
- **Line Plot**:
  - To overlay line plots for Quick Ratio and Retention Rate to show trends over the months.

The combination of these visualizations will provide us with a comprehensive view of user growth dynamics and the effectiveness of user engagement strategies over time.

## Summary

- New Users show a strong start but decline mid-period, with a recovery in later months.
- Resurrected Users consistently rise, peaking in the 12th month.
- Quick Ratio is highest initially and stabilizes around 1, with dips indicating periods of higher churn.
- Retention Rate peaks in the 10th month, showing stable and effective retention strategies.

This analysis provides a detailed understanding of user acquisition, retention, and re-engagement strategies, guiding future growth and engagement efforts.
