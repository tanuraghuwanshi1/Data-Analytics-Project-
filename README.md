📘 Website Analytics and Conversion Rate Optimization
📖 PROJECT OVERVIEW

This project analyzes e-commerce website data to understand user behavior, traffic sources, and purchase patterns. Using SQL, Power BI, Excel, and Python, the goal is to uncover drop-offs in the conversion funnel and provide data-driven recommendations to improve conversion rates and support business decision-making.
📝 PROBLEM STSTEMENT

ClickWave, a mid-sized e-commerce company, is experiencing high website traffic but low conversions. Despite attracting visitors, the conversion funnel is underperforming due to:

    📉 High bounce rates on product pages

    🛒 Poor user experience during checkout

    🎯 Traffic sources misaligned with user intent

The company needs to analyze user traffic behavior (pageviews, sessions, bounce rates, user flow, and device types) to:

    Explore and clean the website traffic dataset
    Identify user behaviour patterns and bounce points
    Visualize conversion funnels using Power BI
    Segment users by device, source, or region

🛠️ TOOLS & TECHNOLOGIES USED :

    Excel → (Performed Data Cleaning, Data Validation and Checked Data Integrity)

    Python → (Analyzed User behavior, Bounce Rate, Funnel Count, Session Revenue and Drop-offs in Conversion)

    SQL → (Analyzed user segmentation, funnel drop-offs, and bounce patterns to uncover mobile conversion gaps)

    Power BI → ( Interactive dashboards for funnel visualization, user flow, and KPI tracking)

📂 DATASET OVERVIEW

👥 Users Table : users.csv

    Purpose: Stores information about website visitors.

⏳Sessions Table : sessions.csv

    Purpose: Tracks user visits (sessions) to the website.

🎯 Events Table : events1.xlsx

    Purpose: Stores user actions during sessions.

🛒 Items Table : items.csv

    Purpose: Contains product catalog details.

📜 DATA PREPARATION - EDA (EXCEL) :

✔️ Used Power Query for cleaning, validation, and type checks

✔️ Built pivot tables and cross-verified SQL vs Power BI outputs for accuracy

✔️ Ensured data consistency across tools
🐍 FUNNEL ANALYTICS (PYTHON) :

✔️ Analyzed session-level event data in Python to measure user behavior, segment by device and traffic source, and model funnel stages—revealing bounce rate, session revenue, and key drop-offs in conversion performance

✔️ Visualizations :

    Funnel Chart (Vertical Bar Chart): Displayed drop-offs at each stage of the purchase journey

funnel_counts_nb

    Top 10 Items by Revenue (Horizontal Bar Chart): Ranked products by total revenue contribution

top_items_by_revenue

    Conversion Rate by Device (Vertical Bar Chart): Compared conversion performance across desktop, mobile, and tablet segments

conversion_rate_by_device
🛢️ USER SEGMENTATION ANALYSIS (SQL) :

✔️ Analyzed user segmentation, funnel drop-offs, and bounce patterns to uncover mobile conversion gaps.

    User Segmentation
    Conversion Funnel Analysis

✔️ Identified loyal desktop users driving session revenue and high-LTV behaviors through funnel and session-level metrics.

    Bounce Rate Analysis
    Session Revenue

📊 DASHBOARD DESIGN (Power BI) :

✔️ Built a dynamic dashboard titled “Funnel & User Flow Dashboard” to track key performance metrics:

    ➡️ Users: 36491M

    ➡️ Sessions: 18K

    ➡️ Events: 754K

    ➡️ Conversions: 17.9K

✔️ Visualized conversion rate, bounce rate, funnel flow, and user journey using donut, Horizontal bar, funnel, and vertical bar charts.
Screenshot 2025-09-30 223507
⚡ PROJECT FLOW & STRUCTURE

 📁Website_Analytics_and_Conversion_Rate_Optimization/
  │ 
  ├── 📁 Data/                         # Raw datasets
  │    ├── users.csv                      # User details
  │    ├── sessions.csv                   # Website sessions
  │    ├── events1.xlsx                   # User events (page views, clicks, cart, etc.)
  │    └── items.csv                      # Product/item details
  │
  ├── 📁 Excel/                        # Data Preprocessing
  │    └── data_cleaning                  # Data preprocessing & cleaning
  │ 
  ├── 📁 Python/                       # Python scripts & notebooks
  │    ├── PROJECT C PYTHON FILE.ipynb    # Funnel conversion analysis
  │    └── visualization                  # Charts (matplotlib / plotly)
  │ 
  ├── 📁 SQL/                          # SQL scripts
  │    └── PROJECT C SQL FILE.sql          # Queries for funnel, drop-off, and conversion analysis
  │
  ├── 📁 Power BI/                     # Power BI dashboards
  │    └── PROJECT C DASHBOARD.pbix        # Interactive visualization & KPIs
  │
  └── README.md                         # Project documentation
