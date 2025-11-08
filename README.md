📈 Tech Sector Volatility & Correlation Analysis 

An interactive dashboard and Python-based analysis project to explore the performance, risk, and relationships of major technology stocks. This project showcases the ability to process time-series data from an API, calculate key financial metrics, and present findings in a dynamic, business-oriented visualization. 

🎯 The Business Problem 

How can an investor or portfolio manager quickly understand the risk and return profile of major tech stocks? Which stocks tend to move together, and how has their volatility changed over time? This dashboard provides a tool to answer these questions, enabling more informed investment decisions. 
📊 Data Source 

     Source: Yahoo Finance API
     Tool: yfinance library in Python
     Tickers Analyzed: Apple (AAPL), Google (GOOGL), Microsoft (MSFT), Amazon (AMZN)
     Date Range: January 1, 2018, to present.
     
 
🔍 Key Findings & Insights 

This analysis of major technology stocks reveals several critical patterns regarding risk, return, and market interdependence. The interactive dashboard was instrumental in uncovering the following insights: 

     

    High Sector-Wide Correlation Limits Diversification: The correlation heatmap shows a strong positive relationship (correlation > 0.80) between Apple (AAPL) and Microsoft (MSFT). This indicates that their stock prices tend to move in tandem, suggesting that holding both may offer limited diversification benefits within a portfolio, as they are exposed to similar market risks. 
     

    Volatility Spikes Align with Macroeconomic Events: The volatility analysis chart clearly shows that all four stocks experienced a dramatic spike in volatility during early 2020 (COVID-19 pandemic) and again throughout 2022 (inflation and interest rate hikes). This demonstrates that even the largest tech companies are not immune to broad market fear and uncertainty. 
     

    Divergent Year-to-Date Performance: While often grouped together, the YTD Return KPIs highlight that not all tech stocks are created equal. In recent periods, one stock may significantly outperform its peers (e.g., NVIDIA's surge in 2023), while others lag. This underscores the importance of individual stock analysis over blind sector investing. 
     

    Amazon Dominates in Trading Volume: The "Average Daily Volume" KPI consistently shows Amazon (AMZN) as the most heavily traded stock among the group. This high volume signifies greater liquidity, meaning shares can be bought or sold quickly without significantly impacting the stock price, a key consideration for active traders. 
     

    Moving Averages Signal Momentum: By overlaying the 50-day and 200-day moving averages, the dashboard can be used to identify key technical signals. For instance, when the 50-day MA crosses above the 200-day MA (a "Golden Cross"), it often signals the beginning of an upward price trend, which was observed for several stocks in late 2022 and early 2023. 
     
     

🎨 Interactive Dashboard 

The core of this project is an interactive Tableau Public dashboard. It allows users to filter by stock and date range to explore trends, volatility, and correlations dynamically. 

### 👉 [View the Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/bilal.nawaz4989/viz/Stockpricevolatilityandcorrealtionalanalysis/TechStockPerformanceDashboard)

<div class='tableauPlaceholder' id='viz1762578490360' style='position: relative'><noscript><a href='#'><img alt='Tech Stock Performance Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;Stockpricevolatilityandcorrealtionalanalysis&#47;TechStockPerformanceDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Stockpricevolatilityandcorrealtionalanalysis&#47;TechStockPerformanceDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;Stockpricevolatilityandcorrealtionalanalysis&#47;TechStockPerformanceDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
