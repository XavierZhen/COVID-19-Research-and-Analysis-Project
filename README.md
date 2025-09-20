# 👋 Hi, It's Xavier — Welcome to my GitHub Profile  

---

## 🌍 COVID-19 Global Impact Analysis  

### 📖 Abstract  
This study investigates the **global impact of COVID-19** by analyzing differences in mortality and infection rates across countries and examining how government strategies, healthcare capacity, and vaccination programs shaped epidemic outcomes.  
The project applies **data-driven methods** to assess the effectiveness of epidemic prevention measures and provides insights into how countries can better prepare for future global health crises.  

---

## 🎯 Research Objectives  
- 🔎 Identify determinants of **mortality and infection rates** across countries  
- 🏛 Evaluate the **effectiveness of government policies** (lockdowns, stringency measures, border closures)  
- 💉 Assess the **impact of vaccination campaigns** on infection control and mortality reduction  
- 🌏 Compare outcomes across **case studies** (UK, Japan, India, Australia, Ukraine)  
- 📊 Derive **policy implications** for epidemic preparedness and response  

---

## 🛠️ Methodology  

**Dataset**: COVID-19 data from [Our World in Data](https://github.com/owid/covid-19-data)  
- Timeframe: Jan 2020 – Oct 2022  
- Coverage: 232 countries, 67 variables  

**Data Processing:**  
```python
# Example data handling snippet
# (not full code, just to show repo style)

# Handle missing values
df = df.dropna()

# Normalize features
from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
df_scaled = scaler.fit_transform(df)

# Example: check correlation with mortality
df.corr()['mortality_rate'].sort_values(ascending=False)
```

---
## 📈 Key Findings  
- 🏥 **Healthcare Capacity Matters**: Higher hospital bed density & GDP correlated with lower mortality  
- 🏛 **Policy Effectiveness**:  
  - "Herd immunity" approaches → higher mortality (e.g., UK)  
  - Strict lockdowns → lower transmission (e.g., Japan, Australia, China)  
- 💉 **Vaccinations**: Reduced severe outcomes, but protection waned with Omicron  
- 🌐 **Socioeconomic & Cultural Factors** influenced compliance & outcomes  

---

## 📂 Repository Contents  
```bash
📁 notebooks/        # Jupyter notebooks (EDA, analysis, visualizations) → see external link below
📁 report/           # Analysis Report (PDF)
📁 data/             # External dataset reference (link below)
```

📥 Dataset Source: [Our World in Data – COVID-19](https://github.com/owid/covid-19-data)

📓 Full Jupyter Notebook (with outputs): [View on Google Drive](https://drive.google.com/file/d/15ILJy1dGnQTPYd7qM6d1hzMLIxfViJju/view?usp=drive_link)


> ⚠️ *Note: The full notebook exceeds GitHub’s 25MB limit, so it is hosted externally.  
> A lightweight version (without outputs) is included in this repo for quick review.*

---

## ⚠️ Limitations  
- 🗂️ Missing or inconsistent reporting in some countries  
- 🧪 Testing/reporting differences reduce comparability  
- 🦠 Variant-specific effects (Delta, Omicron) not fully captured  

---

## 🧭 Implications  
This study highlights the **importance of healthcare infrastructure, rapid policy response, and vaccination campaigns**.  
Future preparedness should combine **data-driven decision making** with flexible, context-specific interventions.  
