# Olympic Games Performance Analysis (Post-1992)

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Olympic Games dataset, focusing on participation trends, medal performance, gender representation, and country-wise efficiency — all filtered for games held after 1992.  
Using powerful visual storytelling, this study aims to understand how countries perform, where gaps exist, and how strategic focus can improve outcomes in future Olympics.

---

## Objective

- Analyze how athlete participation relates to medal wins across countries and sports.
- Examine gender trends and representation in Olympic events.
- Identify high-efficiency sports and countries based on historical medal performance.
- Explore inconsistencies in country participation and sport inclusion over time.
- Compare performance patterns across sports, genders, and nations.
- Develop insights to inform strategic planning for future Olympic participation and medal-winning strategies.

---

## Key Visualizations

- **Dumbbell Chart**  
  Highlights the significant disparity between athlete participation and medal achievements among countries. Reveals performance gaps and medal inefficiency.
- **Violin Plot**  
  Identifies countries that underperform or lack consistency in either the Summer or Winter Games, based on participation distribution.
- **Line Chart**  
  Tracks whether a country's medal tally has been improving or deteriorating over time, and whether a sport shows consistent growth or decline.
- **Area Chart**  
  Shows male vs female participation trends across years, visualizing progress toward gender balance.
- **Stacked Bar Chart**  
  Demonstrates how certain sports are heavily dominated by a few countries, while others show more balanced competition.

---

## Summary Insights

- Countries like **Mexico** and **Czech Republic** demonstrate high medal efficiency with fewer participants.
- Sports such as **Canoeing** (Summer) and **Nordic Combined** (Winter) show signs of decline.
- **Female participation** has increased post-1992, though medal efficiency varies across regions.
- **Athletics** and **Swimming** consistently dominate the overall medal count.
- Several countries, especially in the **Winter Games**, display irregular participation trends.
- Nations like the **United States** and **Norway** have shown consistent improvement in medal performance over time.

---

## Dataset Information

The analysis is based on a historical Olympic Games dataset from Kaggle, covering all modern Games from **1896 to 2016**.  
To ensure relevance and consistency, the analysis is limited to entries **from 1992 onward**.

- Each row represents one athlete’s participation in a specific event.
- Key fields include: `Name`, `Sex`, `NOC`, `Year`, `Season`, `Sport`, `Event`, `Medal`.
- Filtered for modern structure, gender tracking, and accurate event mapping.

📎 **Source**: [Kaggle – 120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

---

## Tools & Technologies

- Python 3.x
- Google Colab (Cloud-based Jupyter environment)
- Libraries used:
  - `pandas`
  - `matplotlib`
  - `seaborn`
