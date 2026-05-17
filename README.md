# 🏥 Hospital Emergency Room Analytics Dashboard  

<div align="center">

![Healthcare](https://img.shields.io/badge/Domain-Healthcare-blue)
![Tool](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Python](https://img.shields.io/badge/Python-Pandas-green)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Dataset](https://img.shields.io/badge/Records-9,216-orange)

</div>

---

# 📌 Project Overview

This project presents a comprehensive analysis of **9,216 emergency room visits** recorded between **April 2023 and October 2024**.  

The dashboard helps identify:
- Patient flow patterns
- Peak emergency hours
- Department workload
- Waiting time impact on satisfaction
- Admission trends
- Demographic distribution

The main objective is to support **hospital management** in improving operational efficiency, reducing wait times, and enhancing patient care quality.

---

# 🎯 Project Objectives

✔ Analyze patient demographics and visit patterns  
✔ Monitor emergency room performance KPIs  
✔ Identify peak rush hours and busiest weekdays  
✔ Understand admission vs non-admission trends  
✔ Evaluate patient satisfaction levels  
✔ Support better staffing and resource allocation  

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|------|------|
| 👥 Total Unique Patients | **9,216** |
| ⏳ Average Wait Time | **35.3 Minutes** |
| ⭐ Average Satisfaction Score | **4.99 / 10** |
| 🏥 Admitted Patients | **50.4%** |
| 🚶 Non-Admitted Patients | **49.6%** |

---

# 📈 Dashboard Features

## 👨‍👩‍👧 Demographic Analysis
- Age group distribution
- Gender analysis
- Racial diversity insights

### Highlights
- Largest age group: **30–39 years**
- Gender ratio: **51.5% Male / 48.2% Female**
- Most represented race: **White patients**

---

## 🏥 Clinical & Operational Insights

### Top Referred Departments
| Department | Referrals |
|------------|------------|
| General Practice | 1,840 |
| Orthopedics | 1,030 |
| Physiotherapy | 776 |

### Peak Traffic Days
| Day | Patients |
|-----|-----------|
| Monday | 1,577 |
| Saturday | 1,322 |
| Tuesday | 1,318 |

### Peak Hours
🕚 11 AM  
🕐 1 PM  
🕖 7 PM  
🕚 11 PM  

---

# 🧠 Key Business Insights

## 1️⃣ Wait Time Impacts Satisfaction
- Longer waiting times reduce patient satisfaction.
- Optimizing queue management can improve patient experience.

---

## 2️⃣ High Department Load
- General Practice and Orthopedics handle maximum referrals.
- Additional staffing during peak hours may improve efficiency.

---

## 3️⃣ Balanced Admission Distribution
- Admission and non-admission rates are almost equal.
- Indicates balanced emergency handling capacity.

---

## 4️⃣ Diverse Patient Population
- Broad demographic diversity observed.
- Multilingual and culturally inclusive support services may help improve care quality.

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Python (Pandas) | Data Cleaning & Analysis |
| Power BI | Interactive Dashboard |
| Excel | Initial Data Processing |
| SQL | Data Querying |
| GitHub | Project Hosting |

---

# 📂 Project Files

```text
Hospital-Emergency-Room-Dashboard/
│
├── Dataset/
│   └── Hospital_ER_Data.csv
│
├── Dashboard/
│   └── Hospital_ER_Dashboard.pbix
│
├── Screenshots/
│   └── Dashboard Preview Images
│
├── README.md
│
└── Key_Takeaways/
```

---

# 📸 Dashboard Preview

## 🏥 Emergency Room Dashboard


---

# Average wait time by weekday
avg_wait = df.groupby('DayOfWeek')['Patient Waittime'].mean()

print(avg_wait)
```

---

# 📌 Future Improvements

- Real-time dashboard integration
- Predictive wait time analysis
- Machine learning for patient admission prediction
- Automated hospital resource optimization

---

# 🤝 Contributing

Contributions and suggestions are welcome.  
Feel free to fork this repository and improve the project.

---

# 📧 Contact

👤 Dinesh Tanwar  
🎓 BCA AI & ML Student  
📊 Aspiring Data Analyst | Power BI Developer  

---

<div align="center">

## ⭐ If you found this project useful, give it a star on GitHub!

</div>
