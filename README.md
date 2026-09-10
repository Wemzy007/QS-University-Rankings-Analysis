# QS University Rankings Analysis

## Project Overview

This project analyzes QS World University Rankings data to identify the factors most strongly associated with university ranking performance and changes over time.

The analysis examines academic reputation, employer reputation, employment outcomes, research performance, faculty resources, sustainability, international diversity, institutional size, institutional focus, and research intensity.

The project combines data preparation, exploratory data analysis, correlation analysis, comparative analysis, and interactive Power BI visualization to generate insights that can support strategic decision-making in higher education.

---

## Business Problem

Universities invest heavily in reputation, research, faculty development, sustainability, and internationalization.

The key question explored in this project is:

> Which factors contribute most strongly to university ranking performance?

The analysis was designed to help institutional strategy teams understand performance drivers, identify areas for improvement, and make data-informed decisions.

---

## Objectives

The project aims to:

- Analyze changes in university rankings.
- Examine the relationship between employer reputation and employment outcomes.
- Assess the relationship between research performance and ranking performance.
- Evaluate faculty and student-related indicators.
- Examine sustainability and international diversity.
- Compare universities based on institutional size.
- Analyze institutional focus and research intensity.
- Identify patterns that can inform strategic recommendations.

---

## Dataset

The dataset contains QS World University Rankings information covering:

- Ranking positions
- Academic reputation
- Employer reputation
- Employment outcomes
- Faculty/student indicators
- Research indicators
- Citations per faculty
- International research network
- International faculty
- International students
- Sustainability
- Institutional characteristics
- Institutional size
- Institutional focus
- Research intensity

The dataset contains 28 indicators used throughout the analysis.

---

## Data Preparation

The data preparation process included:

- Reviewing data quality
- Cleaning missing and inconsistent values
- Standardizing variables
- Preparing the dataset for analysis and visualization
- Identifying distributions, outliers, and structural patterns

---

## Methodology

The analysis used the following approaches:

### 1. Exploratory Data Analysis

Explored the distributions, patterns, and outliers across the available ranking indicators.

### 2. Correlation Analysis

Pearson correlation analysis was used to examine relationships between selected indicators and ranking performance.

Five Pearson correlations were calculated using DAX.

### 3. Comparative Analysis

Compared:

- Top ranking movers
- Regional patterns
- Reputation gaps
- Institutional size categories

### 4. Segmentation Analysis

Universities were segmented according to:

- Institutional size
- Institutional focus
- Research intensity

### 5. Dashboard Visualization

An interactive six-page Power BI dashboard was developed to communicate the analysis and findings.

---

## Key Findings

### Employer Reputation & Employment Outcomes

Employer reputation showed a strong positive relationship with employment outcomes.

**Pearson correlation: r = 0.644**

This indicates that universities with stronger employer reputation generally achieved better employment outcomes.

---

### Research Performance

Citations per Faculty showed one of the strongest relationships with ranking performance.

**Pearson correlation: r = -0.68**

This highlights the importance of research output within the ranking indicators analyzed.

---

### Faculty / Student Ratio

Faculty/student ratio showed a moderate relationship with ranking performance.

**Pearson correlation: r = -0.414**

This suggests that faculty resources and student support contribute to university performance, although the relationship was not as strong as some research-related indicators.

---

### International Diversity

International diversity showed very little relationship with ranking performance in the analysis.

**Pearson correlation: r = 0.04**

The analysis therefore suggests that international diversity alone was not strongly associated with ranking performance within this dataset.

---

### Sustainability

Sustainability showed a strong relationship with ranking performance.

**Pearson correlation: r = -0.74**

Within the indicators analyzed, sustainability demonstrated the strongest single-indicator relationship with ranking performance.

---

### Institutional Size

Large and Extra-Large universities performed better on several research-related metrics.

Smaller institutions, however, often performed better on faculty/student ratios.

The analysis also showed differences in research network performance across institutional size categories.

---

### Institutional Focus & Research Intensity

Universities classified as Fully Comprehensive with Very High Research Intensity achieved the strongest overall performance across key indicators analyzed.

---

## Recommendations

Based on the findings, the project recommends:

### 1. Increase Research Investment

Universities should strengthen research capacity and research output, particularly in areas linked to citations and international research networks.

### 2. Strengthen Employer Engagement

Universities should develop stronger relationships with employers and industry to improve employer reputation and employment outcomes.

### 3. Expand Sustainability Initiatives

Sustainability should remain a strategic priority given its strong relationship with ranking performance in the analyzed dataset.

---

## Power BI Dashboard

The project includes a six-page interactive Power BI dashboard covering:

- Rank Movement Analysis
- Employer Reputation vs Employment Outcomes
- Research Performance
- Faculty Resources
- Institution Size
- Sustainability & Diversity
- Institutional Focus & Research Intensity

The dashboard incorporates interactive visualizations, KPI cards, correlation analysis, and comparative views.

---

## Tools Used

- Microsoft Excel
- SQL
- Microsoft Power BI
- DAX
- Data Visualization
- Exploratory Data Analysis
- Correlation Analysis

---

## Skills Demonstrated

- Data Cleaning
- Data Preparation
- SQL Analysis
- Exploratory Data Analysis
- Correlation Analysis
- DAX
- Power BI Dashboard Development
- Data Visualization
- Comparative Analysis
- Data Storytelling
- Insight Generation
- Strategic Recommendations

---

## Project Structure

```text
QS-University-Rankings-Analysis
│
├── README.md
│
├── SQL
│   └── SQL analysis files
│
├── Excel
│   └── Excel analysis files
│
├── Power BI
│   └── Power BI dashboard
│
└── screenshots
    └── Dashboard screenshots
