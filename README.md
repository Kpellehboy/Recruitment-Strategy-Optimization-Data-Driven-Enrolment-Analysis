# 🚀 Recruitment Strategy Optimization: Data-Driven Enrolment Analysis

This project leverages recruitment outreach and applicant data to provide **data-driven insights** for improving Excelerate’s enrolment outcomes. The analysis focuses on identifying key trends, bottlenecks, and high-impact factors to optimize recruitment strategies, ultimately increasing application rates and enhancing the quality and quantity of successful enrolments.

---

## 🎯 Business Objective

The primary goal is to **optimize recruitment strategies** to:
1.  **Increase application rates** and conversion.
2.  **Enhance candidate engagement** with outreach efforts.
3.  **Improve the quality and quantity** of successful enrolments.

---

## 📊 Data Sources

The analysis is based on three core datasets:

| Dataset | Description | Key Columns |
| :--- | :--- | :--- |
| **Applicant Data** | Applicant demographics and application status. | `App ID`, `Country`, `Phone Number` |
| **Outreach Data** | Records of recruitment call outcomes. | `Reference_ID`, `Recieved_At`, `Caller_Name`, `Outcome_1` |
| **Campaign Data** | Details about the campaigns and recruitment stages. | `ID`, `Name`, `Category` (`Pre Admission`/`Post Admission`) |

---

## 🛠️ Tools and Technologies

The following tools were used for data cleaning, analysis, and visualization:

* **Data Manipulation & Analysis:**
    * **Python** (Jupyter Notebooks)
    * **NumPy** & **Pandas** for efficient data processing.
    * **Microsoft Excel** for initial data inspection and cleaning steps.
* **Visualization & Dashboarding:**
    * **Power BI** for creating the interactive dashboard and key performance indicators (KPIs).

---

## 🧹 Data Preparation & Cleaning Summary

The project began with a critical data cleaning phase to ensure reliability:

* **Standardization:** Cleaned and standardized values across the three datasets (`Outreach`, `Campaign`, `Applicant`).
* **Phone Numbers:** Validated and standardized phone numbers in the `Applicant Data` to a consistent 10-digit format, marking invalid entries.
* **Missing Values:** Handled missing values according to the data dictionary guidelines (e.g., replacing with 'Missing' or 'Not Given').
* **Deduplication:** Removed duplicate records to ensure accurate counting.

---

## ✨ Key Insights and Conclusions

The analysis revealed several actionable insights guiding strategic adjustments:

### 1. Applicant Insights
* **Geographic Focus:** The majority of applicants are concentrated in a few key countries, primarily **Nigeria, Pakistan, and South Africa**.
* **Data Gaps:** A significant portion of applicant records are missing **Country data**, indicating a critical gap in data collection that limits targeted segmentation.

### 2. Outreach Effectiveness
* **Primary Bottleneck:** The most frequent outcome for outreach calls was **"Not connected,"** highlighting a major barrier to candidate engagement. This suggests issues with contact information quality, timing, or persistence.
* **Positive Conversion:** Despite connection challenges, a **notable share of candidates** showed positive progression, moving to actions like **“Will Submit docx”** or **“Completed application.”** This confirms that when contact is established, the outreach is effective.

### 3. Temporal Patterns
* **Activity Peaks:** Outreach activity displays **strong, short-term peaks** that align directly with specific campaign cycles.
* **Inconsistent Engagement:** These peaks are followed by **long lulls in activity**, suggesting an opportunity for **more consistent, sustained engagement** between major campaign pushes to maintain momentum and conversion rates.

---

## 💡 Recommended Actions

Based on the findings, we recommend the following strategic enhancements to improve enrolment:

1.  **Improve Data Quality:** **Mandate country data collection** in the application process. Address the "Missing" values to enable richer geographic segmentation.
2.  **Optimize Outreach Tactics:**
    * Investigate the causes of **"Not connected"** outcomes (e.g., timing, time zone adjustments, alternate contact methods).
    * Implement a **multi-channel follow-up strategy** (email, text, calls) to increase connection rates.
3.  **Enhance Engagement Consistency:** Distribute outreach efforts more evenly throughout the year, focusing on **sustained, year-round engagement** rather than solely relying on campaign peaks.
4.  **Prioritize High-Conversion Applicants:** Develop a segmentation model to **prioritize outreach to candidates** from high-volume countries (Nigeria, Pakistan, South Africa) and those who have already shown positive action (e.g., "Will Submit docx").

---

## 🖼️ Dashboard and Visualizations

The Power BI dashboard provides a **comprehensive visual overview** of recruitment health, tracking key metrics (KPIs) and conversion funnels. ()

* **Key Metrics:** Conversion rates by campaign, outreach outcome distribution, and applicant origin.
* **Functionality:** Enables data-driven adjustments by tracking the performance of new strategies in real-time.
<img width="683" height="476" alt="2025-11-11" src="https://github.com/user-attachments/assets/89a7d682-6fac-4b99-8df4-80abfb8ccfa8" />

---

## ⏭️ Next Steps

Future analysis could involve **linking the Outreach and Applicant data** on a unique identifier to calculate the conversion rates from **"connected"** calls to final enrolment, providing an even clearer picture of outreach ROI.
