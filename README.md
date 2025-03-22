# 📊 Fintech Loan Risk Analysis 

## 📁 **Project Overview**  
- **Goal:** Identify key parameters that relate to potential defaulting behavior, enabling better decision-making in loan processing.  
- **Tools Used:** Power BI, DAX, SQL, Excel  
- **Dataset Source:** Loan data from a non-banking financial company (NBFC), providing insights into applicant behavior to mitigate financial risks.  

## 🔍 **Problem Statement**  
The objective is to identify the parameters that contribute to a potential defaulting behavior. By analyzing the applicant's financial history, credit behavior, and previous loan details, we aim to improve decision-making in processing loan applications.

---

## 📊 **About the Dataset**  
This dataset includes **7 CSV files** providing comprehensive details about loan applications, credit activity, and payment history.

### 📂 **Dataset Files & Descriptions**  
| Filename                   | Description                                                           |
|----------------------------|-----------------------------------------------------------------------|
| `application.csv`            | Recently approved loans                                               |
| `bureau.csv`                  | Applicant's loans taken from other banks                             |
| `previous_application.csv`   | Applicant's previous loans applied at the same bank                   |
| `bureau_balance.csv`         | Applicant's loan installment payment pattern                         |
| `credit_card_balance.csv`    | Applicant's credit card usage and bill payment details                |
| `installments_payments.csv`  | Applicant's previously approved loan's installment payment history   |
| `pos_cash_balance.csv`       | POS and cash balance details from previously approved loans           |
| `Columns_Description_full.xlsx` | Column descriptions of all datasets (for reference only)             |

---

## ❓ **Key Business Questions Addressed**  
This project aims to answer the following critical business questions:

### 📌 **Credit Card & Loan Analysis**
1. How many applicants already have credit cards issued by the same bank?  
2. How many applicants have taken loans previously, with credit information available in the bureau?  
3. How many applicants have applied for loans previously at the same bank?  

### 📌 **Loan Repayment Behavior**
4. How many current applicants made lesser payments for installments on their previous loans?  
5. What percentage of those who made lesser payments for previous loans also defaulted on the recently approved loan?  

### 📌 **Loan History & Default Patterns**
6. What is the maximum number of previously approved loans per applicant (including the recently applied loan)?  
7. How many applicants defaulted despite successfully completing a previously approved loan?  
8. Have the applicants who withdrew cash from credit cards defaulted?  

### 📌 **Active Loans & Default Risk**
9. Among the previously approved loans, how many users have 5 active loans?  
10. Among the defaulters, how many had more than 3 loans approved previously?  

---

## 📈 **Approach & Methodology**  
1. **Data Preparation:**  
   - Merged multiple datasets (`application.csv`, `previous_application.csv`, `bureau.csv`, etc.) to establish relationships.  
   - Cleaned and transformed data to handle missing values and inconsistencies.  

2. **Exploratory Data Analysis (EDA):**  
   - Conducted EDA to identify trends in applicant behavior, loan repayments, and credit card activity.  
   - Derived correlations between credit history and default behavior.  

3. **Dashboard & Report Creation:**  
   - Built an interactive Power BI dashboard addressing the given business questions.  
   - Utilized slicers, filters, and dynamic visuals to enable deeper analysis.  

---

## 📊 **Dashboard Features & Insights**  
- **Loan Overview:** Visualizes loan contract types, default rates, and applicant profiles.  
- **Credit History & Default Trends:** Provides insights into repayment behavior and previous credit records.  
- **Default Risk Patterns:** Highlights correlations between loan characteristics and default tendencies.  

---

## ⚡️ **Challenges Faced**
- Managing and merging multiple datasets with different data structures.  
- Establishing accurate relationships between applicant IDs across datasets.  
- Optimizing DAX measures to improve dashboard performance.  

---

## 🎯 **Conclusion & Recommendations**  
- **High-Risk Applicants:** Monitor high-risk applicant profiles with multiple active loans or poor repayment history.  
- **Financial Counseling:** Recommend financial counseling to applicants with high Loan-to-Income (LTI) ratios.  
- **Enhanced Screening:** Incorporate credit card usage data to improve creditworthiness evaluation.  

---

## 💾 **How to Run the Project**  
1. **Download the `.pbix` file:** Clone or download the repository.  
2. **Open the File in Power BI Desktop:** Load the `.pbix` file to explore the interactive dashboard.  
3. **Interact with Visuals:** Use slicers and filters to analyze applicant behavior and loan performance.  
