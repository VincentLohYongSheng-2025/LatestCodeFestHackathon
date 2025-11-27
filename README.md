# Code Fest Hacakathon
**Team: When you stress don't stress**
- Norman Lee Weng Hong
- Daniel Goh Zhi Qian
- Vincent Loh Yong Sheng
- Ng Tze Fhung
- Ong Zheng Xi
# Creditsphere AI

## Main Goal
To build an LLM-based prototype that assesses credit risk based on **structured data (numeric)** and **unstructured data (text)** for individuals and businesses, in a way that is **transparent, explainable, and reliable**.

---

## Project Overview
**Creditsphere AI** is an AI-driven credit risk scoring system that evaluates both personal and business loan applicants using a combination of:

- Financial & numerical data  
- Natural-language reasoning from user-provided explanations  

The system provides **clear explanations** for each decision, ensuring full transparency and trustworthiness.

---

## Specific Issues Faced

### 1. Interpreting Text
Developing an algorithm that accurately analyzes context from unstructured text inputs.

### 2. Generating Appropriate Responses
Designing a mechanism that produces clear explnation and transparent decision based on the user’s financial and text reasoning.

### 3. Fusion of Numeric and Text Scoring Systems
Building an algorithm that finds the **right balance** between numerical metrics and text-based reasoning to produce a final, accurate risk score.

---

## Specifications

### **1. Numeric Risk Engine**
Processes quantitative financial data such as:
- Salary  
- Expenses  
- Debts  
- Cash flow  
- Revenue  
- Profit  
- Collateral  
- DSCR  
- Loan amount  

### **2. Text Reasoning Engine**
Analyzes unstructured text like applicant explanations or business plans for:
- Clarity  
- Credibility  
- Intent  
- Risk indicators  

### **3. Score Fusion Model**
Combines numeric and text-based results into a **single final risk rating** using weighted logic.

### **4. Explainability Module (XAI)**
Generates clear, transparent explanations for:
- Approvals  
- Rejections  
- Borderline decisions  

### **5. Real-Time UI (Streamlit)**
Provides:
- Interactive forms for personal and business loan applications  
- Instant scoring results and visual feedback

# 📘 How to Use the System

Follow these steps to get a credit risk evaluation:

## Step 1: Choose Loan Type
Select one of the following:
- **Personal Loan**
- **Business Loan**

## Step 2: Fill In Required Information

### For Personal Loans
Provide:
- Salary  
- Expenses  
- Debts  
- Guarantor information  
- Loan amount  
- Loan purpose  

### For Business Loans
Provide:
- Revenue  
- Profit  
- Expenses  
- Cash flow  
- Collateral  
- Number of employees  
- Loan purpose / business plan  

> Make sure all information is accurate for the best results.

## Step 3: Provide Your Written Reason
Write a short explanation covering:
- Why you need the loan  
- How you will use the money  
- How you plan to repay  

This helps the AI assess your clarity, responsibility, and intent.

## Step 4: Submit the Form
Click **Submit** to generate your **risk score**.

---

# 📊 Understanding the Output

## 1. Base Numeric Score (Financial Risk Score)

This score is calculated using:
- Income vs. expenses  
- Debts  
- Loan amount  
- Cash flow  
- Profit & revenue (for business loans)  
- Collateral  
- Other financial factors  

**Interpretation:**  
- **Lower score → lower risk → better**  
- **Higher score → higher risk → worse**

This score reflects the applicant’s financial strength based purely on numbers.

---

## 2. Intent Multiplier (Based on Text Score)

This multiplier comes from evaluating the applicant’s written explanation, checking for:
- Clarity  
- Responsibility  
- Confidence  
- Planning  
- Red flags  

**Effect on scoring:**
- **Good explanation → Lower multiplier (0.80 – 1.00)** → reduces risk  
- **Weak/risky explanation → Higher multiplier (1.10 – 1.50)** → increases risk  

> The text does **not** create its own risk score — it only adjusts the numeric score.

---

## 3. Final Risk Score

Formula:


This combines:
- Financial strength (numbers)  
- Loan intent (text)  

### How to interpret the final score
- 🟢 **Low Risk** → good applicant  
- 🟡 **Borderline** → needs review  
- 🔴 **High Risk** → likely reject  


---

### Demo video link
https://drive.google.com/file/d/1Xy4iOr7cAOnPxbzRGDkW_0jWg5YqFzR6/view?usp=sharing


### Slides link

Editable version
https://www.canva.com/design/DAG54Cv-bl4/4fvfE-uL3UnO7p-19_LFtw/edit?utm_content=DAG54Cv-bl4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

View only
https://www.canva.com/design/DAG54Cv-bl4/D46DPTzkFRjT8W_OwMaigg/view?utm_content=DAG54Cv-bl4&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h9f47bb2a89




