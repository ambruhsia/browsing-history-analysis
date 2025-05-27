# 📁 Analyzing User Browsing History  
### 🔍 Data Exploration | 🧠 Behavioral Insights | 📊 Visual Storytelling
view on kaggle: https://www.kaggle.com/code/amritarajput54/pyinsight
---

## 📌 Summary

In this notebook, we perform an in-depth analysis of an anonymized **browsing history dataset** to extract meaningful behavioral insights, supported by clean visualizations and structured storytelling. The goal is to understand **how**, **when**, and **why** the user browses — identifying trends, patterns, and signals of attention or distraction.

We apply a combination of **data cleaning**, **session modeling**, **temporal analysis**, **sequence mining**, and **text-based sentiment modeling** to uncover a rich behavioral profile.

---

## 🧰 Techniques Used

### ✅ **Data Cleaning & Preprocessing**
- Skipped metadata rows and extracted structured headers
- Converted timestamps, derived day/time/hour features
- Extracted and normalized domains from URLs
- Defined browsing **sessions** based on 30-minute gaps

---

### 📈 **Behavioral Analyses & Visualizations**

1. **🕓 Temporal Trends**
   - Browsing patterns by hour, day of week, and session duration

2. **📊 Transition Type Breakdown**
   - Seaborn-styled pie chart showing how pages were reached (typed, link, etc.)

3. **🔁 Navigation Flow (Sankey Diagram)**
   - Domain-to-domain transitions via referral paths

4. **⏱️ Time Spent Analysis**
   - Identified "long visit" domains using top quartile filter  
   - Visualized with a horizontal bar chart

5. **🧘 Idle vs Active Tabs**
   - Classified pages as **Idle** vs **Active** based on dwell time  
   - Summarized attention allocation and engagement depth

6. **🎢 Browsing Mood Rollercoaster**
   - Applied **VADER sentiment analysis** on page titles  
   - Visualized emotional journey across sessions

7. **🔁 Cross-Session Continuity**
   - Detected domains revisited after long gaps  
   - Flagged task continuity and long-term user interest

8. **📈 Sequence Mining (PrefixSpan)**
   - Identified frequent domain visit patterns (e.g., `google.com → upwork.com`)  
   - Interpreted intent like job search, research, or tool usage

9. **🧠 Topic Modeling from Page Titles**
   - Used **LDA** on cleaned titles to extract dominant browsing themes  
   - Themes included travel, job tools, search, and productivity

---

## ✅ Task Coverage Checklist

| Requirement                             | ✅ Done |
|----------------------------------------|--------|
| Load, clean, and structure the dataset | ✅     |
| Analyze user behavior patterns         | ✅     |
| Identify key metrics and trends        | ✅     |
| Create at least 5 visualizations       | ✅ 9+  |
| Apply ML or text mining techniques     | ✅ LDA, VADER, PrefixSpan |
| Deliver insights through storytelling  | ✅     |
| Present results in a structured report | ✅     |

---

> 💡 **Outcome**: This notebook delivers a comprehensive, multi-angle exploration of the user's browsing behavior — surfacing **attention patterns**, **task flows**, **interest clusters**, and even **mood shifts** — all supported with intuitive visualizations and explainable logic.
