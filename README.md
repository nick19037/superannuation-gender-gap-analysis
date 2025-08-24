# superannuation-gender-gap-analysis
*Analysis of gendered superannuation balances over lifetime using ATO sample data*

# A Husband is Not a Retirement Plan: A Gender-Based Analysis of Australia's Retirement System  

This project evaluates structural inequalities in Australia’s retirement income system, focusing on how **gender, occupation, and partner status** interact to shape lifetime superannuation outcomes. It was originally completed as part of an ANU data evaluation assignment, where it received a High Distinction.  

---

## 📊 Project Overview  
Australia’s superannuation system, while formally gender-neutral, produces **unequal outcomes** for men and women. Women consistently retire with substantially lower balances due to:  
- The gender pay gap  
- Occupational segregation  
- Interrupted career patterns from caregiving  
- Policy settings tied to continuous, high-income employment  

This analysis uses the **ATO 2% Sample Unit Record File (2013–14)** to investigate disparities and highlight potential reforms.  

---

## 🔎 Research Question  
**How do gender, occupation, and partner status interact to affect lifetime superannuation accumulation under Australia’s retirement income system?**

---

## 🛠️ Methods & Data  
- **Dataset**: Australian Taxation Office 2% Sample Unit Record File of Individual Tax Returns (2013–14)  
- **Variables considered**: income, occupation, age, partner status, superannuation balances  
- **Techniques**:  
  - Descriptive statistics & visualisation (income, contributions, balances)  
  - Outlier trimming (top 1%)  
  - Linear regression:  
    ```
    SuperBalance ~ Gender + AgeGroup + PartnerStatus + Occupation
    ```  

📂 *Note*: The dataset is not included here due to licensing and size. For more information, see the ATO [Taxation Statistics](https://www.ato.gov.au/about-ato/research-and-statistics/in-detail/taxation-statistics/taxation-statistics-previous-editions/taxation-statistics-2013-14/statistics/individuals#Individualssamplefile).  

---

## 📈 Key Findings  
- **Income inequality drives superannuation gaps** — women earn less across all age groups, with mid-career divergence most pronounced.  
- **Contribution disparities** mirror income differences, compounding over time.  
- **Partner status matters**: partnered men accumulate the most; unpartnered women the least.  
- **Regression analysis** confirmed gender as a significant predictor even after controlling for occupation, age, and relationship status — women hold on average **$8,193 less** than men.  

---

## 🏛 Policy Implications  
- Current superannuation policy design reinforces inequality by linking contributions strictly to income.  
- Reforms like **Superannuation on Paid Parental Leave (from 2025)** are positive but insufficient.  
- Stronger interventions are needed, such as:  
  - Expanding LISTO and co-contribution schemes  
  - Caregiver credit schemes (trialled in European systems)  
  - Broader pay equity and childcare reforms  

---

## 📚 References  
Key sources include:  
- Workplace Gender Equality Agency (2023). *Australia’s gender pay gap statistics*.  
- Australian Treasury (2020). *Retirement Income Review*.  
- Basu & Drew (2009). *The case for gender-sensitive superannuation plan design*.  
- Stewart & Whiteford (2020). *Compulsory superannuation and the Australian retirement income system*.  

(See full reference list in the PDF report.)  

---

## 🏆 Acknowledgements  
- Developed as part of ANU coursework on **policy evaluation and data analysis**.  
- Received a **High Distinction** grade.
