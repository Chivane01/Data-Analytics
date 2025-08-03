# 🧠 Open Banking Funnel Analysis & Optimization

This project simulates and analyzes a digital banking user journey — from sign-up to transaction — to understand drop-offs and model where improvements would drive the most conversion impact.

---

## 📘 Project Context

You're part of a data team at a digital banking platform. Many users sign up, but only a fraction complete a transaction. This project aims to:

- Simulate the user funnel (Sign-Up → KYC → Link → Transaction)
- Identify the biggest drop-off points
- Model "what-if" improvements to guide UX/product prioritization

---

## 🟦 Funnel Design

Simulated 1,000 users progressing through 4 funnel stages, each with a drop-off probability:

1. Sign-Up
2. KYC Completion
3. Account Linking
4. Transaction Completion

---

## 📊 Conversion & Drop-Off Summary

| Funnel Step             | Conversion Rate | Drop-Off Rate |
|-------------------------|------------------|----------------|
| Sign-Up → KYC           | 85.9%            | 14.10%         |
| KYC → Link              | 75.79%           | 24.21%         |
| Link → Transaction      | 57.45%           | 42.55%         |
| **Overall Funnel**      | **37.2%**        | —              |

---

## 🧪 Funnel Optimization (What-if Modeling)

Modeled a 10% improvement in drop-off at each stage to measure conversion gains:

- Final step improvement → +25 users
- Mid-stage (KYC → Link) → +12
- Early-stage (Sign-Up → KYC) → +7

### 💰 Simulated Revenue Uplift

Assuming ₹500 per user transaction:
- **+25 users recovered × ₹500 = ₹12,500 projected gain**

---

## 💡 Strategic Takeaways

> “Not all drop-offs are equal — later saves matter more.”

- The **Link → Transaction** step is the most impactful optimization point
- Early stage fixes help but deliver smaller ROI
- This framework gives a **conversion ROI-based prioritization strategy** to product teams

### 🛠️ Improvement Ideas:
- Simplify transaction UI and CTA design
- Add trust signals or secure-payment messaging
- Introduce progressive onboarding before linking
- Nudge or incentivize users who stall post-KYC

---

## 📌 Project Summary for Resume

- Simulated a 4-stage open banking funnel with 1,000 users  
- Identified and quantified key drop-off stages using Python  
- Modeled 10% improvement scenarios to prioritize UX fixes  
- Projected +25 transactions and ₹12.5K in revenue from bottom-funnel optimization  

---

## 🛠️ Tools Used

- Python
- Pandas, NumPy
- Matplotlib

## 📁 Folder Structure

```
Open_Banking_Funnel_Analysis/
├── open_banking_funnel.ipynb
├── README.md
├── requirements.txt
└── visuals/
```

