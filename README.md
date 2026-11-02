<div align="center">

#  ADE Manufacturing Group
## HR Data Analysis Dashboard

**Turning workforce data into fair, data-driven people decisions**

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-HR%20Analytics-1E90FF?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Diversity%20%26%20Pay%20Equity-8A2BE2?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-2EA44F?style=for-the-badge)

![Dashboard Preview](assets/dashboard.png.)

</div>

---

##  Table of Contents
1. [Background Story](#-background-story)
2. [Statement of the Problem](#-statement-of-the-problem)
3. [Project Objectives](#-project-objectives)
4. [Dashboard at a Glance](#-dashboard-at-a-glance)
5. [Key Findings](#-key-findings)
6. [How the Dashboard Solves the Problem](#-how-the-dashboard-solves-the-problem)
7. [Recommendations](#-recommendations)
8. [Limitations and Next Steps](#-limitations-and-next-steps)
9. [Tools and Skills Demonstrated](#-tools-and-skills-demonstrated)
10. [About the Author](#-about-the-author)

---

##  Background Story

**ADE Manufacturing Group** is a growing manufacturing company with **943 employees** spread across **three locations (Abuja, Kaduna and Lagos)** and **12 departments**, from Engineering and Sales to Legal, Support and Training.

As the company grew, so did the questions leadership kept asking the HR team:

- *"Is our workforce balanced and inclusive?"*
- *"Are we paying people fairly, regardless of gender?"*
- *"Does performance look different across groups, and is it being rewarded the same way?"*

The answers lived in spreadsheets: rows of employee records that were hard to scan, slow to summarise, and impossible to slice by location or department in real time. HR could answer these questions only after hours of manual work, and by the time the numbers were ready, the conversation had often moved on.

Leadership needed one place to **see the whole workforce, ask questions, and get answers instantly**. This dashboard was built to be that place.

---

##  Statement of the Problem

Without a consolidated view of its HR data, ADE Manufacturing Group faced four connected challenges:

| # | Challenge | Business Risk |
|---|-----------|---------------|
| 1 | **No quick view of workforce composition** by gender, department or location | Diversity gaps go unnoticed; hiring decisions lack direction |
| 2 | **Salary data not analysed by gender** | Potential pay inequity stays hidden and becomes a legal and morale risk |
| 3 | **Performance ratings not compared across groups** | Possible bias in appraisals; high performers may go unrecognised |
| 4 | **Manual, spreadsheet-based reporting** | Slow, error-prone, and not interactive enough for decision-makers |

> **Core problem:** HR and leadership had no fast, reliable, interactive way to understand workforce diversity, pay and performance together, and therefore could not confidently act on fairness and equity concerns.

---

##  Project Objectives

1. Provide a **single-page executive view** of the workforce (headcount, departments, average salary).
2. Show the **gender composition** of the company at a glance.
3. Compare **average salary across gender groups** to surface any pay gaps.
4. Compare **performance rating distribution by gender** to check for appraisal differences.
5. Let users **filter by Location and Department** to drill into any part of the business.

---

##  Dashboard at a Glance

### KPI Cards
| Metric | Value |
|--------|-------|
|  Total Employees | **943** |
|  Gender Categories | **3** (Male, Female, Prefer not to say) |
|  Departments | **12** |
|  Average Salary | **74K** |

### Visuals
| Visual | Purpose |
|--------|---------|
|  **Donut chart:** Count of Gender | Shows workforce composition |
|  **Column chart:** Average Salary by Gender | Reveals pay differences between groups |
|  **100% stacked bar:** Ratings by Gender | Compares performance rating distribution (Very Good to Very Poor) |
|  **Slicers:** Location and Department | Interactive filtering across all visuals |

---

##  Key Findings

### 1. The workforce is almost evenly split between men and women
| Gender | Employees | Share |
|--------|-----------|-------|
| Male | 464 | 49% |
| Female | 440 | 47% |
| Prefer not to say | 39 | 4% |

**Insight:** Gender representation is close to balanced overall, which is a healthy foundation. The 4% who chose not to disclose is a small but meaningful group, and the company should keep its data collection inclusive and respectful.

### 2. Women have the lowest average salary
| Gender | Average Salary |
|--------|----------------|
| Prefer not to say | 79K |
| Male | 75K |
| Female | 72K |

**Insight:** Women earn on average **3K less than men (about 4% lower)**, and **7K less than the "Prefer not to say" group (about 9% lower)**. Despite near-equal headcount, the pay is not equal. This is the most important flag on the dashboard and warrants a closer look at roles, grades and tenure.

### 3. Women are rated *better* than men, yet paid less
| Rating Group | Female | Male | Prefer not to say |
|--------------|--------|------|-------------------|
| **Very Good + Good** | **34%** | 27% | **36%** |
| Average | 47% | 49% | 49% |
| **Poor + Very Poor** | 19% | 23% | 16% |

**Insight:** A higher share of women (34%) are rated Good or Very Good than men (27%), and fewer women fall in the Poor or Very Poor bands (19% vs 23%). Yet women have the lowest average salary. **Pay does not appear to be tracking performance equally across genders.**

### 4. "Average" is the dominant rating for every group
Between **47% and 49%** of each gender group sits in the "Average" band. This suggests a possible **central-tendency bias** in appraisals, where managers default to the middle rating. It makes it harder to identify and reward true top performers.

### 5. The "Prefer not to say" group shows the strongest profile
This group has the **highest average salary (79K)**, the **highest Good/Very Good share (36%)** and the **lowest Poor share (8%)**. Note, however, that this is a small group of only 39 people, so conclusions should be treated with caution.

---

##  How the Dashboard Solves the Problem

| Problem | How the Dashboard Addresses It |
|---------|--------------------------------|
| No quick view of workforce composition | KPI cards and a donut chart summarise headcount and gender mix in seconds |
| Salary not analysed by gender | The salary-by-gender chart makes the 72K / 75K / 79K gap instantly visible |
| Ratings not compared across groups | The 100% stacked bar normalises each group so ratings can be compared fairly, regardless of group size |
| Slow, manual reporting | An interactive Power BI report replaces hours of spreadsheet work; Location and Department slicers let HR drill down on demand |

**The result:** leadership moves from *"we think we are fair"* to *"here is the evidence, and here is where to look."*

---

##  Recommendations

1. **Run a formal pay-equity audit.** Compare like-for-like roles, grades and tenure to confirm whether the female pay gap is explained by role mix or reflects genuine inequity.
2. **Review salary-progression and promotion decisions**, since women are rated as well as or better than men but earn less.
3. **Calibrate performance reviews.** With nearly half of all ratings sitting at "Average," introduce manager calibration sessions and clearer rating criteria.
4. **Drill down by department and location** using the slicers to find where gaps are largest, and target interventions there first.
5. **Keep inclusive data practices** for employees who prefer not to disclose gender, and track this group's outcomes responsibly.

---

##  Limitations and Next Steps

- Salary figures are **averages** and do not yet account for job level, tenure or department mix, so the gaps shown are **descriptive, not proof of causation**.
- The "Prefer not to say" group is small (n = 39), so its results are less statistically reliable.
- **Planned enhancements:**
  - Add tenure, age band and job-level analysis
  - Add attrition / turnover tracking
  - Add a department-level pay-gap view
  - Add tooltips and a hiring-trend page

---

##  Tools and Skills Demonstrated

| Category | Details |
|----------|---------|
| **Tool** | Microsoft Power BI Desktop |
| **Data Preparation** | Data cleaning and modelling in Power Query |
| **Analysis** | KPI design, demographic analysis, pay-equity and performance analysis |
| **Visualisation** | Donut, column and 100% stacked bar charts; slicers; custom layout and formatting |
| **Soft Skills** | Business storytelling, problem framing, translating data into recommendations |

---

##  About the Author

**Adebayo Idowu**
Data Analyst | Power BI | HR Analytics

 **Connect with me:**
[LinkedIn](linkedin.com/in/idowu-adebayo-157a1420b) · [Email](adebayoidowu08125@gmail.com) · [Portfolio](https://github.com/Idowu-Adebayo)

---

<div align="center">

 *If you found this project insightful, please give it a star!* 

</div>
