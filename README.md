
# Youth Employability in Africa: Data-Driven Insights into Employment Outcomes

## 1. Project Overview

Youth employability remains an important workforce-development challenge across Africa. This project uses data analytics and Power BI to examine employment outcomes among young people across selected African countries between **2019 and 2024**.

The analysis explores how **education, digital skills, training access, internet connectivity, gender, work experience, and skill gaps** are associated with employment outcomes, employability scores, and income.

The final Power BI dashboard transforms the dataset into an interactive analytical tool that enables users to explore youth employment patterns by country, region, year, employment status, and job type.

---

## 2. Analytical Problem

The project seeks to answer five key questions:

1. What is the overall employment situation among the young people represented in the dataset?
2. Which factors are associated with stronger employability outcomes?
3. How do education and digital skills relate to employment?
4. What are the major skill gaps among young people?
5. How do employment outcomes translate into income and job type?

## 3. Dataset

The dataset comprises 4,450 youth records from 10 African countries across three regions (East, West, and Southern Africa), covering 2019–2024. It captures key demographic, education, skills, digital access, training, employment, income, and employability indicators.

Key variables include: gender, age, education, vocational and digital skills, skill and employability scores, training and internet access, employment status, job type, income, skill gaps, and recommended interventions.

The dataset provides a multidimensional view of youth employability rather than focusing solely on employment status.

---

# 4. Power BI Dashboard

<img width="711" height="400" alt="Screenshot 2026-05-15 113111" src="https://github.com/user-attachments/assets/b0ba745e-9393-4970-861d-363300a8d7ba" />


# 5. Key Insight 1:Education Shows a Strong Employment Gradient

Education is one of the clearest differentiators in the dataset.

| Education Level     | Employment Rate |
| ------------------- | --------------: |
| No Formal Education |        **0.0%** |
| Primary             |       **43.0%** |
| Secondary           |       **91.2%** |
| Tertiary            |      **100.0%** |


Higher educational attainment is strongly associated with better employability outcomes in the dataset.


# 6. Key Insight 2:Digital Skills Are Closely Associated With Employability

Digital capability shows another strong pattern.

| Digital Skill Level | Employment Rate | Avg. Employability Score |
| ------------------- | --------------: | -----------------------: |
| No Digital Skills*  |        **0.0%** |                 **19.0** |
| Basic               |       **74.0%** |                 **53.5** |
| Intermediate        |       **88.8%** |                 **70.3** |
| Advanced            |      **100.0%** |                 **89.3** |


Youth with advanced digital skills recorded an average employability score of **89.3**, compared with **53.5** for those with basic digital skills.


# 7. Key Insight 3 :Training Access Is Associated With Better Employment Outcomes

| Training Access | Employment Rate | Avg. Employability Score |
| --------------- | --------------: | -----------------------: |
| No              |       **65.1%** |                 **45.3** |
| Yes             |       **83.2%** |                 **70.8** |

Access to training is strongly associated with improved employment outcomes and employability scores.
Training programs may therefore represent an important avenue for improving workforce readiness.

---

# 8. Key Insight 4: Internet Access Is Associated With Employment


| Internet Access | Employment Rate | Avg. Employability Score |
| --------------- | --------------: | -----------------------: |
| No              |       **60.9%** |                 **50.9** |
| Yes             |       **85.2%** |                 **70.0** |

The results suggest that **digital connectivity may play an important role in access to employment opportunities, skills development, and workforce participation.**

# 9. Key Insight 5:Gender Differences Exist in Employment Outcomes

The dataset contains:

* **2,373 male records**
* **2,077 female records**

Employment outcomes differ between the two groups.

| Gender | Employment Rate | Avg. Employability Score |
| ------ | --------------: | -----------------------: |
| Male   |       **81.3%** |                 **69.6** |
| Female |       **76.9%** |                 **60.5** |


The results indicate a gender gap in employability outcomes, highlighting the importance of examining whether differences in education, skills, training access, internet access, or other factors contribute to the observed disparity.

---

# 10. Key Insight 6 : Skill Gaps Remain a Major Employability Challenge


| Skill Gap            |   Records |     Share |
| -------------------- | --------: | --------: |
| Low Digital Skills   | **1,854** | **41.7%** |
| Minor / No Major Gap | **1,821** | **40.9%** |
| No Vocational Skill  |   **460** | **10.3%** |
| No Digital Skills    |   **175** |  **3.9%** |
| Low Education        |   **140** |  **3.1%** |


Digital-skills development should be a central component of youth employability interventions.

---

# 11. Key Insight 7: Formal Employment Is Associated With Higher Income


| Job Type | Average Monthly Income |
| -------- | ---------------------: |
| Formal   |        **KSh 272,748** |
| Informal |         **KSh 75,468** |

The employability challenge is not simply about getting young people into employment.
**The quality and type of employment also matter.**

---

# 12. Country Level Insights

| Country      | Employment Rate |
| ------------ | --------------: |
| Ghana        |      **100.0%** |
| Rwanda       |      **100.0%** |
| South Africa |      **100.0%** |
| Kenya        |       **84.6%** |
| Nigeria      |       **82.9%** |
| Tanzania     |       **76.4%** |
| Ethiopia     |       **59.7%** |
| Uganda       |       **57.1%** |
| Senegal      |        **0.0%** |
| Zambia       |        **0.0%** |

## Important data-quality observation

These extreme country-level results should be treated carefully.

For example, Ghana, Rwanda and South Africa have 100% employment in the dataset, while Senegal and Zambia have 0%. This may reflect the way the dataset was constructed or sampled rather than actual national employment rates.

Therefore, the dashboard presents these as **employment outcomes within the dataset**, not as official national unemployment statistics.

---

# 13. Employment Trend

Employment rates varied across the six years:

| Year | Employment Rate |
| ---- | --------------: |
| 2019 |       **87.9%** |
| 2020 |       **67.6%** |
| 2021 |       **73.7%** |
| 2022 |       **75.7%** |
| 2023 |       **85.7%** |
| 2024 |       **79.0%** |

The largest decline occurs between **2019 and 2020**, followed by a gradual recovery through 2023.

The employment rate subsequently declined to **79.0% in 2024**.

---

# 14. Analytical Relationship: Skills and Employability

The dataset shows a very strong positive relationship between:

**Skill Score → Employability Score**

The correlation between the two variables is approximately **0.99** in this dataset.

There is also a strong relationship between employability score and employment probability.

The results reinforce the central role of skills in the employability model used in this dataset.

---

# 15. Recommendations

### 1. Expand Digital Skills Development 

The largest identified skill gap is low digital capability.

Youth employment programs should prioritize practical digital-skills training aligned with workplace requirements.

### 2. Increase Access to Training 

Training access is associated with an employment rate of **83.2%**, compared with **65.1%** among youth without training access.

Programs should improve access to affordable, practical and employment-oriented training.

### 3. Improve Digital Connectivity 

Internet access is associated with significantly stronger employment outcomes.

Digital inclusion initiatives should combine connectivity with digital-literacy training and access to online employment opportunities.

### 4. Strengthen Education-to-Employment Pathways 

The substantial employment differences across education levels indicate the importance of connecting education with practical employability skills, internships, vocational training and industry exposure.

### 5. Focus on Employment Quality 

Because formal employment is associated with considerably higher income than informal employment, youth employment initiatives should focus not only on employment creation but also on **decent, sustainable and productive employment**.

### 6. Address Gender Differences 

The observed gender gap in employability and employment outcomes warrants further analysis to identify the underlying barriers affecting female youth.

### 7. Use Data to Target Interventions 

Organizations can use employability scores, skill gaps, education levels and employment outcomes to identify groups requiring targeted interventions rather than applying a one-size-fits-all approach.

---

# 18. Project Impact

The analysis demonstrates how a relatively complex youth-employability dataset can be transformed into an interactive decision-support tool.

Rather than simply reporting employment figures, the dashboard allows stakeholders to investigate **why employability outcomes differ across groups** and identify areas where interventions could have the greatest potential impact.

The findings particularly highlight the importance of:

**Education + Digital Skills + Training + Internet Access → Stronger Employability Outcomes**

These insights could support decision-making by youth employment programs, NGOs, policymakers, training institutions and workforce-development organizations.

---

# 19. Conclusion

The Youth Employability analysis reveals substantial differences in employment outcomes across education levels, digital skills, training access, internet connectivity, gender and countries.

The strongest patterns are associated with **education and skills development**. Youth with tertiary education, advanced digital skills, training access and internet access generally demonstrate stronger employability and employment outcomes.

At the same time, the analysis highlights that employment alone is not sufficient. The substantial income difference between formal and informal employment demonstrates the importance of improving the **quality and sustainability of employment opportunities**.

The Power BI dashboard provides an interactive way to explore these patterns and translate raw data into actionable insights for youth workforce development.

---

