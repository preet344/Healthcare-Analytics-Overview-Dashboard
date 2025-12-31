# 🏥 Healthcare Analytics Dashboard

**An end-to-end Power BI solution analyzing patient records, hospital performance, and operational efficiency. Identifies cost-saving opportunities and underperforming departments.**

<img width="604" height="333" alt="image" src="https://github.com/user-attachments/assets/39fcb9ef-4d15-4b0b-b5cf-6f1753aab781" />


## 🎯 **Business Problem**
Hospitals faced challenges with:
- Manual tracking of **patient LOS** (avg 5.2 days)
- **15% readmission rates**
- No real-time visibility into **departmental costs**
- Slow KPI reporting (days instead of hours)

## 💡 **Solution Impact**
- **30% faster KPI reporting**
- Identified **top 3 underperforming departments**
- **₹5-10L monthly cost savings potential**
- Real-time slicers for Hospital/Department/Diagnosis analysis

## 🛠️ **Tech Stack**
- Power BI Desktop (Data Modeling, DAX)
- SQL (ETL Pipeline)
- Excel (Initial EDA)
- 20+ Advanced DAX Measures

## 📊 **Key Features**

### **Dashboard Components**

| Visual | KPI | Purpose |
|--------|-----|---------|
| **KPI Cards** | Total Patients, Avg LOS, Readmission %, Avg Cost | Executive overview |
| **Line Chart** | Monthly Admissions Trend | Capacity planning |
| **Bar Chart** | Dept-wise Cost Ranking | Resource allocation |
| **Scatter Plot** | Cost vs Recovery | Efficiency analysis |
| **Map** | Hospital Performance | Geographic insights |
| **Slicers** | Hospital, Dept, Diagnosis | Interactive filtering |

### **Advanced DAX Measures**
- `Readmission Rate %` - 15.2% benchmark
- `Cost Per Patient` - Dept-wise ranking
- `Potential Savings` - ₹7.5L/month
- `Hospital Efficiency Score` - Performance benchmarking

## 🚀 **Quick Setup**
**1. Clone/Download repo:**
git clone https://github.com/yourusername/Healthcare-Analytics-Dashboard.git

**2. Open in Power BI Desktop:**
Healthcare_Analytics_Dashboard.pbix

**3. Explore interactive slicers:**


## 📈 **Key Insights Generated**
🏥 Top 3 Underperformers: Cardiology, Orthopedics, Respiratory

💰 Potential Savings: ₹5-10L/month (30% cost reduction)

⏱️ Avg LOS: 5.2 days (Target: <5 days)

📊 Readmission Rate: 15.2% (Target: <10%)

🏥 Best Hospital: Hospital A (Recovery Score: 8.7/10)

## 🎓 **Skills Demonstrated**
✅ Data Modeling (1:M relationships)

✅ Advanced DAX (Ranking, Time Intelligence, Forecasting)

✅ Interactive Visualizations (Slicers, Drill-through)

✅ ETL Pipeline Design (SQL → Power BI)

✅ Executive Reporting (KPIs, Actionable Insights)


## 📊 **Sample Data Preview**

**Patient Records (1K+ rows)**
PatientID,Age,LengthOfStay,Diagnosis,ReadmissionFlag

P001,45,5,Cardiac,No

P002,32,3,Respiratory,Yes


**Treatment Details**
PatientID,Hospital,Department,TotalTreatmentCost,RecoveryRating

P001,HospitalA,Cardiology,₹25,000,8.5


## 🔗 **Live Demo**
<img width="597" height="338" alt="image" src="https://github.com/user-attachments/assets/ce6948f3-b56f-4fd1-bbd6-ab14ade2addd" />
<img width="601" height="337" alt="image" src="https://github.com/user-attachments/assets/dded4213-9f4f-42bc-b86f-432d03a3efc1" />
<img width="597" height="336" alt="image" src="https://github.com/user-attachments/assets/6b105700-2dca-45cd-91f3-65b6d2291d3e" />
<img width="599" height="333" alt="image" src="https://github.com/user-attachments/assets/b977a965-d155-4bd1-a11e-3721957410e7" />

## 📈 **Resume Bullet Points**
- Built Power BI dashboard analyzing patient records → 30% faster KPI reporting, ₹5-10L savings
- 20+ DAX measures for LOS, readmission (15%), cost-per-patient rankings
- Identified top 3 underperforming departments using interactive slicers
