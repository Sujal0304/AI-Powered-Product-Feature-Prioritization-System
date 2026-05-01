# AI-Based Product Feature Prioritization

> Simulating how real product teams decide **what to build next** using data + ML

---

##  Overview  
This project builds a system to prioritize product features using:
- Business logic (**RICE + ROI**)  
- Machine Learning (**Decision Tree**)  

Goal: Replace subjective decisions with a **data-driven prioritization system**.

---

##  What I Built  

### 1. Feature Dataset  
Created a realistic dataset of product features like:
- AI Chatbot, Fraud Detection, Recommendation Engine, etc.

Each feature includes:
- Demand, Impact, Revenue, Risk  
- Engineering Cost, Effort, Time  
- Customer Reach, Confidence  

---

### 2. Scoring System (PM Logic)  
- **RICE Score** → (Reach × Impact × Confidence) / Effort  
- **ROI Score** → Revenue + Demand − Cost  
- Combined into a final **AI Priority Score**

 Features classified into:
- High / Medium / Low priority  

---

### 3. ML Model  
- Trained a **Decision Tree Classifier**  
- Input: product metrics  
- Output: predicted priority  

Goal: Learn how prioritization decisions are made.

---

### 4. Comparison System  
Compared:
- Traditional (formula-based) priority  
- ML-predicted priority  

---

##  Key Results  

-  **75% Agreement** between ML and traditional decisions  
-  Identified cases where ML disagrees → highlights potential decision gaps  
-  Showed trade-offs between:
  - Risk vs ROI  
  - Effort vs Value  

---

##  Visual Insights  
- Priority comparison (Traditional vs ML)  
- Risk vs ROI scatter  
- Effort vs ROI (decision conflicts)  
- Feature-level metric comparisons  

---

##  What This Shows  
- High revenue ≠ high priority (risk & effort matter)  
- ML can replicate and challenge product decisions  
- Prioritization can be **standardized and scaled**

---

##  Tech Stack  
Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn  

---

##  Author  
Sujal Swami
