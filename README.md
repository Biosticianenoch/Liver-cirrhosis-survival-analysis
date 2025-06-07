# 🧪 Liver Cirrhosis Survival Analysis

![Liver Cirrhosis](https://via.placeholder.com/1200x400.png?text=Liver+Cirrhosis+Survival+Analysis)

## 📖 Overview  

This project investigates the **survival probabilities** of patients diagnosed with **liver cirrhosis** using advanced statistical techniques:  
✅ **Kaplan-Meier survival curves**  
✅ **Cox proportional hazards regression**  
✅ **Survival probability estimation**  

The goal is to identify **key medical predictors**, compare treatment effects (**D-penicillamine vs. Placebo**), and offer recommendations for better **clinical decision-making**.  

---

## 🎯 Study Objectives  

🔍 **Estimate Survival Probability:** Understand survival trends over time.  
💊 **Compare Treatment Effects:** Determine effectiveness of **D-penicillamine** vs. **Placebo**.  
📊 **Identify Key Predictors:** Analyze bilirubin, albumin, ascites, edema, and disease stage.  
🔬 **Validate Cox Model Assumptions:** Ensure data fits proportional hazards assumptions.  
📌 **Offer Clinical Recommendations:** Use findings for better patient care.  

---

## 🛠 Technologies Used  

🔹 **R** — Data analysis & modeling  
🔹 **tidyverse** — Data wrangling & visualization  
🔹 **survival** — Survival analysis models  
🔹 **survminer** — Elegant visualizations  
🔹 **flexsurv** — Advanced survival modeling  

---

## 📊 Data Overview  

📌 The dataset includes **276 participants** and tracks their medical condition.  
🩸 **111 patients** died from liver cirrhosis during the study.  
🩺 **Key variables:**  
   - `N_Days` → Survival duration  
   - `Status` → Deceased (`D`) or Censored (`C`)  
   - `Drug` → **D-penicillamine** vs. **Placebo**  
   - `Age`, `Sex`, `Bilirubin`, `Albumin`, `Stage` → Clinical indicators  

---

## 🔬 Key Findings  

### **Kaplan-Meier Survival Analysis**  
📌 **Median survival time:**  
   - 💊 **D-penicillamine:** **3086 days**  
   - ⚪ **Placebo:** **3428 days**  
📉 **Log-rank test:** *No significant difference* _(p = 0.5)_.  

### **Cox Proportional Hazards Model**  
⚠️ **Significant predictors affecting survival:**  
✅ **Higher bilirubin →** **↑ Risk of mortality**  
✅ **Higher albumin →** **↓ Risk of mortality**  
✅ **Presence of edema →** **↑ Risk** (_Severe cases more vulnerable!_)  
✅ **Stage progression →** **↑ Risk**  
📌 **Treatment Effect:** No statistical difference _(p > 0.05)_ between **Placebo** & **D-penicillamine**.  

---

## 📉 Visualizations  

### 🔍 Kaplan-Meier Survival Curves  
![Kaplan-Meier Plot](https://via.placeholder.com/800x400.png?text=Kaplan-Meier+Survival+Curves)

### 📊 Cox Model Assumptions  
![Cox Model Assumptions](https://via.placeholder.com/800x400.png?text=Cox+Proportional+Hazards)

---

## 🔎 Recommendations  

💡 **Clinical Actions for Improved Survival**  

🔬 **Monitor Bilirubin & Albumin Levels Carefully**  
- 🩸 **Elevated bilirubin** signals higher risk → Require aggressive intervention.  
- 🍽 **Higher albumin** improves survival → Consider **nutritional therapy** support.  

⚠️ **Manage Edema Risks**  
- 🏥 **Severe edema** raises mortality risk → **Early treatment is critical!**  

📌 **Stage-Based Treatment Strategies**  
- Advanced stages significantly **increase risk** → **Customized interventions per stage needed.**  

💊 **Re-evaluate D-Penicillamine Usage**  
- 🏷 No significant survival benefit over Placebo → Consider alternative treatments.  

---

## 🚀 Getting Started  

### 🔗 **Prerequisites**  
Ensure you have **R** installed and the required libraries:  
```r
install.packages(c("survminer", "survival", "flexsurv", "tidyverse"))
