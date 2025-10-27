Project Valuation Analysis Report

1. Introduction
The purpose of this project is to analyze the valuation trends of unicorn companies (startups valued at $1 billion or more). The dataset includes company name, valuation (in billions), date joined, country, city, industry, and key investors.

Our main goal is to answer critical questions such as:
- Which companies have the highest valuations?
- When did these companies become unicorns?
- Which countries, cities, and industries dominate the unicorn space?
- Who are the key investors backing these high-value companies?
- What is the growth trend of unicorns over time?
- Which young companies are achieving high valuations quickly?

This analysis helps understand where innovation is booming, who is funding it, and which sectors are attracting the most capital.

2. Data Preparation & Cleaning
- Before analysis, we performed the following data cleaning steps in Python (pandas):
- Converted “Valuation ($B)” to numeric by removing $ and B and converting to float.
- Converted “Date Joined” to datetime format for time-series analysis.
- Created a combined “Location” column as City, Country for easy mapping (but kept “City” and “Country” separate for grouping).
- Checked for missing values — none were significant enough to impact results.

3. Exploratory Data Analysis (EDA)
Q1. Highest Valuation Projects
Answer:
Top 3 highest-valued companies are:
- ByteDance – $140B
- SpaceX – $127B
- SHEIN – $100B
📊 These three companies alone represent a significant share of global unicorn valuation.

Q2. Earliest vs Latest Joined Projects
- Earliest unicorn: Veepee – joined on 2 July 2007
- Latest unicorn: Tridge – joined on 24 August 2022
⏳ This shows the dataset spans over 15 years of unicorn creation, allowing trend analysis over time.

Q3. Highest-Valued Projects by Country and City
Top 3 countries:
- China
- United States
- Australia
Top 3 cities:
- Beijing
- Hawthorne
- Shenzhen
🌎 China and the U.S. clearly dominate the unicorn ecosystem, both in terms of number and valuation.

Q4. Industries of the Highest-Valued Projects
Top industries by total valuation are:
- Artificial Intelligence
- Other (diverse sectors)
- E-commerce & Direct-to-Consumer
💡 AI leads in valuation, reflecting global focus on machine learning and data-driven businesses.

Q5. Key Investors in Highest-Valued Projects
- ByteDance: Sequoia Capital China, SIG Asia Investments, SoftBank
- SpaceX: Founders Fund, Draper Fisher Jurvetson, Rothen…
- SHEIN: Tiger Global Management, Sequoia Capital China…
💰 Sequoia Capital is a recurring name — one of the most influential unicorn investors globally.

Q6. Growth Trend: Count of Unicorns by Year
📈 A line chart shows a sharp increase in unicorn creation after 2015, peaking in 2020–2021.
This indicates strong investor interest and rapid startup growth in recent years.

Q7. Youngest Projects with High Valuation
- Miro – $17.50B, joined 5 January 2022
🚀 Miro is a fast-scaling SaaS company showing how quickly valuations can rise with product-market fit.

Q8. Average Valuation by Country & Industry
- Highest average by country: China
- Highest average by industry: Artificial Intelligence
📊 This indicates that Chinese unicorns and AI companies, on average, achieve higher valuations than their global peers.

4. Limitations
- Limited dataset: Covers only unicorns (not all startups).
- No revenue/funding data: Couldn’t compare valuation with actual financial performance.
- Industry granularity: Some companies are categorized as “Other,” limiting deep sector analysis.

5. Recommendations
- Collect funding & revenue data to compare valuation vs actual business performance.
- Segment data by unicorn stage (early, mid, late) for deeper insights.
- Expand dataset to include more countries & years for long-term trend analysis.

6. Conclusion
This project provided a detailed look into unicorn company valuations worldwide.
Key takeaways:
- ByteDance, SpaceX, and SHEIN are the highest-valued unicorns.
- China and the U.S. dominate the unicorn landscape.
- AI and e-commerce sectors attract the most valuation.
- Unicorn creation has grown exponentially in the last decade.
Overall, unicorns remain a critical driver of innovation and investment, shaping the future of global markets.
