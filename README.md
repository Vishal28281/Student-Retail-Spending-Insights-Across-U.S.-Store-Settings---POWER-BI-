# Student-Retail-Spending-Insights-Across-U.S.-Store-Settings---POWER-BI-
A Power BI project analysing U.S. students’ spending across retail store settings (Urban, Suburban, Rural). It visualises expenses on video games, sports, books, gadgets, and toys by age group, using interactive dashboards, row-level security, and automated data refresh.

# 🧾 Student Retail Spending Insights Across U.S. Store Settings

## 📊 Project Overview
This Power BI project analyses **student spending patterns across U.S. retail store settings**.  
The dataset, *Student Survey*, includes details on how students spend on categories like:
- 🎮 Video Games  
- 🏏 Outdoor Sports  
- 🏠 Indoor Sports  
- 📚 Books  
- 🤖 Gadgets  
- 🎲 Toys  

The analysis helps identify trends across **different age groups** and **store types (Urban, Suburban, Rural)**.

---

## 🏢 Industry Type
**Retail Industry**

---

## 🧰 Dataset Information
- **Name:** Student Survey  
- **Source:** Provided dataset (CSV)  
- **Key Columns:**
  - Age  
  - Store Setting  
  - Video Games  
  - Indoor Sports  
  - Outdoor Sports  
  - Books  
  - Toys  
  - Gadgets  

---

## 🎯 Project Objectives
1. **Matrix Visualization:**  
   Show the amount spent on *Outdoor Sports* across different ages and store settings, with colour formatting.  

2. **Scatter Plot:**  
   Analyse the correlation between *Video Games* and *Outdoor Sports* spending across ages.  

3. **Sand Dance Plot:**  
   Visualise indoor sports vs. video games spending across age groups.  

4. **Row-Level Security (RLS):**  
   Restrict user access — for example, *Mani* can view only Rural data.  

5. **Master Dashboard:**  
   Combine a Funnel Chart and Scatter Plots into a single dashboard.  

6. **Scheduled Refresh:**  
   Configure 6 automatic refreshes per day (every 4 hours) on the Power BI Service.

---

## 🔐 Data Access Restriction (RLS Example)
| User | Store Setting |
|------|----------------|
| Mani | Rural          |
| John | Urban          |
| Emma | Suburban       |

RLS ensures each user sees only their relevant regional data.

---

## ☁️ Power BI Cloud Publishing
Steps followed:
1. Published `.pbix` file to Power BI Service  
2. Created a Master Dashboard combining visuals  
3. Scheduled dataset refresh every 4 hours (6 times/day)

---

## 📷 Key Visuals
| Visualization | Description |
|----------------|-------------|
| Matrix | Outdoor Sports spending by Age and Store Setting |
| Scatter Plot | Video Games vs Outdoor Sports spending |
| Sand Dance | Indoor Sports vs Video Games |
| Funnel Chart | Category-wise total spending |

---

## 🧩 Files Overview
| Folder | Description |
|---------|--------------|
| `data/` | Raw dataset (`student_survey.csv`) |
| `pbix/` | Power BI project file |
| `documentation/` | Reports, screenshots, and data dictionary |
| 'Project Statement/'
| `README.md` | Project overview and setup guide |

---



## 🏷️ Tags
`#PowerBI` `#Dashboard` `#RetailAnalytics` `#DataVisualization` `#StudentSurvey` `#BusinessIntelligence`
