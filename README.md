# Credit-Risk-Analysis-Loan-Default-Prediction-Dashboard



# Credit Risk Analysis & Loan Default Prediction Dashboard

## Project Overview
I developed an end-to-end **Credit Risk Analysis and Loan Default Prediction Dashboard** to help financial institutions better assess loan applications, minimize defaults, and optimize lending decisions. This project analyzes borrower profiles and loan characteristics to identify high-risk applicants and provide actionable insights for risk management.

**Live Dashboard**:

<img src="https://github.com/jsivamani12-wq/Credit-Risk-Analysis-Loan-Default-Prediction-Dashboard/blob/main/Screenshot%20(34).png" />

**My WorkBook**: [<a href="https://github.com/jsivamani12-wq/Credit-Risk-Analysis-Loan-Default-Prediction-Dashboard/blob/main/My%20Wark%20Book.pbix"> Credit-Risk-Analysis-Loan-Default-Prediction-Dashboard</a>]

## Business Problem
Financial companies face significant losses due to loan defaults. The goal was to build a robust analytics solution that:
- Identifies key risk factors in loan applications
- Segments borrowers by risk level
- Monitors portfolio performance
- Supports data-driven approval and pricing strategies

## Dataset
- **Source**: Kaggle (Lending Club Loan Data / Custom Credit Risk Dataset)
- **Size**: Large dataset with 32,500+ records and 25+ features
- **Key Columns**: loan_amount, interest_rate, grade, annual_income, debt_to_income_ratio, default_status, employment_length, purpose, etc.
- File: `new_credit_risk_dataset.csv`

## Tech Stack
- **Data Processing & Analysis**: Python (Pandas, NumPy, Matplotlib, Seaborn), SQL
- **Visualization & Dashboard**: Power BI (DAX measures, interactive visuals)
- **Tools**: Power Query for ETL, Jupyter Notebook for EDA

## Project Workflow
1. **Data Understanding & Cleaning**
   - Handled missing values, outliers, and data type issues
   - Feature engineering (e.g., risk_score, income brackets)
   - Exploratory Data Analysis (EDA)

2. **Analysis & Insights**
   - Calculated default rates by loan grade, purpose, and income level
   - Identified strong correlations between interest rate, DTI ratio, and default probability
   - Performed customer segmentation (High/Medium/Low Risk)

3. **Dashboard Development**
   - Interactive Power BI dashboard with multiple pages:
     - Executive Summary (KPIs)
     - Risk Analysis
     - Borrower Segmentation
     - Portfolio Trends

## Key Insights & Recommendations
- Loans with grade G and high DTI ratio have significantly higher default rates (XX%).
- Borrowers in certain employment lengths and loan purposes show lower risk.
- Recommended risk-based pricing and stricter approval criteria for high-risk segments to potentially reduce defaults by 15-25%.

## Screenshots

## ![Risk Segmentation]

<img src="https://github.com/jsivamani12-wq/Credit-Risk-Analysis-Loan-Default-Prediction-Dashboard/blob/main/Screenshot%20(37).png">

## ![Default Trends]

<img src="https://github.com/jsivamani12-wq/Credit-Risk-Analysis-Loan-Default-Prediction-Dashboard/blob/main/Screenshot%20(38).png">

*(Add your actual screenshot images in an /images folder)*

## How to Run the Project
1. Clone the repository: `git clone <your-repo-url>`
2. Open `Credit_Risk_Dashboard.pbix` in Power BI Desktop
3. Explore the interactive visuals and filters
4. Review `EDA_Notebook.ipynb` for detailed analysis
5. Run SQL queries in `queries.sql` for custom insights

## Future Enhancements
- Add machine learning model for default probability prediction
- Integrate real-time data pipeline
- Deploy dashboard on Power BI Service

## About Me
Finance graduate and aspiring Data Analyst passionate about using data to solve real-world business problems in the lending and risk management space.

---

**Made with ❤️ for learning and portfolio purposes**
