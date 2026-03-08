# Wellspring-Registration_Study

An R-based statistical analysis evaluating the impact of Wellspring's March 2024 registration system update on member attendance, LGBTQ+ engagement, and registration trends.

## Project Overview
This project assesses whether the system update achieved its goals of streamlining processes and promoting engagement by comparing data from 2023 and 2024.

### Key Research Questions
1. **Attendance Rates:** Did the system change impact mean attendance rates?
2. **LGBTQ+ Engagement:** Did the update influence representation within the LGBTQ+ community?
3. **Trend Prediction:** Can registration trends be predicted using a linear model?

## Methodology
*   **Hypothesis Testing:** Conducted two-sample tests (10,000 resamples) for attendance and permutation methods (1,000 shuffles) for LGBTQ+ proportions.
*   **Linear Regression:** Built models to analyze registration counts over time to identify slopes and trends.
*   **Data Cleaning:** Processed datasets including "Member Background" and "Service Deliveries" for 4,829 members.

## Key Findings
*   **Significant Decline:** Attendance rates saw a statistically significant drop post-update ($p < 0.0001$).
*   **No Significant Engagement Change:** LGBTQ+ sign-ups showed no statistically significant change ($p = 0.861$).
*   **Persistent Trend:** Linear modeling revealed a negative slope in registrations both before and after the system change.

## Technologies Used
*   **RStudio**
*   **ggplot2** (Visualizations)
*   **Permutation/Resampling Methods**
