## 🌆 Urban Development & Public Sentiment Analytics

### 📊 Power BI | Geospatial Intelligence | Sentiment Analysis

This project focuses on transforming city complaints and public sentiment data into actionable insights for smarter urban planning in **Bengaluru**. The dashboard enables city officials to identify neighborhood service issues, track infrastructure performance, and understand citizen emotions in real-time.

---

### 🚀 Project Objectives

* Build a unified analytical system combining complaint logs & sentiment data
* Provide geospatial insights for resource allocation and city health monitoring
* Identify sentiment patterns from citizen feedback text
* Track resolution rate, SLA adherence and service request KPIs
* Empower decision-makers through interactive Power BI dashboards

---

### 🏗 Data Architecture & Modeling

A Star Schema data model was designed with:

* **Fact_Complaints / Fact_Requests**
* Sentiment facts using NLP classification
* Dimensions for Date, Status, Category, Location, Transit, etc.

📌 Data modeling and processing includes:

* Data cleaning & transformation using Power Query
* Sentiment scoring via NLP (Azure Cognitive Services)
* Geocoding latitude/longitude to neighborhood zones

📄 Model & architecture are aligned with methodologies described in the project report


---

### 📌 Features & Visualizations

The project delivers a **two-page Power BI dashboard**:

#### **📍 Page 1 — Overview & City Health Summary**

* Total requests & trend analysis
* Resolution rate & SLA comparison
* Positive / Negative / Neutral sentiment distribution
* Category-level complaint volume across time
* Neighborhood-based service performance filters

#### **🎯 Page 2 — Sentiment & Feedback Deep Dive**

* Sentiment trend over time
* Source breakdown (Twitter, Email, Call Center, Mobile App)
* Emotion category analysis (Anger, Joy, Neutral, Sadness, Trust)
* Geographic sentiment hotspot mapping
* Key verbatim complaint insights via AI table

These visuals help:

* Locate service gaps
* Measure public trust & frustration
* Prioritize urban improvement actions

---

### 📂 Tech Stack Used

| Layer                  | Tools & Tech                                                    |
| ---------------------- | --------------------------------------------------------------- |
| Data                   | CSV / Public Open Data / API Inputs                             |
| Processing & Modelling | Power Query, DAX, Azure Text Analytics                          |
| Visualization          | Power BI (Azure Maps, Donut/Line charts, Decomposition visuals) |

✔ RLS (Row Level Security) considered for sensitive access control

---

### 👥 Team Contributions

| Member                 | Responsibility                                                               |
| ---------------------- | ---------------------------------------------------------------------------- |
| **Varun Panchal**      | Designed & developed Dashboard Page-1                                        |
| **Rajeshwari Acharya** | Dataset cleaning & project report documentation                              |
| **Karanam Akhil**      | Designed & developed Dashboard Page-2, Sentiment insights                    |

✔ This is a team academic-industry project developed under **Infotact Solutions**.

---

### 📌 Project Structure

```
├── Data/
│   ├── Fact_Complaints.csv
│   ├── Sentiment_Data.csv
│   ├── Location_Data.csv
│   ├── Dim_Category.csv
│   ├── Dim_Date.csv
│   └── ...
├── PowerBI/
│   ├── Dashboard_Page1.pbix
│   ├── Dashboard_Page2.pbix
├── Documentation/
│   ├── Project_Report.pdf
│   ├── Data_Model_screenshots/
│   └── README.md
```

---

### 🏁 Outcomes & Findings

✔ 50%+ complaints carried negative sentiment — strong citizen dissatisfaction
✔ Garbage & Noise complaints highest → require immediate action
✔ Downtown & South Bengaluru show the worst sentiment clusters
✔ Social media platforms drive most negative feedback spikes
✔ SLA delays directly influence sentiment drop patterns

These insights demonstrate the value of **data-driven urban management**.

---

### 🔮 Future Enhancements

* Live integration with 311 real-time APIs
* Predictive hotspot detection (Machine Learning)
* Multilingual sentiment classification
* Mobile-friendly dashboards for field teams
