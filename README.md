# Productivity, Performance, and Well-Being: Investigating the Misalignment

## Overview

Productivity is increasingly viewed as the new currency of intellectual and social value. Popular books such as *Atomic Habits* by James Clear and *Getting Things Done* by David Allen and many other books encourage people to seek out and build the best version of themselves, offering methods to improve performance, optimize their lives, and achieve their goals.

However, productivity is often equated with long working hours and constant activity. Emerging research suggests that this interpretation may contribute to increased mental and physical health concerns, particularly among younger generations.

This project investigates whether high performance is truly associated with better well-being. More specifically, it explores whether indicators commonly used to evaluate productivity can reliably reflect underlying mental health and recovery needs.

---

## Why This Matters

This research contributes to the design of:

* Employee well-being programs
* Human-centered productivity tools
* Digital health applications
* Workplace analytics solutions

The project aligns with my interest in building technology that supports human well-being rather than maximizing activity at all costs.

---

## Research Question

### Original Research Question

> To what extent is there a systematic misalignment between perceived productivity and actual rest and well-being indicators?

### Adapted Research Question

Due to dataset limitations, the study was conducted within an academic setting using academic performance as a proxy for productivity and mental health indicators as proxies for well-being.

The research question was therefore reformulated as:

> To what extent can academic performance serve as a reliable indicator of well-being, and is there a discrepancy between academic performance and mental health indicators?

---

## Methodology

### Research Workflow

```text
Literature Review
        ↓
Research Protocol Design
        ↓
Dataset Selection
(Student Mental Health Dataset)
        ↓
Proxy Variable Construction
Academic Performance → Productivity
Mental Health Indicators → Well-Being
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Hypothesis Testing
(Chi-Square Analysis)
        ↓
Interpretation of Findings
        ↓
Product & Well-Being Implications
```

### Research Design

This study uses a quantitative research approach to examine relationships between academic performance and well-being indicators.

The original research objective focused on productivity, rest, and well-being. However, the available dataset did not directly capture perceived productivity or recovery variables.

To address this limitation, a proxy-based analytical framework was adopted:

| Concept of Interest | Proxy Used                    |
| ------------------- | ----------------------------- |
| Productivity        | Academic Performance (GPA)    |
| Well-Being          | Mental Health Indicators      |
| Recovery Status     | Mental Health Risk Indicators |

This approach enables an indirect assessment of potential misalignment between observable performance outcomes and underlying well-being.

### Hypotheses

**H1:** There is no positive relationship between academic performance and improved mental health outcomes among students.

**H2:** A significant proportion of high-achieving students exhibit symptoms of poor mental health (anxiety, depression, or panic attacks).

**H3:** There is no significant difference in mental health outcomes between high-achieving and lower-achieving students.

---

## Dataset

### Source

Student Mental Health Dataset (public dataset)

### Sample

* Approximately 101 student responses
* Only complete observations containing GPA and mental health variables were retained

### Variables

#### Independent Variable

**Academic Performance**

* GPA Range

#### Dependent Variables

Mental health indicators:

* Depression (Yes/No)
* Anxiety (Yes/No)
* Panic Attacks (Yes/No)

#### Derived Variables

To strengthen the analysis, additional variables were created:

1. **High Performer Indicator**

   * Identifies students within the highest GPA category

2. **Mental Health Risk Indicator**

   * Standardized measure combining mental health conditions into a single risk metric

### Limitations

GPA is widely used as a measure of academic performance and was used here as a proxy for productivity.

However, GPA does not directly capture an individual's perceived productivity, creating an important limitation that should be considered when interpreting the results.

---

## Key Findings

### Finding 1: Mental Health Challenges Exist Across All Performance Levels

Students reported mental health concerns regardless of academic achievement.

| Performance Group  | Mental Health Risk |
| ------------------ | ------------------ |
| High Performers    | 64.8%              |
| Average Performers | 75.0%              |
| Low Performers     | 50.0%*             |

*Interpretation should be cautious due to the very small sample size of low-performing students (n = 2).

This finding suggests that academic success alone does not protect against mental health challenges.

---

### Finding 2: Academic Performance Is Not a Reliable Indicator of Well-Being

The analysis revealed a misalignment rate of **60.8%**, indicating that for more than half of students, academic performance failed to reflect their underlying mental well-being.

This supports the hypothesis that visible performance outcomes may mask psychological struggles.

---

### Finding 3: High Achievement Does Not Predict Better Mental Health

A statistical analysis using the Chi-Square Test produced:

* α = 0.05
* p-value = 0.8293

Because the p-value is substantially greater than the significance threshold, the analysis found no statistically significant relationship between academic performance and mental health risk.

As a result, academic performance cannot be used as a reliable predictor of student well-being.

---

### Finding 4: High Performers May Still Be at Elevated Risk

High-performing students exhibited a mental health risk rate that was **14.8 percentage points higher** than low-performing students.

While further investigation with larger samples would be required, this result suggests that strong performance can coexist with significant psychological distress.

---

## Conclusion

The findings support all three hypotheses and indicate a substantial disconnect between observable performance and underlying well-being.

Academic achievement alone cannot be considered a reliable indicator of mental health.

More broadly, these results reinforce concerns that performance metrics may fail to capture hidden psychological costs, highlighting the importance of integrating well-being indicators into educational and workplace performance systems.

---

## Visualizations

### Mental Health Risk by Performance Group

![Mental Health Risk by Performance Group](assets/performance_vs_risk.png)

### Distribution of Mental Health Indicators

![Mental Health Indicators](assets/mental_health_distribution.png)

### Performance vs Well-Being Misalignment

![Misalignment Analysis](assets/misalignment_rate.png)

---

## Potential Product Applications

Based on these findings, future productivity and well-being platforms could:

* Detect potential signs of insufficient recovery
* Recommend personalized recovery periods based on user behavior
* Balance performance metrics with well-being indicators
* Identify hidden burnout risks
* Promote sustainable productivity rather than activity maximization

---

## Skills Demonstrated

### Research

* Literature Review
* Research Protocol Design
* Hypothesis Formulation
* Critical Evaluation of Research Limitations

### Data Analysis

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Statistical Testing (Chi-Square Analysis)
* Data Visualization

### Communication

* Research Reporting
* Evidence-Based Interpretation
* Translating Research Findings into Product Opportunities

---

## Future Work

Future research would benefit from collecting primary data that directly measures:

* Perceived productivity
* Sleep quality and duration
* Recovery habits
* Cognitive fatigue
* Subjective well-being

Such data would allow for a more direct evaluation of the relationship between productivity, recovery, and human well-being.
