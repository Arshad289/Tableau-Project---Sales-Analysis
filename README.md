# 📊 Interactive Tableau Sales Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-blue)

An interactive **Tableau storyboard** analyzing **271,955+ sales transactions** across 147 countries and 795 sales representatives, visualizing sales trends over 4 years (2011-2014), geographic distribution, and top performer identification.

---

## 📌 Project Highlights

| Area | Detail |
|---|---|
| **Dataset** | 271,955 transactions across 147 countries |
| **Time Period** | 2011-2014 (4 years) |
| **Sales Reps** | 795 unique representatives |
| **Visualization** | Interactive Tableau storyboard with drill-down capabilities |
| **Key Finding** | 89% sales growth from 2011 ($24.6M) to 2014 ($46.5M) |

---

## 🗂 Repository Contents

```
Tableau-Project---Sales-Analysis/
├── Sales_Dashboard.twbx          # Tableau packaged workbook
├── sales_by_rep.csv             # Source data (271,955 rows)
├── Problem_Statement.docx       # Analysis objectives & findings
└── README.md                    # This file
```

---

## 🎯 Business Questions Answered

### 1. What is the overall trend in sales over the years?
**Finding:** Strong upward trend with **89% growth** over 4 years

| Year | Total Sales | YoY Growth |
|------|-------------|------------|
| 2011 | $24.6M | - |
| 2012 | $28.8M | +17% |
| 2013 | $36.8M | +28% |
| 2014 | $46.5M | +26% |

### 2. Which countries have the highest number of sales?
**Finding:** Top 5 countries contribute **35% of global sales**

| Rank | Country | Total Sales | Share |
|------|---------|-------------|-------|
| 1 | United States | $6.9M | 8.5% |
| 2 | France | $5.8M | 7.1% |
| 3 | Australia | $5.7M | 7.0% |
| 4 | Mexico | $5.5M | 6.7% |
| 5 | Germany | $5.0M | 6.1% |

### 3. Who are the top sales representatives based on performance?
**Finding:** Top 5 reps generated **$2.6M combined** (3.2% of total sales)

| Rank | Sales Rep | Total Sales | Avg Deal Size |
|------|-----------|-------------|---------------|
| 1 | Natalie Fritzler | $572,063 | $2,108 |
| 2 | Tamara Chand | $562,644 | $2,075 |
| 3 | Art Ferguson | $507,372 | $1,871 |
| 4 | Greg Tran | $497,713 | $1,835 |
| 5 | Tom Ashbrook | $485,857 | $1,791 |

---

## 🚀 Getting Started

### Prerequisites
- **Tableau Desktop** (version 2020.1+) OR **Tableau Reader** (free)
- Download from [Tableau's website](https://www.tableau.com/products/desktop/download)

### Opening the Dashboard

1. **Download the Files:**
   ```bash
   git clone https://github.com/Arshad289/Tableau-Project---Sales-Analysis.git
   cd Tableau-Project---Sales-Analysis
   ```

2. **Open in Tableau:**
   - Double-click `Sales Dashboard.twbx`
   - OR open Tableau Desktop → File → Open → Select `Sales Dashboard.twbx`

3. **Explore the Dashboard:**
   - Navigate through the storyboard tabs
   - Use filters to drill down by year, country, or sales rep
   - Hover over visualizations for detailed tooltips

---

## 📊 Dashboard Features

### Story Tab 1: Sales Trend Analysis
- **Line chart** showing yearly sales progression
- **YoY growth indicators** with percentage changes
- **Forecast projection** for 2015 (if enabled)

### Story Tab 2: Geographic Distribution
- **Interactive world map** with bubble sizes representing sales volume
- **Country-level breakdown** with drill-down capabilities
- **Regional performance comparison** (Americas, EMEA, APAC)

### Story Tab 3: Top Sales Representatives
- **Bar chart ranking** top 20 performers
- **Individual sales rep dashboards** with deal breakdown
- **Performance metrics:** total sales, deal count, average deal size

### Story Tab 4: Comparative Analysis
- **Year-over-year comparisons** by country
- **Sales rep performance** across different regions
- **Trend analysis** with moving averages

---

## 🛠 Technical Details

### Data Source
- **File:** `sales_by_rep.csv`
- **Rows:** 271,955 transactions
- **Columns:** 6 (country, record, deal_id, sales_rep, sales, year_of_transaction_date)
- **Date Range:** January 2011 - December 2014
- **No missing values:** Complete dataset

### Tableau Features Used
- **Calculated Fields:** YoY growth %, rank calculations
- **Parameters:** Year selector, top N filter
- **Filters:** Country, sales rep, year range
- **Maps:** Geographic visualization with custom territories
- **Tooltips:** Enhanced with custom formatting
- **Storyboards:** Multi-tab narrative structure

---

## 📈 Key Insights

1. **Consistent Growth:** Sales increased every year with no decline periods
2. **US Dominance:** United States leads by a narrow margin (~3%) over France
3. **Geographic Diversity:** Sales spread across 147 countries reduces market concentration risk
4. **Top Performer Gap:** #1 rep (Natalie) outperforms #5 (Tom) by only 18%, indicating competitive balance
5. **Strong 2013-2014:** Largest absolute growth ($9.7M increase) occurred in 2013-2014

---

## 💡 Business Recommendations

Based on the analysis:

1. **Expand Top Markets:** Invest in US, France, and Australia - proven high-volume markets
2. **Replicate Success:** Study Natalie Fritzler's and Tamara Chand's strategies for training
3. **Accelerate Growth:** 2013-2014 momentum suggests market expansion opportunities
4. **Diversification:** 147-country presence provides excellent risk distribution
5. **Performance Coaching:** Narrow gap between top reps suggests leveling-up potential for all

---

## 🔄 Future Enhancements

Potential additions to this analysis:

- [ ] Product category breakdown (if data available)
- [ ] Seasonal trend analysis (monthly/quarterly)
- [ ] Sales rep performance by region
- [ ] Customer acquisition cost analysis
- [ ] Profitability metrics (if margin data available)
- [ ] Predictive analytics for 2015+ projections

---

## 🤝 Contributing

Improvements welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/enhancement`)
3. Commit changes (`git commit -m 'Add new analysis'`)
4. Push to branch (`git push origin feature/enhancement`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available for educational purposes.

---

## 👤 Author

**Arshad Ali Mohammed**
- [GitHub](https://github.com/Arshad289)
- [LinkedIn](https://www.linkedin.com/in/arshad-ali-m-080110135)
- Email: Mohammedarshadali89@gmail.com

---

## 🎓 Skills Demonstrated

This project showcases:
- ✅ **Data Analysis:** Trend identification, comparative analysis
- ✅ **Tableau Proficiency:** Storyboards, calculated fields, interactive filters
- ✅ **Business Intelligence:** KPI definition, insight generation
- ✅ **Data Visualization:** Effective chart selection, design principles
- ✅ **Communication:** Clear presentation of findings to stakeholders

---

**⭐ Star this repo if you found it helpful!**
