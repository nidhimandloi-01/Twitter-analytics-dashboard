# Twitter Social Media Analytics Dashboard 🐦📊

An interactive Power BI dashboard that analyzes Twitter (X) social media performance — tracking impressions, engagement, likes, retweets, and clicks over time to surface trends in content performance.

## 📌 Overview

This project turns raw Twitter activity data into a single-page, decision-ready dashboard. It's built to help a social media / marketing team quickly answer:

- How is content performing week over week?
- What's driving engagement — media, hashtags, links, or profile visits?
- Which weeks/months saw spikes or dips in activity?

## 🖼️ Dashboard Preview

<img width="903" height="510" alt="Screenshot 2026-07-25 215617" src="https://github.com/user-attachments/assets/67101bc3-1433-4b18-b5cc-9fd46c53caec" />


## 🔑 Key Features

**KPI Cards**
- Total Media Views
- Average Engagement Rate
- Total Impressions
- Total Tweet Count

**Gauges**
- Likes (against target)
- Retweets (against target)

**Charts**
- Tweet Count by Week (line chart)
- Impressions by Week (line chart)
- URL Clicks by Tweet (clustered bar chart)
- Hashtag, URL & Profile Clicks breakdown (pie chart)
- Media Engagement vs. Media Views by Week (clustered column chart)
- Tweet Count by Week (clustered column chart)

**Interactivity**
- Month slicer to filter the entire report by `MonthName`
- Cross-filtering across all visuals

## 🗂️ Data Model

The report runs on a single flat table, **SocialMedia**, with the following fields:

| Column | Description |
|---|---|
| `Tweet` | Individual tweet identifier/text |
| `WeekDay` | Day of week the tweet was posted |
| `MonthName` | Month of the tweet (used for slicer filtering) |
| `impressions` | Number of times the tweet was seen |
| `engagement rate` | Engagement rate for the tweet |
| `likes` | Number of likes |
| `retweets` | Number of retweets |
| `media views` | Number of media views |
| `media engagements` | Number of media engagements |
| `hashtag clicks` | Clicks on hashtags |
| `url clicks` | Clicks on links |
| `user profile clicks` | Clicks through to the user's profile |

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — data modeling, DAX aggregations, report design
- **DAX** — Sum/Average/Count aggregations powering KPI cards and gauges
- **Data Visualization** — line charts, clustered bar/column charts, pie chart, gauges, slicers
- **Data Storytelling** — layout designed to move from high-level KPIs to weekly trends to channel-level breakdowns

## 🚀 How to Use

1. Clone or download this repository
2. Open `Twitter_project.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Use the **Month slicer** to filter data by month
4. Hover over any visual for tooltip details, or click a data point to cross-filter the rest of the report

## 📁 Repository Contents

```
├── Twitter_project.pbix   # Power BI report file
└── README.md              # Project documentation
```

## 👤 Author

**Nidhi Mandloi**
Data Analyst | SQL • Excel • Power BI • Tableau
- GitHub: [nidhimandloi-01](https://github.com/nidhimandloi-01)

---
*This project is part of a broader data analytics portfolio built to demonstrate BI dashboarding and data storytelling skills.*
