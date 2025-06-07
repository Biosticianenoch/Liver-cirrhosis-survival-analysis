
# 🧪 **Liver Cirrhosis Survival Analysis**

![Liver Cirrhosis Banner](https://via.placeholder.com/1200x400.png?text=Liver+Cirrhosis+Survival+Analysis)

> 📊 *Uncovering key predictors of survival outcomes in liver cirrhosis patients using robust statistical tools.*

---

## 📖 Overview  

This project conducts a deep dive into the **survival rates of liver cirrhosis patients** using modern survival analysis techniques. It aims to uncover **crucial clinical indicators** and evaluate the treatment effects of **D-penicillamine** vs. **Placebo**.

**🔍 Key Techniques:**
- Kaplan-Meier Curves 📈
- Cox Proportional Hazards Regression ⚖️
- Survival Probability Estimation ⏳

> 💡 *Goal: Inform better clinical decisions and improve patient outcomes through data-driven insights.*

---

## 🎯 Objectives  

| 🧭 Goal | 🎯 Description |
|--------|----------------|
| ⏱ Estimate Survival | Track and visualize survival probability over time |
| 💊 Compare Treatments | Assess efficacy of **D-penicillamine** vs. **Placebo** |
| 🔍 Identify Predictors | Analyze variables like bilirubin, albumin, and disease stage |
| 📐 Validate Model | Ensure Cox model assumptions hold true |
| 🩺 Recommend Actions | Translate insights into actionable medical strategies |

---

## 🛠 Technologies & Tools  

```yaml
🧪 Language:       R
📦 Libraries:      
  - tidyverse:     Data wrangling & plotting
  - survival:      Core survival analysis
  - survminer:     Beautiful survival plots
  - flexsurv:      Advanced modeling
```

---

## 📂 Dataset Summary  

📊 **Sample Size:** 276 patients  
🧬 **Events Recorded:** 111 deaths  

### 🔑 Key Variables:
| Variable     | Description                             |
|--------------|-----------------------------------------|
| `N_Days`     | Duration of survival (in days)          |
| `Status`     | `D` (Deceased) or `C` (Censored)        |
| `Drug`       | Treatment: D-penicillamine or Placebo   |
| `Bilirubin`  | Liver function indicator                |
| `Albumin`    | Protein level in blood                  |
| `Edema`      | Presence of fluid retention             |
| `Stage`      | Cirrhosis progression stage             |

---

## 🔬 Key Findings  

### 📈 Kaplan-Meier Analysis  
| Treatment        | Median Survival |
|------------------|------------------|
| 💊 D-penicillamine | **3,086 days**   |
| ⚪ Placebo         | **3,428 days**   |

> 🧪 *No significant difference observed (p = 0.5)*

---

### ⚖️ Cox Proportional Hazards Model  

🧠 **Top Predictors of Mortality Risk:**

| Predictor        | Impact on Survival                  |
|------------------|--------------------------------------|
| 🔴 Bilirubin ↑   | **Increased risk**                   |
| 🟢 Albumin ↑     | **Reduced risk**                     |
| ⚠️ Edema         | **Significantly higher risk**        |
| 📉 Stage ↑       | **More advanced = worse prognosis**  |
| 💊 Drug          | *No significant difference (p > 0.05)* |

---

## 📊 Visualizations  

### 🔍 Kaplan-Meier Survival Curve  
![Kaplan-Meier Plot](https://via.placeholder.com/800x400.png?text=Kaplan-Meier+Survival+Curves)

---

### 🧪 Cox Model Diagnostics  
![Cox Model Assumptions](https://via.placeholder.com/800x400.png?text=Cox+Proportional+Hazards)

---

## 🩺 Clinical Recommendations  

> 💡 *Translating data into practical strategies for improving survival outcomes:*

### ✅ **Actionable Insights**  
- 🩸 **Monitor Bilirubin:** Elevated levels require urgent care.  
- 🍽️ **Boost Albumin:** Nutritional therapy can improve survival.  
- 🛏 **Manage Edema Promptly:** Early intervention critical for severe cases.  
- 📉 **Stratify by Stage:** Customize treatment plans per disease severity.  
- 🚫 **Review D-Penicillamine Use:** No proven survival advantage over Placebo.

---

## 🚀 Getting Started  

### 🔧 Prerequisites  
Install required R packages:
```r
install.packages(c("survminer", "survival", "flexsurv", "tidyverse"))
```

### 📥 Clone & Run  
```bash
git clone https://github.com/your-username/liver-cirrhosis-survival.git
cd liver-cirrhosis-survival
```

Run the analysis:
```r
source("analysis.R")
```

---

## 🤝 Contributing  

We welcome ideas and improvements!  
- 📥 Submit a pull request  
- 🐛 Report bugs or issues  

> 🙌 Let’s work together to enhance survival research.

---

## 📄 License  

🛡️ **MIT License**  
Free to use, modify, and share — just give credit.

---

## 📬 Contact  

Got questions or feedback?  
📩 Email: [My email](mailto:enochosenwafulah@gmail.com)

---

