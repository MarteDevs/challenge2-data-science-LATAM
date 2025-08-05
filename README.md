# 🚀 TelecomX Customer Churn Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776ab?style=for-the-badge&logo=python&logoColor=white)

**💀 BREAKING THE CHURN CYCLE 💀**

*Data Science meets rebellion against customer loss*

[![License](https://img.shields.io/badge/License-MIT-red.svg?style=flat-square)](#license)
[![GitHub stars](https://img.shields.io/github/stars/MarteDevs/telecomx-churn-analysis?style=flat-square&color=yellow)](#)
[![GitHub issues](https://img.shields.io/github/issues/MarteDevs/telecomx-churn-analysis?style=flat-square&color=orange)](#)

</div>

---

## 🎯 **MISSION STATEMENT**

> *"In a world where customers vanish like ghosts, we bring the dead back to life through data."*

This project analyzes customer churn patterns for **TelecomX**, a telecommunications company facing high cancellation rates. Using Python and advanced data science techniques, we dissect the anatomy of customer loss and forge weapons against churn.

---

## ⚡ **QUICK START**

```bash
# Clone the rebellion
git clone https://github.com/MarteDevs/challenge2-data-science-LATAM.git

# Enter the battlefield
cd challenge2-data-science-LATAM

# Install your arsenal
pip install pandas numpy matplotlib seaborn requests jupyter

# Launch the attack
jupyter notebook TelecomX_LATAM.ipynb
```

---

## 🛠️ **TECH STACK**

| Tool | Purpose | Version |
|------|---------|---------|
| 🐍 **Python** | Core language | 3.8+ |
| 🐼 **Pandas** | Data manipulation | Latest |
| 🔢 **NumPy** | Numerical operations | Latest |
| 📊 **Matplotlib** | Visualization engine | Latest |
| 🌊 **Seaborn** | Statistical plots | Latest |
| 📓 **Jupyter** | Interactive development | Latest |

---

## 📊 **PROJECT ANATOMY**

```
challenge2-data-science-LATAM/
├── 📓 TelecomX_LATAM.ipynb    # Main analysis notebook
├── 📄 README.md              # Project documentation
├── 📊 visualizations/        # Generated plots
│   ├── churn_distribution.png
│   ├── contract_analysis.png
│   └── payment_method_breakdown.png
└── 📑 reports/              # Analysis insights
    └── final_report.md
```

---

## 🔬 **ANALYSIS PIPELINE**

### **Phase 1: Data Extraction** 🎣
- **Source**: JSON API endpoint
- **Raw records**: 7,043 customers
- **Method**: RESTful API consumption

### **Phase 2: Data Transformation** ⚙️
- **Normalization**: Flattened nested JSON structures
- **Cleansing**: Removed duplicates and null values
- **Feature Engineering**: Created `Cuentas_Diarias` metric
- **Standardization**: Binary encoding (Yes/No → 1/0)
- **Localization**: Spanish column naming

### **Phase 3: Exploratory Data Analysis** 🔍
- **Descriptive Statistics**: Mean, median, standard deviation
- **Churn Distribution**: Customer retention patterns
- **Categorical Analysis**: Gender, contract type, payment method
- **Numerical Analysis**: Tenure, charges, billing patterns

---

## 💀 **KEY FINDINGS**

<div align="center">

### **THE CHURN LANDSCAPE**

| Metric | Value | Impact |
|--------|-------|--------|
| 🟢 **Retained Customers** | 5,174 | 73.5% |
| 🔴 **Churned Customers** | 1,869 | 26.5% |
| ⚖️ **Gender Balance** | ~50/50 | Minimal impact |

</div>

### **🎯 HIGH-RISK SEGMENTS**

- **📅 Month-to-Month Contracts**: 1,655 churned customers (88% of total churn)
- **💳 Electronic Check Payments**: 1,071 churned customers (57% of total churn)
- **⏰ Early Tenure**: Median churn at 10 months vs 40 months for retained

### **🛡️ RETENTION CHAMPIONS**

- **📋 Two-Year Contracts**: Only 48 churned customers
- **🏦 Bank Transfer/Credit Card**: Lower churn rates
- **👥 Long-term Customers**: 60+ months show loyalty

---

## 📈 **VISUALIZATIONS**

The project generates several punk-inspired visualizations:

- **Churn Distribution Charts** 📊
- **Contract Type Analysis** 📋
- **Payment Method Breakdown** 💳
- **Tenure vs Churn Patterns** ⏰
- **Revenue Impact Analysis** 💰

---

## 🚨 **STRATEGIC RECOMMENDATIONS**

### **IMMEDIATE ACTIONS** ⚡
1. **Month-to-Month Contract Reform**
   - Enhance monthly plan benefits
   - Introduce loyalty rewards
   - Implement retention bonuses

2. **Electronic Check Investigation**
   - Analyze payment friction points
   - Offer alternative payment methods
   - Provide payment support services

### **LONG-TERM STRATEGY** 🎯
- **Early Intervention Program**: Target customers at 6-12 month mark
- **Contract Migration Incentives**: Move monthly customers to annual plans
- **Payment Experience Optimization**: Streamline billing processes

---

## 🔧 **INSTALLATION & SETUP**

### **Prerequisites**
- Python 3.8 or higher
- Jupyter Notebook
- Internet connection (for data fetching)

### **Dependencies**
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import requests
import json
```

### **Installation Steps**
```bash
# Create virtual environment (optional but recommended)
python -m venv telecom_env

# Activate environment
source telecom_env/bin/activate  # Linux/Mac
# or
telecom_env\Scripts\activate     # Windows

# Install required packages
pip install pandas numpy matplotlib seaborn requests jupyter
```

---

## 🤝 **CONTRIBUTING**

We welcome fellow data rebels! Here's how to join the fight:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/new-analysis`)
3. **Commit** your changes (`git commit -m 'Add retention model'`)
4. **Push** to the branch (`git push origin feature/new-analysis`)
5. **Open** a Pull Request

### **Contribution Guidelines**
- Follow PEP 8 coding standards
- Add docstrings to functions
- Include unit tests for new features
- Update documentation as needed

---

## 📜 **LICENSE**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 **TEAM**

<div align="center">

**Data Science Rebel** 🎭  
*Bringing order to chaotic customer data*

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MarteDevs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/martedevs)

</div>

---

## 🚀 **WHAT'S NEXT?**

- [ ] **Machine Learning Models**: Build predictive churn models
- [ ] **Real-time Dashboard**: Create interactive visualizations
- [ ] **A/B Testing Framework**: Test retention strategies
- [ ] **API Integration**: Automate data pipeline
- [ ] **Advanced Segmentation**: Customer persona analysis

---

<div align="center">

**💀 FIGHT THE CHURN. WIN THE WAR. 💀**

*Made with ❤️ and rebellion by the Data Science Underground*

---

**⭐ Star this repo if you found it useful! ⭐**

</div>
