# MV Academy (MVA) Retention and Dropout Analysis

## Table of Contents

- [Project Background](#project-background)  
- [Executive Summary](#executive-summary)  
- [Insights Deep-Dive](#insights-deep-dive)  
  - [Overall Enrollment and Yearly Dropout Rate Trend](#overall-enrollment-and-yearly-dropout-rate-trends)
  - [Student Flow Between Grades](#student-flow-between-grades)
  - [Student Distribution and Dropout by Grade](#student-distribution-and-dropout-by-grade)
  - [Dropout Rate Within Each Grade](#dropout-rate-within-each-grade)
  - [Cohort Retention Curve](#cohort-retention-curve)
  - [New Student Enrolment Trends](#new-student-enrolment-trends)
  - [Loyalty and Long-Term Families](#loyalty-and-long-term-families)

## Project Background

MVA is an online PreK-12 academy which aims to provide affordable US-standardized curriculum to students of diverse backgrounds and ages. This analysis's goal is to understand student retention and dropout rates, which contributes directly to the academy's revenue. I reported this to the Founder and Head of the TA-Research Team. 

## Executive Summary

- Enrollment stabilized after a short-lived COVID surge. Total enrollment spiked in 2020 due to a 140% increase in new students, then declined steadily (-23% to -7% YoY) back toward pre-COVID levels (1495 vs. 1239), indicating that most surge-driven growth was not sustainable.
- Grade-to-grade flows highlight critical weak points. Most students progress to the next grade, but PreK has extremely weak retention (progress:drop ~ 1:6), and upper grades (7–12) show dropout around 50%, with recent further drops, signalling pressure at both the entry-level and advanced-grades.
- Enrollment by grade is relatively balanced but core growth relies on early grades. Grades 1–3 hold the largest and most stable share of students (11–13%), while PreK, Grade 7, and Grade 8 remain cónistently small (5–7%), suggesting that protecting early primary years is key for retaining quantity.
- Cohort retention is concentrated in the first 2–3 years. 86% of students leave within three years (53% after one year). The 2023 cohort (more recent cohorts) performs better in Year-2 to Year-3, indicating improving onboarding and targeting such newer cohorts can improve the retention curve.
- As a reuslt, MVA behaves as a short- to mid-term option for most families. With very low retention beyond Year 4 and a majority of students staying three years or less, the current business model operates more like a 1–3 year transitional solution than a long-term schooling destination.
- Strategic focus should shift to durable retention. The main focuses are: stabilizing early-year and transition-grade retention (PreK->K and 6->7, 8->9), improving outcomes for secondary grades, and converting more 1-year families into 2–3 year loyal customers through cohort-specific and grade-specific interventions.

## Insights Deep-Dive

### Overall Enrollment and Yearly Dropout Rate Trends
- Total enrollment soared in 2020 mostly due to a surge of new students registering (increasing 140% from previous year). This is likely due to school closures on a large scale (from COVID19) and families shift to online learning. 
- However, this surge proved to be short-term as the new registrations drops significantly for the next 2 years 2021 & 2022 (each year witnessed an average -50% drop). This is also reflected in the dropout rate the same year (2020) reaching all-time high (66%) and staying at 51% and 47% the next 2 years. This shows that the customers gained from the surge is not long-term and may start leaving after traditional schools showing signs of recovery. 
- Enrolment continues to decline year over year (-23% to -7%), reaching its lowest point in 2024–2025 (1495 students). Even though throughout 2022-2024, enrollment shows positive signs of stabilizing after COVID19 adjustments, 2023-2024 school year shows concerning signs as total enrollment decreased -22%, due to both lower new registrations and lower students returning. 
- Current enrolment levels are returning toward pre-COVID levels (1495 vs 1239), signaling a stabilizing period but also the need for actions to restore growth.

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/enrollment_trend.png?raw=true" width="800">
</p>
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/overall_trend_time.png?raw=true" width="800">
</p>

#### Recommendation
- Rebalance strategy from pure acquisition toward onboarding and retention, especially for first-year families from “surge” cohorts.
- Build a normalization forecast (pre-COVID vs COVID vs post-COVID) to set realistic targets for enrollment, staffing, and revenue.
- Set early-warning retention KPIs (e.g., Year-1 dropout, return rate of new students) and track by cohort to catch issues before total enrollment dips.

### Student Flow Between Grades

- Generally, most students progress to the next expected grade.  
- All grades show smaller forward flows from 2022-2025, indicating fewer students advancing, with progress:drop ratios of ~17:10 in 2022 to ~12:10 in 2025, or for every 12 students progressing, there will be 10 dropping.  
- PreK shows the highest share of students leaving the school, having a progress:drop ratio of 1:6, meaning for every 7 students, only 1 student will return next year, while the remaining 6 will leave.
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/student_flow.png?raw=true" width="800">
</p>

### Recommendation
- Create grade-transition playbooks (communications, trial classes, parent sessions) for grades with weaker forward flows.
- Treat PreK as a special case: decide if it should be a one-year bridge or a pipeline into K, and design PreK→K offers accordingly.
- Develop a simple “transition risk” score to flag students likely to drop at key grade changes and target them with proactive outreach.

### Student Distribution and Dropout by Grade

- PreK, Grade 7, and Grade 8 consistently have the lowest enrolment (account for 5–7%) over the years.  
- Grades 1–3 maintain the highest share (11–13%), while overall grade distribution remains fairly balanced at ~10% per grade.

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/enrollment_by_grades.png?raw=true" width="800">
</p>

### Recommendation
- Protect Grades 1–3 as the core base, ensuring the strongest teaching quality, communication, and support there.
- Clarify the role of small classes (from PreK, 7, 8) - the institution may have to position them as niche offerings and optimize resources and staffing accordingly. Such patterns of low enrollment from these grades over the years might be a permanent characteristic, as they are at important transitioning points in students' life (transitioning to primary / highschool)
- Review capacity and profitability by grade to align staffing and class sizes with actual demand and margin.

### Cohort Retention Curve 

- Overall, over the years, the cohort retention curves become flatter and higher, showing positive signs of retention improvement. 
- Year-1 retention increased by 5–10 percentage points for the newest cohort compared to 2020–2022.  
- Cohort 2019 shows turbulent behavior (Cohort gained from COVID19), with their engagement plunged sugnificantly to near 0 only after Year 2.
- Cohort 2023 shows the strongest Year-2 to Year-3 persistence, indicating better mid-program stability.  
- Cohorts 2020–2021 show the weakest retention, likely influenced by COVID-19 disruptions and inconsistent learning environments.  
- Retention past Year 4 remains low across all cohorts, suggesting limited long-term engagement.
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/retetion_curve.png?raw=true" width="800">
</p>

### Recommendation
- Position MVA around 2–3 year learning journeys, since most families leave within three years; design programs and pricing to match.
- Analyze what made Cohort 2023 stronger (channels, grades, products, teachers) and use this to refine the “ideal” target profile.
- Use cohort/survival dashboards and trigger “save at Year-2” interventions (check-ins, offers, personalized plans) before the usual drop.

### Dropout Rate Within Each Grade

- Grades 7–12 show high dropout levels (~50%), increasing by 10% from SY23-24 to SY24-25.  
- Grades 1–6 improved from 38% to 33% dropout last year.  
- Kindergarten (Grade K) shows fluctuating behavior, ranging from 33% lows (2022–2023) to 52% highs (2025).

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/dropout_by_grades.png?raw=true" width="800">
</p>

### Recommendation
- Split retention strategies by stage: Early years (PreK–K), Primary (1–6), Secondary (7–12), with tailored objectives and interventions.
- For Grades 7–12, run a focused deep dive and feedback (reasons for leaving, competition, engagement data) and design exam-focused or flexible offerings that fit students' demands.
- Stabilize Kindergarten by standardizing onboarding and monitoring any curriculum/teacher changes, with grade-level dropout targets set and tracked.

### New Student Enrolment Trends

- Grades K–5 receive the highest number of new students (especially Grade K-3), with PreK peaking in 2021 before declining steadily.  
- Grades K and 1 consistently attract 60–70 new students per year, which nearly double other grades (max ~37).  
- New enrolment stabilized (10–30 per grade) after large swings from 2019–2021 due to COVID19 impacts.
<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/new_students.png?raw=true" width="800">
</p>

### Recommendation
- Treat K–1 as the main acquisition engine and ensure a best-in-class experience there, as these grades feed the pipeline.
- Build and track a PreK→K conversion funnel (conversion rate, reasons for non-conversion) and design bridging offers to improve it.
- Evaluate acquisition channels not just on volume, but on 1-year retention and LTV, and shift spend toward “stickier” sources.

### Loyalty and Long-Term Families

- 86% of students stay for three years or less (1-year streak: 53%, 2-year: 22%, 3-year: 12%).  
- After three years, only 1–6% of students remain enrolled, indicating that most families treat MVA as a short-term or transitional option.

<p align="center">
  <img src="https://github.com/tthvan/MVA-Retention-Analysis/blob/main/visualizations/loyal_families.png?raw=true" width="800">
</p>

### Recommendation
- Target the 1-year-only segment (53%) with structured end-of-Year-1 campaigns (progress reviews, next-year plans, small incentives to stay).
- Launch a simple loyalty program from Year 2 onward (recognition, perks, or added services) to push more families into 2–3 year streaks.
- Build an LTV-by-streak view and a small “loyalty health” dashboard to track the share of 1-, 2-, 3-, and 4+-year families over time.

## Assumptions and Caveats

- COVID19 significantly affected enrolment, retention, and new student spikes between 2019–2021.  
- Student IDs and grade placements are assumed to be consistent year-over-year for tracking cohorts.  
- PreK behaviour differs from K–12 patterns due to age-based transitions and family circumstances.  
- High dropout rates in Grades 9–12 may reflect external academic priorities rather than dissatisfaction with the program.  
- Long-term retention is measured by enrolment count rather than qualitative feedback or performance data.  
- Future analysis may improve accuracy by integrating attendance logs, academic performance, and engagement metrics.
