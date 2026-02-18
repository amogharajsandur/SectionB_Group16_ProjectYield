# 🏦 Optimizing Term Deposit Marketing Campaigns
### A Strategic Data Analysis of 43,000+ Client Interactions

![Project Status](https://img.shields.io/badge/Status-Complete-success)
![Tools](https://img.shields.io/badge/Tools-Google_Sheets_%7C_Excel_%7C_SQL-blue)
![Analysis Type](https://img.shields.io/badge/Analysis-Descriptive_%26_Strategic-orange)

---

## 🔗 Live Dashboard & Data
**Access the full analysis and interactive dashboard here:**
https://docs.google.com/spreadsheets/d/1n5M-HqA6OUdS49zxsxrWao99QGIJi2H2CNEurIyX4M8/edit?gid=1345962654#gid=1345962654

---

## 📌 Executive Summary
**The Problem:** The bank's current telemarketing campaign suffers from inefficiency, with a **11.6% conversion rate** and high operational costs due to indiscriminate calling.  
**The Solution:** A data-driven segmentation strategy analyzing **43,354** client records to identify high-probability personas.  
**The Impact:** Recommended strategies (Solvency Filtering & Seasonal Shifting) are projected to:
* 🚀 Increase Conversion Rate to **>13.5%**.
* 💰 Generate **€1.1M** in additional annual revenue.
* 📉 Reduce operational call volume by **15%** (saving ~€70k/year).

🛠️ Tools & Methodology
Primary Tool: Google Sheets (Advanced)

Techniques Used:

Data Cleaning: Handling missing values (IFERROR, FILTER), sanitizing text (PROPER, TRIM), and duplicate removal.

Feature Engineering:

Lifecycle Status: Created logic to distinguish "New" vs. "Existing" customers.

Financial Health: Segmented users into "In Debt" vs. "In Credit" based on balance sheets.

Analysis: Pivot Tables, Correlation Matrices, and Descriptive Statistics.

Visualization: Interactive Dashboard with Slicers and Dynamic Charts.

📊 Key Insights & Findings
1. The "Solvency" Correlation
Customers with a Personal Loan are 3x less likely to subscribe to a term deposit.

Action: Exclude leads with loan = yes from cold-call lists immediately.

2. Seasonal Inefficiency
May is the highest volume month (31% of calls) but has the lowest efficiency (6% conversion). In contrast, October and September show conversion rates >15%.

Action: Shift 20% of the marketing budget from Q2 (May) to Q3/Q4 (Sep-Oct).

3. Demographic Opportunities
"The Golden Ratio": Students (<25) and Retirees (>60) convert at 25%+, yet make up less than 5% of the call volume.

"The Blue-Collar Trap": Blue-collar workers receive the most calls but have the lowest ROI.

4. Duration Thresholds
Calls exceeding 15 minutes (900s) have a diminishing return on investment and often indicate non-sales interactions (complaints).

Action: Implement a soft operational cap at 12 minutes to preserve agent availability.
