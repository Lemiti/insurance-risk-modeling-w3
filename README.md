# Insurance Risk Analytics & Predictive Modeling  
**AlphaCare Insurance Solutions (ACIS)**  
*Optimizing premiums by identifying low-risk segments using historical claim data (2014–2015).*

---

## 📌 Business Objective  
Analyze car insurance claims to:  
1. **Discover low-risk segments** (e.g., by province, vehicle type, gender).  
2. **Optimize premiums** using predictive modeling.  
3. **Test hypotheses** about risk drivers (e.g., "Do men file higher claims than women?").  

---

## 🛠️ Tasks Overview  
| Task | Deliverables |  
|------|-------------|  
| **1. EDA & Git Setup** | EDA notebook, interim report, visualizations |  
| **2. Data Version Control (DVC)** | Reproducible data pipeline |  
| **3. A/B Hypothesis Testing** | Statistical tests, risk/difference insights |  
| **4. Predictive Modeling** | Premium optimization models, SHAP analysis |  

---

## 📂 Repository Structure  
```bash
insurance-risk-analytics/  
├── data/                    # Raw and processed data (tracked with DVC)  
├── notebooks/  
│   ├── 1_EDA.ipynb          # Task 1: Exploratory Data Analysis  
│   ├── 2_Hypothesis_Testing.ipynb  
│   └── 3_Modeling.ipynb  
├── reports/  
│   ├── interim_report.md    # Task 1-2 summary  
│   └── final_report.md      # Medium-style blog post  
├── scripts/                 # Modular code (e.g., data cleaning)  
├── .gitignore  
├── README.md                # This file  
└── requirements.txt         # Python dependencies  
