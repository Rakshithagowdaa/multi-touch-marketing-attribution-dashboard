# Multi-Touch Marketing Attribution Dashboard

This project focuses on analyzing how different marketing channels contribute to customer conversions. Instead of crediting only the final interaction (last-touch), this dashboard evaluates **multiple touchpoints** to understand the real influence of each channel throughout the customer journey.

## 📊 Problem Statement
In digital marketing, customers rarely convert after a single interaction. They may see a Facebook Ad, click an Email link, visit the Website again, and then finally make a purchase.  
Traditional attribution models often credit only one channel, which causes inaccurate budgeting decisions.

This project aims to solve this by applying **Multi-Touch Attribution Models** to identify:
- Which channels create initial awareness
- Which channels support engagement
- Which channels drive final conversion

## 🗂️ Dataset Used
**marketing_touchpoints.csv**

| Field | Description |
|------|-------------|
| Customer_ID | Unique identifier of customer |
| Touchpoint | Step in customer journey |
| Channel | Marketing channel used (e.g., Social Media, Email, Paid Ad, Website) |
| Timestamp | Date & time of interaction |
| Spend | Marketing cost for the interaction |
| Conversion_Flag | Whether customer converted (1 = Yes, 0 = No) |
| Revenue | Revenue generated per converted customer |

The dataset was **generated using Python** and then processed in **Power BI**.

## 🧠 Attribution Models Implemented
This dashboard includes:

| Model | Meaning |
|------|---------|
| **First-Touch Attribution** | Gives 100% credit to the first channel |
| **Last-Touch Attribution** | Gives 100% credit to the final converting channel |
| **Time Decay Attribution** | Channels closer to conversion get more credit |
| **U-Shaped Attribution** | First & Last touch get highest credit, middle touches shared |

These models were calculated using **DAX formulas** in Power BI.

## 🖥️ Dashboard Features
- Total Customers Reached
- Total Conversions Achieved
- Conversion Rate & Revenue Insights
- Attribution Score Comparison Across Models
- Channel Performance by Cost vs. Revenue
- Customer Journey Flow Visualization (Touchpoint Trend / Path Chart)

## 🛠 Tools & Technologies
| Tool | Use |
|-----|-----|
| **Python** | Dataset generation & preprocessing |
| **Power BI** | Dashboard design & DAX calculations |
| **DAX** | Attribution model logic |
| **CSV** | Data storage format |

## 🎯 Key Insights
- Not all channels play the same role in conversion.
- Some channels help in **awareness**, others help in **final conversion**.
- Attribution helps in **better marketing budget allocation** and **ROI improvement**.

## 📌 Conclusion
This Multi-Touch Attribution Dashboard allows businesses to:
- Understand real channel performance
- Avoid over-investing in non-effective channels
- Optimize marketing spend for **maximum conversions**

---

## 👩‍💻 Author
Rakshitha B
rakshitha.raksh.b@gmail.com
R
If you found this useful, feel free to ⭐ the repo ✨
