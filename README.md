# MV Academy (MVA) Retention and Dropout Analysis

> For more of my projects and data journey, visit my [Portfolio](*).

## Table of Contents

- [Project Background](#project-background)  
- [Executive Summary](#executive-summary)  
- [Insights Deep-Dive](#insights-deep-dive)  
  - [Student Flow Between Grades](#student-flow-between-grades)  
  - [New Student Enrolment Trends](#new-student-enrolment-trends)  
  - [Cohort Retention Curve (Year-Over-Year Persistence)](#cohort-retention-curve-year-over-year-persistence)  
  - [Yearly Dropout Rate Trends](#yearly-dropout-rate-trends)  
  - [Dropout Composition by Grade](#dropout-composition-by-grade)  
  - [Student Distribution By Grade](#student-distribution-by-grade)  
  - [Loyalty and Long-Term Families](#loyalty-and-long-term-families)  
  - [Dropout Rate Within Each Grade](#dropout-rate-within-each-grade)  
- [Recommendations](#recommendations)  
- [Assumptions and Caveats](#assumptions-and-caveats)

## Project Background

MVA is an online PreK-12 academy which aims to provide affordable US-standardized curriculum to students of diverse backgrounds and ages. This analysis's goal is to understand student retention and dropout rates, which contributes directly to the academy's revenue. I reported this to the Founder and Head of the TA-Research Team. 

## Executive Summary

*MVA’s student lifecycle analysis from 2019–2025 highlights clear patterns in grade progression, retention, new enrolment, and long-term learner behavior. Early elementary grades (K–5) continue to attract the highest number of new students, while upper-grade levels (7–12) show noticeably higher dropout rates, especially in post-pandemic cohorts. Despite these challenges, recent cohorts (2023–2024) demonstrate meaningful improvements in first-year and Year 2–3 retention. Enrolment levels are stabilizing toward pre-pandemic norms, though overall retention past Year 4 remains low, reflecting a largely short-term learner population.

## Insights Deep-Dive

### Overall Enrollment and Yearly Dropout Rate Trends
- Total enrollment soared in 2020 mostly due to a surge of new students registering (increasing 140% from previous year). This is likely due to school closures on a large scale (from COVID19) and families shift to online learning. 
- However, this surge proved to be short-term as the new registrations drops significantly for the next 2 years 2021 & 2022 (each year witnessed an average -50% drop). This is also reflected in the dropout rate the same year (2020) reaching all-time high (66%) and staying at 51% and 47% the next 2 years. This shows that the customers gained from the surge is not long-term and may start leaving after traditional schools showing signs of recovery. 
- Enrolment continues to decline year over year (-23% to -7%), reaching its lowest point in 2024–2025 (1495 students). Even though throughout 2022-2024, enrollment shows positive signs of stabilizing after COVID19 adjustments, 2023-2024 school year shows concerning signs as total enrollment decreased -22%, due to both lower new registrations and lower students returning. 
- Current enrolment levels are returning toward pre-COVID levels (1495 vs 1239), signaling a normalization period but also the need for interventions to restore growth.

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/enrollment_trend.png?raw=true" width="800">
</p>
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/overall_trend_time.png?raw=true" width="800">
</p>

### Student Flow Between Grades

- Generally, most students progress to the next expected grade.  
- Grades 1–5 show smaller forward flows, indicating fewer students advancing compared to other segments.  
- Grades 7–8 show more stable and predictable grade movement.  
- PreK consistently shows the highest share of students leaving the school.
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/student_flow.png?raw=true" width="800">
</p>


### Student Distribution and Dropout by Grade

- Student population are distributed quite evenly between grades (each taking up 7%-13%)
- PreK, Grade 7, and Grade 8 consistently have the lowest enrolment (5–7%).  
- Grades 1–3 maintain the highest share (11–13%), while overall grade distribution remains fairly balanced at ~10% per grade.

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/enrollment_by_grades.png?raw=true" width="800">
</p>

### Dropout Rate Within Each Grade

- Grades 7–12 show high dropout levels (~50%), increasing by 10% from SY23-24 to SY24-25.  
- Grades 1–6 improved from 38% to 33% dropout last year.  
- Kindergarten (Grade K) shows variable behavior, ranging from 33% lows (2022–2023) to 52% highs (2025).

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/dropout_by_grades.png?raw=true" width="800">
</p>

### Cohort Retention Curve 

- Year-1 retention increased by 5–10 percentage points for the newest cohort compared to 2020–2022.  
- Cohort 2023 shows the strongest Year-2 to Year-3 persistence, indicating better mid-program stability.  
- Cohorts 2020–2021 show the weakest retention, likely influenced by COVID-19 disruptions and inconsistent learning environments.  
- Retention past Year 4 remains low across all cohorts, suggesting limited long-term engagement.
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/retetion_curve.png?raw=true" width="800">
</p>

### New Student Enrolment Trends

- Grades K–5 receive the highest number of new students, with PreK peaking in 2021 before declining steadily.  
- Grades K and 1 consistently attract 60–70 new students per year, roughly double other grades (max ~37).  
- New enrolment stabilized (10–30 per grade) after large swings from 2019–2021 due to COVID-19 impacts.
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/new_students.png?raw=true" width="800">
</p>

### Loyalty and Long-Term Families

- 86% of students stay for three years or less (1-year streak: 53%, 2-year: 22%, 3-year: 12%).  
- After three years, only 1–6% of students remain enrolled, indicating that most families treat MVA as a short-term or transitional option.

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/loyal_families.png?raw=true" width="800">
</p>

## Recommendations

### Strengthen Early-Grade Retention  
- Enhance support in Grades K–2 where new students are concentrated and early disengagement begins.  
- Provide structured onboarding for new families to increase first-year retention.

### Support Middle Grade Transitions  
- Focus academic and counseling support in Grades 4–6 to stabilize movement and reduce mid-grade exits.

### Address High School Dropouts  
- Review curriculum alignment in Grades 9–12.  
- Expand course offerings, career pathways, and test-prep support to retain older students.

### Grow and Stabilize Enrolment  
- Target marketing toward Grades K–3, where demand is strongest.  
- Reduce volatility by improving continuity programs for multi-year families.

### Build Long-Term Engagement  
- Introduce incentives, progress pathways, and extracurriculars to encourage students to stay past Year 3.

## Assumptions and Caveats

- COVID-19 significantly affected enrolment, retention, and new student spikes between 2019–2021.  
- Student IDs and grade placements are assumed to be consistent year-over-year for tracking cohorts.  
- PreK behaviour differs from K–12 patterns due to age-based transitions and family circumstances.  
- High dropout rates in Grades 9–12 may reflect external academic priorities rather than dissatisfaction with the program.  
- Long-term retention is measured by enrolment count rather than qualitative feedback or performance data.  
- Future analysis may improve accuracy by integrating attendance logs, academic performance, and engagement metrics.
