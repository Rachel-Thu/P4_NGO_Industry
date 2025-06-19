# P4_NGO_Industry – Cost Optimization and Resource Efficiency Analysis

## Table of Contents

- [Executive Summary](#executive-summary)
- [Project Objective](#project-objective)
- [Methodology Overview](#methodology-overview)
- [Tools and Technologies](#tools-and-technologies)
- [Project Overview](#project-overview)
  - [Working Structured Table Preview](#working-structured-table-preview)
  - [Visual Report Preview](#visual-report-preview)
- [Reporting and Communication](#reporting-and-communication)
  - [Key Findings](#key-findings)
  - [Recommendations](#recommendations)
- [Repository Contents](#repository-contents)
- [How to Use](#how-to-use)

## Executive Summary

This project presents a comprehensive data analysis conducted for a non-governmental organization (NGO) with the objective of improving cost efficiency and optimizing the allocation of donor funds. The study focuses on identifying inefficiencies in program spending, evaluating the alignment between costs and outcomes, and improving the transparency and effectiveness of fund utilization.

## Project Objective  
The primary goal of this project is to support data-driven decision-making in NGO operations by:  
- Analyzing high program costs and their justification relative to outcomes  
- Identifying patterns of budget overuse or underuse across initiatives  
- Evaluating the efficiency of donor fund allocation and its impact on program success  
- Providing actionable insights to enhance financial planning, improve donor trust, and ensure sustainable operations

---

## Methodology Overview

The project employed a structured, insight-driven approach to analyze financial inefficiencies, improve cost control, and enhance the effective use of donor funds:

- **Understanding Business Needs:** Defined core financial issues, including high program costs, inconsistent budget performance, and inefficient allocation of donor contributions.
- **Data Accessing:** Imported and consolidated multiple datasets via Power Query, ensuring proper structure and validation through unique identifiers.
- **Data Quality Review:** Assess data integrity by identifying missing values, duplicates, errors & inconsistencies, and outliers that could affect analysis quality.
- **Data Cleaning & Transformation:** Applied Power Query to clean, standardize, and merge datasets, preparing the data for in-depth analysis and visualization.
- **Analysis & Modeling:** Explored patterns in spending and program performance to identify inefficiencies, budget discrepancies, and gaps in fund allocation.
- **Data Visualization:**   Designed a focused set of visuals to communicate financial insights clearly:
  - **Cost-Benefit Analysis (Bubble Chart):**  
    Plots Program_ID, Number of Beneficiaries, and Cost per Beneficiary
  - **Variance Analysis (Clustered Column Chart):**  
    Illustrates overspent and underspent programs by Program_ID
  - **Fund Efficiency Analysis (Bubble Chart):**  
    Highlights Program_ID, Number of Beneficiaries, and Fund per Beneficiary
- **Reporting & Communication:** Delivered results through a clear visual report to support stakeholder understanding and data-driven decision-making.

---

## Tools and Technologies

- **Microsoft Excel:**  Used for data analysis, visualization, and reporting  
- **Power Query:** Applied for data importing, cleaning, and transformation 

---

## Project Overview

This section presents a visual overview of key analytical components—from cleaned and structured data to final visual reports—demonstrating how raw financial and operational data was transformed into meaningful insights to support cost optimization and resource efficiency.

### Analyzing & Modelling Preview 



### Cost-Benefit Analysis Preview  


### Variance Analysis Preview


### Fund Efficiency Anslysis Preview 

---

## Reporting and Communication

### Key Findings

- **High Program Costs Without Proportional Benefits:** Programs such as **P024 (Child Safety and Shelter)** and **P034 (Disaster Preparedness Education)** recorded substantial budget overruns while serving a relatively low number of beneficiaries. This suggests inefficiencies in cost-effectiveness and impact delivery.

- **Underspent Programs with Unused Funds:** Initiatives like **P006 (Primary School Nutrition Program)** and **P012 (Disaster Relief Program)** were notably underspent, indicating potential misalignment between budget planning and program execution.

- **Donor Fund Inefficiency:** Projects supported by significant donor contributions, such as **P009 (Women’s Economic Empowerment)** and **P007 (Agricultural Skills Training)**, exhibited low fund utilization per beneficiary, raising concerns about the effective use of donor resources.

### Recommendations

- **Reassess Overspent Programs:** Examine budget overruns in programs such as **P007** and **P008 (Emergency Medical Support)** to uncover operational inefficiencies or procurement challenges, and strengthen financial oversight.

- **Improve Fund Allocation Efficiency:** Reevaluate how donor funds are distributed to ensure they are directed toward programs with proven impact. For example, **P026 (Disaster Risk Reduction Training)** demonstrates high fund efficiency and could serve as a model for allocation.

- **Enhance Monitoring of Program Spend:** Introduce regular monitoring mechanisms to identify deviations in spending patterns early. This is especially critical for programs like **P034**, where timely adjustments can prevent underperformance.

- **Prioritize High-Impact Programs:** Focus funding and resources on programs that generate strong outcomes per dollar spent—those with a high cost per beneficiary and low fund per beneficiary ratio—ensuring optimal value from limited resources.

### Next Actions

- **Spending Trend Analysis:** Perform time-series analysis to understand when overspending or underspending typically occurs, enabling earlier corrective action in the project lifecycle.

- **Budget-Beneficiary Correlation Analysis:** Assess whether higher budget allocations are directly associated with greater beneficiary reach to ensure alignment between funding and impact.

- **Cost-Savings Opportunities:** Identify consistently underspent programs and explore ways to reallocate surplus funds or reduce unnecessary expenditures, enhancing overall budget efficiency.

---

## Repository Contents

- Cleaned datasets prepared for analysis  
- Excel file (`P4_ProjectFile(May).xlsx`) with detailed analysis and visualizations  
- Data transformed using Power Query  
- Visual reports on cost-benefit, variance, and fund efficiency  
- Source data files in `P4_SourceDatasets/` folder 
