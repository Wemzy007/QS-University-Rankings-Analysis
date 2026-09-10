# QS University Rankings Analysis

## Project Overview

This project analyzes the **QS World University Rankings 2025** to identify the factors most strongly associated with university ranking performance and changes over time.

The analysis combines data cleaning, exploratory analysis, correlation analysis, comparative analysis, institutional segmentation, and Power BI dashboard development to translate university ranking data into actionable insights.

---

## Business Problem

Universities invest heavily in research, reputation, faculty resources, internationalisation, sustainability, and student outcomes.

The key question addressed in this project is:

> **Which factors are most strongly associated with university ranking performance, and where can institutions focus their strategic efforts to improve?**

---

## Objectives

The analysis focused on:

- Examining university ranking movements between 2024 and 2025
- Assessing the relationship between employer reputation and employment outcomes
- Evaluating research performance and faculty-related indicators
- Investigating sustainability and international diversity
- Comparing institutions by size and institutional focus
- Assessing the interaction between institutional focus and research intensity
- Identifying strategic areas associated with stronger ranking performance

---

## Dataset

The dataset contains QS World University Rankings information covering:

- 2025 and 2024 ranking positions
- Academic reputation
- Employer reputation
- Employment outcomes
- Citations per faculty
- Faculty-student ratio
- International research network
- International faculty and student ratios
- Sustainability
- Institutional size
- Institutional focus
- Research intensity
- Other ranking indicators

The source dataset was obtained from Kaggle.

The final analytical dataset contained **1,502 universities** after data-quality processing.

---

## Data Preparation & Cleaning

Several data-quality issues were addressed before analysis:

- Converted banded ranking values such as `621–630` and `1401+` into usable numerical components
- Created ranking midpoint values for quantitative analysis
- Preserved missing Overall Score values and added a scoring-status flag
- Removed tie notation from ranking fields
- Corrected character encoding issues
- Decoded institutional size, focus, and research-intensity codes into readable categories
- Removed one corrupted record
- Standardised variables for analysis and visualization

A total of **902 Overall Score values were null** in the source data and were retained rather than arbitrarily imputed.

---

## Analytical Approach

The project used:

- Exploratory Data Analysis (EDA)
- Correlation analysis
- Comparative analysis
- Ranking movement analysis
- Institutional segmentation
- Size and focus analysis
- Research-intensity analysis
- Power BI dashboard visualization

The dataset contained **28 indicators**, and Pearson correlations were calculated for selected indicator-to-ranking relationships.

---

## Key Findings

### 1. Research Performance

**Citations per Faculty** showed a strong relationship with overall ranking:

> **Pearson correlation: r = -0.68**

This was the strongest relationship among the core academic indicators analysed, highlighting the importance of research impact in ranking performance.

---

### 2. Employer Reputation & Employment Outcomes

Employer Reputation showed a meaningful positive relationship with Employment Outcomes:

> **Pearson correlation: r = 0.644**

Universities with stronger employer reputations generally demonstrated stronger employment outcomes.

---

### 3. Faculty-Student Ratio

The Faculty-Student Ratio showed a moderate relationship with ranking:

> **Pearson correlation: r = -0.414**

This suggests that faculty resources and student support are relevant to ranking performance, although the relationship was weaker than that observed for research performance.

---

### 4. Sustainability

Sustainability demonstrated a strong relationship with overall ranking:

> **Pearson correlation: r = -0.742**

The analysis identifies sustainability as one of the strongest aligned indicators in the dataset.

---

### 5. International Diversity

International diversity showed very little relationship with overall ranking:

> **Pearson correlation: r = 0.036**

This indicates that international diversity, while strategically valuable for universities for many other reasons, showed negligible association with ranking position in this analysis.

---

### 6. Institutional Size

Large and Extra-Large universities generally performed better on research-related measures, while smaller institutions showed strengths in faculty-student ratios.

The analysis suggests that institutional scale can provide advantages in research capacity and international research networks.

---

### 7. Institutional Focus & Research Intensity

The strongest overall institutional configuration identified in the analysis was:

> **Fully Comprehensive + Very High Research Intensity**

The findings indicate that disciplinary breadth combined with high research intensity is strongly associated with stronger performance across key ranking indicators.

---

### 8. Ranking Movements

The elite tier of universities showed considerable stability between 2024 and 2025.

However, some institutions recorded substantial improvements, demonstrating that significant ranking movement is possible through targeted institutional development.

The largest improvement identified in the analysis was approximately:

> **+1,021 ranking positions**

---

## Strategic Recommendations

Based on the analysis, universities seeking to improve their global ranking position should consider:

### 1. Increase Research Investment

- Strengthen research infrastructure
- Improve faculty research capacity
- Increase research productivity and impact
- Expand international research collaborations
- Improve access to research funding

### 2. Strengthen Employer Engagement

- Build stronger relationships with employers
- Develop industry partnerships
- Improve graduate employability
- Strengthen alumni and employer networks

### 3. Prioritise Sustainability

- Integrate sustainability into institutional strategy
- Strengthen environmental and social initiatives
- Improve sustainability measurement and reporting

### 4. Develop Institutional Capacity

Institutions should consider their size, disciplinary focus, and research intensity when developing ranking-improvement strategies rather than applying a one-size-fits-all approach.

---

## Power BI Dashboard

The project includes a **six-page interactive Power BI dashboard** designed to communicate the analysis through:

- KPI cards
- Ranking movement analysis
- Correlation analysis
- Employer reputation analysis
- Research performance analysis
- Faculty resource analysis
- Institution size comparisons
- Sustainability and diversity analysis
- Institutional focus and research-intensity segmentation

Dashboard screenshots are available in the `screenshots` folder.

---

## Project Structure

```text
QS-University-Rankings-Analysis/
│
├── README.md
│
├── Data/
│   └── QS World University Rankings 2025 (Top global universities).csv
│
├── Power BI/
│   ├── Cleaned dataset for universities ranking.pbix
│   └── Dashboard analysis for universities ranking.pbix
│
├── Report/
│   └── Final Project Analysis Report.pdf
│
├── Presentation/
│   └── QS_University_Rankings_Presentation(1).pptx
│
└── screenshots/
    ├── Dashboard screenshots
    └── Analysis visuals
