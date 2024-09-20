# Job-Displacement-Analysis
This repository contains the analysis of job displacement's impact on income using Two-Way Fixed Effects (TWFE) and Difference-in-Differences (DiD). It explores treatment effects over time, accounts for anticipation, and models both aggregate and dynamic effects to derive insights into labor market disruptions.

This repository contains a comprehensive analysis of the effects of job displacement on income, using two main methodologies: Two-Way Fixed Effects (TWFE) and Difference-in-Differences (DiD). The analysis is part of a capstone project focused on assessing the impact of labor market disruptions over time, particularly in relation to job displacement events.

The analysis explores the dynamics of treatment effects over time, accounts for anticipation effects, and evaluates both aggregate and group-specific treatment effects.

### Dataset
- **Job Displacement Data:** Contains income, demographic information, treatment variables (job displacement), and panel data of individuals across various time periods.

### Objectives
1. **Descriptive Analysis:** Summarize the dataset, providing insights into the average income, job displacement rates, and cohort characteristics.
2. **Dynamic Treatment Effects Analysis:** Use Difference-in-Differences (DiD) to estimate the dynamic treatment effects over multiple periods.
3. **Anticipation Effects:** Investigate the effects of anticipated job displacement on income using DiD, accounting for pre-displacement behavior.
4. **Model Comparison:** Compare the outcomes of Two-Way Fixed Effects (TWFE) and DiD models to assess the treatment effect on income.

### Repository Structure

- `Analysis.Rmd` - R Markdown file with complete analysis, including code for plotting and interpreting the event study results.
- `Detailed_Report.pdf` - A comprehensive PDF report detailing the methodology, analysis, and conclusions drawn from the job displacement data.

### Key Findings
1. **Treatment Effects (TWFE):** Job displacement is associated with a significant decline in income of approximately $6455.36, controlling for individual and time-fixed effects.
2. **Dynamic Treatment Effects (DiD):** Results reveal heterogeneous treatment effects across cohorts and time periods, with some periods experiencing sharper declines in income post-displacement.
3. **Anticipation Effects:** The analysis reveals significant pre-treatment declines in income, indicating that income drops even before job displacement occurs.
4. **Model Comparison:** DiD provides more robust and interpretable results for dynamic treatment effects than TWFE, especially when accounting for anticipation.

### Conclusion
This analysis provides detailed insights into the effects of job displacement on income using TWFE and DiD models. Significant negative treatment effects were identified, with income declining both before and after displacement events. The findings highlight the importance of accounting for anticipation effects and using dynamic models like DiD for policy evaluation.
The results can inform labor market policies, particularly those aimed at mitigating the effects of job displacement on income. Additional analysis could focus on industry-specific effects or more granular time periods to better understand how income recovery varies post-displacement.



### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/Job-Displacement-Analysis.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com

