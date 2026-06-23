# AI-Evaluation-of-E-commerce-Chatbot-Responses-Using-Rubric-Based-Quality-Scoring
AI evaluation capstone project assessing chatbot response quality in a retail and e-commerce context. The project applies rubric-based scoring, error taxonomy classification, and targeted manual review to identify performance gaps and generate actionable insights for improving chatbot usefulness, user experience, and conversion outcomes.

# 🧠 AI Evaluation of E-commerce Chatbot Responses Using Rubric-Based Quality Scoring

## 📌 Overview
This project evaluates the quality of AI-generated chatbot responses in an e-commerce environment using a structured rubric-based scoring framework.

The evaluation focuses on identifying quality gaps in AI outputs by combining:
- quantitative scoring
- error taxonomy classification
- targeted manual review

---

## 🎯 Objectives
- Evaluate chatbot responses across key quality dimensions  
- Identify recurring failure patterns (e.g. generic responses, missing steps)  
- Assess performance across intents and product categories  
- Generate actionable insights to improve chatbot usefulness and business impact  

---

## 📊 Dataset
- **Bitext Retail & E-commerce Chatbot Dataset**
- Sample size: **390 rows (stratified by category)**
- Fields:
  - prompt
  - intent
  - category
  - ai_response  

---

## ⚙️ Methodology

### ✅ Evaluation Framework
Each response is scored using a **1–5 rubric** across:
- Accuracy  
- Relevance  
- Completeness  
- Consistency  
- Business Usefulness  
- Clarity  

---

### ✅ Error Taxonomy
Responses are tagged using:
- `overly_generic_response`
- `missing_key_step_or_omission`
- `too_verbose_or_inefficient`

---

### ✅ Evaluation Process
1. Data cleaning and standardisation  
2. Stratified sampling (390 rows)  
3. Semi-automated scoring  
4. Targeted manual review:
   - low-quality rows  
   - edge cases  
   - error clusters  
5. Aggregation and visualisation  

---

## 📈 Key Findings

- ✅ **Strong baseline performance** across accuracy and relevance  
- ⚠️ **Dominant issue:** overly generic responses  
- ⚠️ Responses lack **specificity and actionable detail**  
- ✅ Stable performance across intents and categories  
- ⚠️ Weak adaptation to different query types  

---

## 📊 Visual Outputs

The project includes the following visualisations:

- ✅ **Rubric Score Distribution**
- ✅ **Error Taxonomy Distribution**
- ✅ **Response Quality by Intent**
- ✅ **Response Quality by Category**
- ✅ **Edge Case Analysis**

---

## 💡 Key Insight

> The chatbot performs reliably but lacks optimisation.  
> The primary issue is not correctness, but insufficient specificity and contextual awareness.

---

## 🏢 Business Implications

- ✅ Reliable for baseline customer support  
- ⚠️ Generic responses may reduce:
  - user trust  
  - perceived intelligence  
  - satisfaction  
- ⚠️ Potential negative impact on e-commerce conversion  

---

## 🚀 Recommendations

- Improve response specificity  
- Reduce template-based outputs  
- Enhance completeness in transactional workflows  
- Introduce intent-aware response tuning  
- Balance clarity with conciseness  

---

## ⚠️ Challenges & Solutions

| Challenge | Solution |
|----------|---------|
| Small initial sample | Use 390 stratified sample |
| No errors detected initially | Improve error detection logic |
| Jupyter execution issues | Use structured pipeline + run-all |
| Auto-scoring limitations | Add targeted manual review |
| Weak initial charts | Ensure diverse dataset coverage |

---

## 🔧 What I Would Improve Next

- Extend evaluation to additional datasets  
- Add inter-rater agreement checks  
- Refine error taxonomy further  
- Build a scoring interface  
- Compare auto vs manual scoring accuracy  
- Add SEO/KPI-based evaluation extension  

---

## 🛠 Tools Used

- Python (pandas, numpy)  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- CSV exports  

---

## 📂 Project Structure
