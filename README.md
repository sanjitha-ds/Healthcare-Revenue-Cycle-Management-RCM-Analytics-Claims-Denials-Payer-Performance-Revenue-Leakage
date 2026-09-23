# Healthcare Revenue Cycle Management (RCM) Analytics

## 📊 Project Overview

This project presents an end-to-end **Healthcare Revenue Cycle Management (RCM) analytics workflow** using **Microsoft Excel** to analyze claims, billing, denials, payer performance, unbilled procedures, and coding-related issues.

## 🎯 Project Objectives

The primary objectives of this project are to:

* Analyze overall claims and billing performance
* Measure key Revenue Cycle Management (RCM) KPIs
* Identify major denial root causes
* Analyze the financial impact of denials
* Evaluate payer-level reimbursement performance
* Calculate payer contract yield
* Identify potentially unbilled procedures
* Examine coding-related denial patterns
* Combine Excel-based business analysis with Python-based analytical workflows

---

## 🏥 RCM Analysis Framework

The project covers five major analytical areas:

### 1. RCM Performance Analysis

The performance analysis evaluates claims and billing activity over time and across insurance providers.

Key metrics include:

* Total claims
* Denied claims
* Total billed amount
* Total paid amount
* Denial rate
* Net Collection Rate (NCR)
* Payer-level performance

---

### 2. Denial Root Cause Analysis

The denial analysis examines denied claims to identify the major reasons contributing to claim denials.

The analysis focuses on:

* Denial reason frequency
* Percentage contribution of denial reasons
* Financial impact of denial reasons
* Denied amount by insurance provider
* Identification of major denial drivers

Denial patterns are evaluated from both a **volume perspective** and a **financial-impact perspective**.

This distinction helps identify whether a denial issue is primarily frequent, financially significant, or both.

---

### 3. Payer Performance Analysis

Payer performance is analyzed using claims data to understand differences in reimbursement and denial patterns across insurance providers.

Key measures include:

* Total paid claims
* Total billed amount
* Total paid amount
* Contract yield
* Denial patterns by payer

### Contract Yield

Contract yield is calculated as:

```text
Contract Yield (%) =
Total Paid Amount / Total Billed Amount × 100
```

The analysis provides a payer-level view of reimbursement performance and allows comparison of billed versus paid amounts.

---

### 4. Unbilled Procedure Analysis

The unbilled procedure analysis examines whether procedures recorded in the procedure dataset have a corresponding claim.

The workflow links:

```text
Procedures
     ↓
Encounter ID
     ↓
Claims
```

Procedures without a corresponding claim are identified as potentially unbilled procedures.

This analysis provides a framework for investigating **potential revenue leakage caused by missed or incomplete billing**.

---

### 5. Compliance & Coding Audit

The compliance and coding analysis examines claims, denials, diagnoses, and procedures to investigate coding-related denial patterns.

The analysis includes:

* Claim denial reasons
* Coding-related denial patterns
* Claims and denial data
* Diagnosis information
* Procedure information

This component connects RCM analytics with **coding quality and compliance monitoring**.

---

# 🛠️ Tools & Technologies

## Microsoft Excel

Excel was used for business-oriented RCM analysis, including:

* Data preparation
* Claims and billing analysis
* Formulas
* Pivot tables
* KPI calculations
* Payer analysis
* Denial analysis
* Reporting and visualization


---

# 🔄 Analytical Workflow

```text
                Claims & Billing Data
                         │
                         ▼
                Data Preparation
                         │
                         ▼
                RCM KPI Analysis
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
      Denials          Payers       Procedures
          │              │              │
          ▼              ▼              ▼
     Root Cause     Contract Yield   Unbilled
      Analysis       Analysis       Procedures
          │              │              │
          └──────────────┼──────────────┘
                         │
                         ▼
               Coding / Compliance
                         │
                         ▼
                  RCM Insights
```

---

# 📈 Key RCM KPIs

| KPI                     | Purpose                                                |
| ----------------------- | ------------------------------------------------------ |
| Total Claims            | Measures claim volume                                  |
| Total Billed Amount     | Measures total billed value                            |
| Total Paid Amount       | Measures collected/reimbursed amount                   |
| Denial Rate             | Measures proportion of claims denied                   |
| Net Collection Rate     | Measures paid amount relative to billed amount         |
| Contract Yield          | Measures payer reimbursement relative to billed amount |
| Denial Financial Impact | Measures monetary impact associated with denials       |
| Unbilled Procedures     | Identifies procedures without a corresponding claim    |

---

# 💡 Business Analysis Perspective

The project demonstrates how RCM data can be analyzed across multiple dimensions rather than focusing on a single KPI.

The analysis connects:

**Claims → Denials → Payers → Procedures → Coding**

This provides a broader view of factors that can influence reimbursement, claim performance, and potential revenue leakage.

Particular attention is given to distinguishing:

* High-volume denial reasons
* High-financial-impact denial reasons
* Payer reimbursement differences
* Potentially unbilled procedures
* Coding-related denial patterns

---

# 📊 Expected Outputs

The project produces analytical outputs related to:

* Monthly RCM performance
* Payer-level KPIs
* Denial reason analysis
* Denial financial impact
* Payer reimbursement performance
* Contract yield
* Potentially unbilled procedures
* Coding-related denial patterns
---

# 🚀 Skills Demonstrated

* Healthcare Revenue Cycle Management
* Claims Analytics
* Denial Management
* Payer Analytics
* Revenue Leakage Analysis
* Coding & Compliance Analysis
* Data Cleaning
* Data Analysis
* KPI Development
* Microsoft Excel
* Healthcare Data Analytics
* Business Analysis

---

## 👩‍💻 Project Focus

**Healthcare Analytics | Revenue Cycle Management | Claims & Billing | Data Analytics**

This project demonstrates the application of analytical tools to healthcare revenue-cycle data and translates claims-level analysis into meaningful operational insights.

