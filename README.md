<div align="center">

<img src="Customer%20Churn%20Analysis/images/banner_animated_full.gif" alt="Customer Churn Analysis animated banner" width="100%"/>

<br/>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
<img src="https://img.shields.io/badge/Seaborn-2DD4BF?style=for-the-badge&logoColor=white" alt="Seaborn"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logoColor=white" alt="Matplotlib"/>

<img src="https://img.shields.io/badge/📉_Churn_Rate-26.5%25-F43F5E?style=flat-square" alt="Churn rate"/>
<img src="https://img.shields.io/badge/💸_Revenue_Leakage-$139.1K%2Fmonth-F59E0B?style=flat-square" alt="Revenue leakage"/>
<img src="https://img.shields.io/badge/👥_Customers-7%2C043-2DD4BF?style=flat-square" alt="Customers"/>
<img src="https://img.shields.io/badge/📊_Dashboard_Pages-4-8B5CF6?style=flat-square" alt="Dashboard pages"/>
<img src="https://img.shields.io/badge/✅_Status-Completed-22C55E?style=flat-square" alt="Status"/>
<img src="https://img.shields.io/badge/🤝_PRs-Welcome-3B82F6?style=flat-square" alt="PRs welcome"/>

<br/><br/>

<a href="https://www.linkedin.com/in/ayush-jena/"><img src="https://img.shields.io/badge/LinkedIn-Ayush_Jena-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ayushjena227@gmail.com"><img src="https://img.shields.io/badge/Email-ayushjena227@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/ayushjena1"><img src="https://img.shields.io/badge/GitHub-ayushjena1-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/>

<img src="https://img.shields.io/github/stars/ayushjena1/Customer-Churn-Analysis?style=social" alt="Stars"/>
<img src="https://img.shields.io/github/forks/ayushjena1/Customer-Churn-Analysis?style=social" alt="Forks"/>

</div>

---

> ### 🔥 Project at a Glance
> A telecom company loses **26.5% of its customers**, which means **💸 $139.1K of monthly revenue** walking out the door. I cleaned the data 🧹, built a rule-based **risk model** 🚦, found what drives churn 🔍, and turned it into a **4-page Power BI dashboard** 📊 with a prioritised retention plan 🎯.

---

<details>
<summary><b>🌳📂 Repository structure (click to expand)</b></summary>

```text
.
├── Customer Churn Analysis/
│   ├── images/
│   │   ├── banner_animated.gif
│   │   ├── 01_churn_overview.png
│   │   ├── 02_risk_and_retention.png
│   │   ├── 03_revenue_and_behaviour_drivers.png
│   │   └── 04_strategic_recommendations.png
│   ├── analyzed_cleaned_churn.csv
│   ├── churn_analysis_dashboard.pbix
│   ├── customer_churn_analysis.ipynb
│   └── customer_churn_dataset.csv
└── README.md
```
</details>

---

## 🎯 Project Summary

| Step | What happened |
|:-:|---|
| 🧹 | **Clean:** fixed missing values and converted codes into readable labels |
| 🛠️ | **Engineer:** created a `TotalServices` count and a rule-based `RiskProfile` (High / Medium / Low) |
| 🔍 | **Explore:** compared churn across contract, tenure, services, payment method and demographics |
| 📊 | **Visualise:** built a 4-page Power BI dashboard (Overview, Risk & Retention, Drivers, Recommendations) |
| 💡 | **Recommend:** turned the findings into prioritised actions with a 90-day roadmap |

---

## ❓ Business Problems

| # | 🤔 Question the analysis answers | 📍 Where to look |
|:-:|---|---|
| 1️⃣ | How much of the customer base and revenue is churn costing us? | Dashboard 1 |
| 2️⃣ | Which contract types drive churn? | Dashboards 1 and 3 |
| 3️⃣ | When in the customer lifecycle do people leave? | Dashboards 1 and 2 |
| 4️⃣ | Which internet service has the weakest retention? | Dashboards 1 and 3 |
| 5️⃣ | Do add-ons like Tech Support and Online Security reduce churn? | Dashboard 3 |
| 6️⃣ | Does payment method or billing type affect churn? | Dashboard 3 |
| 7️⃣ | Which customers should the retention team contact first? | Dashboard 2 |
| 8️⃣ | How much revenue can be protected, and with which actions? | Dashboard 4 |

---

## 🗃️ Dataset

📄 **File:** [customer_churn_dataset.csv](Customer%20Churn%20Analysis/customer_churn_dataset.csv) · 📏 **Size:** 7,043 customers × 21 columns · 🎯 **Target:** `Churn` (Yes / No)

| 🗂️ Group | 📋 Columns |
|---|---|
| 👤 Demographics | `gender`, `SeniorCitizen`, `Partner`, `Dependents` |
| 📞 Services | `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies` |
| 📝 Account | `tenure`, `Contract`, `PaperlessBilling`, `PaymentMethod` |
| 💵 Billing | `MonthlyCharges`, `TotalCharges` |
| 🎯 Target | `Churn` |
| ✨ **Added by me** | `TotalServices`, `RiskProfile`, `TenureGroup`, `Segments`, `AddOns`, `RevenueLeakage` |

---

## 🧪 What I Did in the Queries

Everything is in [📓 customer_churn_analysis.ipynb](Customer%20Churn%20Analysis/customer_churn_analysis.ipynb), built with pandas, NumPy, Matplotlib and Seaborn.

### 1️⃣ Load and inspect 📥
Read the CSV and checked it with `df.shape`, `df.info()`, `df.describe()` and `df.describe(include='all')`.

### 2️⃣ Clean 🧹
- Ran `df.isnull().sum()`, which found **11 missing `TotalCharges`** values.
- Replaced them with `0`, since these are brand-new customers (tenure 0) who have not been billed yet.
- Converted `SeniorCitizen` from 0/1 to No/Yes with a custom function and `.apply()`, so charts and the dashboard are readable.

### 3️⃣ Engineer features 🛠️

**➕ `TotalServices`: how many services each customer uses**

```python
df['TotalServices'] = (
    (df['StreamingTV'] == 'Yes').astype(int) +
    (df['StreamingMovies'] == 'Yes').astype(int) +
    df['InternetService'].isin(['DSL', 'Fiber optic']).astype(int) +
    (df['PhoneService'] == 'Yes').astype(int) +
    (df['MultipleLines'] == 'Yes').astype(int) +
    (df['OnlineSecurity'] == 'Yes').astype(int) +
    (df['TechSupport'] == 'Yes').astype(int) +
    (df['DeviceProtection'] == 'Yes').astype(int) +
    (df['OnlineBackup'] == 'Yes').astype(int)
)
```

**🚦 `RiskProfile`: rule-based churn risk tier**

```python
def assign_risk_profile(row):
    contract, tenure, services = row['Contract'], row['tenure'], row['TotalServices']

    if contract == 'Month-to-month' and (tenure <= 10 or services < 3):
        return 'High Risk'
    elif contract in ['One year', 'Two year'] and tenure > 12 and services > 3:
        return 'Low Risk'
    else:
        return 'Medium Risk'

df['RiskProfile'] = df.apply(assign_risk_profile, axis=1)
```

### 4️⃣ Explore 🔍

| 🔬 Analysis | 🧰 Technique | 📌 Result |
|---|---|---|
| 📉 Overall churn | `countplot`, `groupby`, pie chart | 1,869 churned, **26.54%** |
| ⚧️ Gender | `countplot(hue='Churn')` | Slightly more females churned |
| 👴 Senior citizens | `countplot(hue='Churn')` | Small group with a much higher churn rate |
| 💑 Partner status | `countplot(hue='Churn')` | Customers without partners churn more |
| ⏳ Tenure | `groupby(['tenure','Churn'])`, `histplot` | Churn clusters in the first months |
| 📝 Contract | `countplot(hue='Churn')` | Month-to-month churns the most |
| 🧩 Service columns | 3×3 grid of `countplot`s over 9 service columns | Missing protection add-ons means more churn |
| 🔢 Total services | `groupby` + `unstack` summary table, bar chart | Peaks at 3 services (44.9%) |
| 🚦 Risk profile | `agg()` summary table, bar chart | High 47.7%, Medium 22.9%, Low 9.3% |

### 5️⃣ Validate and export ✅
Built a risk-vs-churn summary table (customers, churned, churn %) to confirm the tiers separate churners, then exported the final data to [📄 analyzed_cleaned_churn.csv](Customer%20Churn%20Analysis/analyzed_cleaned_churn.csv), which feeds Power BI.

---

## 🚦 Risk Segmentation Model

| Tier | 📏 Rule | 👥 Customers | 🚪 Churned | 📉 Churn rate |
|---|---|:-:|:-:|:-:|
| 🔴 **High** | Month-to-month **and** (tenure ≤ 10 months **or** fewer than 3 services) | 2,132 | 1,017 | **47.7%** |
| 🟡 **Medium** | Everyone else | 2,913 | 667 | **22.9%** |
| 🟢 **Low** | 1- or 2-year contract **and** tenure > 12 months **and** more than 3 services | 1,998 | 185 | **9.3%** |

✅ High-risk customers are **30% of the base but 54% of all churners**, and churn is roughly **5× higher** than in the Low tier.

---

## 📈 Key Insights

| | 🔎 Insight | 📊 Evidence |
|:-:|---|---|
| 📝 | **Contract is the #1 driver** | Month-to-month churns at **42.7%** vs 11.3% (1-year) and 2.8% (2-year), about 15× higher |
| 💸 | **Leakage is concentrated** | **86.9% ($120.8K)** of the $139.1K leakage comes from month-to-month customers |
| 🌐 | **Fiber optic is the weakest link** | **41.9%** churn vs 19.0% on DSL; Fiber holds **$114.3K (82%)** of leakage |
| 🐣 | **Year one is the danger zone** | **47.4%** churn at 0–12 months, falling to **9.5%** after 4+ years |
| 💳 | **Electronic check is a red flag** | **45%** churn vs 15–19% for other payment methods |
| 🛡️ | **Add-ons build loyalty** | Without Tech Support: **41.6%** churn; with it: **15.2%** |
| 👥 | **Profile matters** | Senior citizens (~42%) and paperless-billing users (~34%) churn well above average |
| 📦 | **Bundles retain** | Customers with 8+ services churn below **12%** |

---

## 🖼️ Power BI Dashboard Gallery

The report in [📊 churn_analysis_dashboard.pbix](Customer%20Churn%20Analysis/churn_analysis_dashboard.pbix) has four pages with a navigation bar at the top.

### 📊 Page 1: Churn Overview
*Where churn happens and how much revenue it costs.*

<img src="Customer%20Churn%20Analysis/images/01_churn_overview.png" alt="Churn Overview dashboard" width="100%"/>

### 🚦 Page 2: Risk & Retention
*Risk profiles built on contract type, tenure and total services.*

<img src="Customer%20Churn%20Analysis/images/02_risk_and_retention.png" alt="Risk and Retention dashboard" width="100%"/>

### 🔬 Page 3: Revenue & Behaviour Drivers
*What billing, add-ons and customer profile say about churn.*

<img src="Customer%20Churn%20Analysis/images/03_revenue_and_behaviour_drivers.png" alt="Revenue and Behaviour Drivers dashboard" width="100%"/>

### 🎯 Page 4: Strategic Recommendations
*Executive actions, revenue protection and the retention roadmap.*

<img src="Customer%20Churn%20Analysis/images/04_strategic_recommendations.png" alt="Strategic Recommendations dashboard" width="100%"/>

---

## 💡 Strategic Recommendations

| 🏁 Priority | 🛠️ Action | 🎯 Target segment | 🧾 Evidence |
|:-:|---|---|---|
| 🔴 **High** | Build a 90-day onboarding and check-in programme | Tenure 0–12 months (2,186) | 47.4% churn in year one |
| 🔴 **High** | Move month-to-month customers to 12/24-month plans | Month-to-month (3,875) | 42.7% vs 11.3% on 1-year |
| 🔴 **High** | Review Fiber optic pricing and service quality | Fiber optic (3,096) | 41.9% churn, $114.3K leakage |
| 🟡 Medium | Bundle Tech Support and Online Security | Internet users without add-ons | 41.6% vs 15.2% with Tech Support |
| 🟡 Medium | Incentivise auto-pay over electronic check | Electronic check (2,365) | 45.3% vs 16.0% on auto-pay |
| 🟡 Medium | Run a monthly risk watchlist | High-risk customers (2,132) | 54% of all churners |

### 🗓️ 90-Day Roadmap

| 🧱 Days 1–30: Foundation | 🧪 Days 31–60: Pilot | 🚀 Days 61–90: Scale |
|---|---|---|
| Publish a risk-scored watchlist<br>Launch a contract-upgrade offer<br>Design an auto-pay incentive | Start the 90-day onboarding flow<br>Trial protection bundles<br>Fiber quality review | A/B test each lever<br>Roll out what works<br>Track KPIs monthly |

### 🎁 Estimated Impact (illustrative)

<img src="https://img.shields.io/badge/🙌_Fewer_Churned_Customers-~555-F43F5E?style=for-the-badge" alt="Fewer churned customers"/>
<img src="https://img.shields.io/badge/💰_Revenue_Retained-~$41.3K%2Fmonth-22C55E?style=for-the-badge" alt="Revenue retained"/>
<img src="https://img.shields.io/badge/📝_Long--term_Contracts-45%25_→_55%25-3B82F6?style=for-the-badge" alt="Long-term contracts"/>
<img src="https://img.shields.io/badge/📉_Churn_Rate-26.5%25_→_18.7%25-F59E0B?style=for-the-badge" alt="Churn rate improvement"/>

> ⚠️ These figures come from a scenario (20% of month-to-month customers move to 1-year plans, 15% of internet customers without Tech Support adopt it, 25% of electronic-check customers switch to auto-pay). They are estimated before overlap between levers and based on correlation, so validate them with A/B pilots.

**📌 KPIs to track:** churn rate (26.5%) · annual/2-year contract share (45%) · Tech Support attach rate (29%) · auto-pay share (44%) · monthly revenue leakage ($139.1K)

---

## 🧰 Skills Demonstrated

<img src="https://img.shields.io/badge/🧹_Data_Cleaning-2DD4BF?style=for-the-badge" alt="Data Cleaning"/>      <img src="https://img.shields.io/badge/🛠️_Feature_Engineering-2DD4BF?style=for-the-badge" alt="Feature Engineering"/>
<img src="https://img.shields.io/badge/🔍_EDA-2DD4BF?style=for-the-badge" alt="EDA"/>
<img src="https://img.shields.io/badge/🐼_Pandas_GroupBy-F59E0B?style=for-the-badge" alt="Pandas GroupBy"/>
<img src="https://img.shields.io/badge/📈_Data_Visualisation-F59E0B?style=for-the-badge" alt="Data Visualisation"/>
<img src="https://img.shields.io/badge/📊_Power_BI-F2C811?style=for-the-badge&labelColor=F2C811&logoColor=black" alt="Power BI"/>
<img src="https://img.shields.io/badge/🎛️_KPI_Design-F59E0B?style=for-the-badge" alt="KPI Design"/>
<img src="https://img.shields.io/badge/🚦_Customer_Segmentation-F43F5E?style=for-the-badge" alt="Customer Segmentation"/>
<img src="https://img.shields.io/badge/💼_Business_Analysis-F43F5E?style=for-the-badge" alt="Business Analysis"/>
<img src="https://img.shields.io/badge/🗣️_Data_Storytelling-F43F5E?style=for-the-badge" alt="Data Storytelling"/>

| 🧠 Area | ✅ Applied |
|---|---|
| 🐍 **Python** | pandas, NumPy, Matplotlib, Seaborn, Jupyter |
| 🧹 **Data preparation** | Null handling, label conversion, custom `apply()` functions |
| 🛠️ **Feature engineering** | `TotalServices` metric, rule-based `RiskProfile` |
| 📊 **Business intelligence** | Multi-page Power BI report, KPI cards, heatmaps, segment drill-downs |
| 🔬 **Analytical thinking** | Root-cause analysis, segmentation, revenue-at-risk quantification |
| 🗣️ **Communication** | Executive summary, prioritised recommendations, 90-day roadmap |

---

## 📬 Contact

<div align="center">

### 👋 Hi, I'm **Ayush Jena**
*Let's talk data, dashboards and customer retention!*

<a href="https://www.linkedin.com/in/ayush-jena/"><img src="https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:ayushjena227@gmail.com"><img src="https://img.shields.io/badge/Email_me-ayushjena227@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/ayushjena1"><img src="https://img.shields.io/badge/Follow_on-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/>

<img src="https://img.shields.io/badge/Made_with-❤️_%26_Python-F43F5E?style=flat-square" alt="Made with love and Python"/>
<img src="https://img.shields.io/badge/Powered_by-☕_Coffee-92400E?style=flat-square" alt="Powered by coffee"/>
<img src="https://img.shields.io/badge/Insights_by-📊_Power_BI-F2C811?style=flat-square" alt="Insights by Power BI"/>

⭐ **If this project helped you, drop a star on the repo!** ⭐

</div>
