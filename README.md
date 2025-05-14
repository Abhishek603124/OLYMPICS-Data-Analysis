🏅 Olympic Medal Analysis
This project performs data analysis on Olympic Games athletes and medal distribution using the Athlete Events and NOC Regions datasets. It explores medal tallies across countries and over time using Python, pandas, seaborn, and plotly.

📁 Dataset Used
athlete_events.csv: Contains data on athletes, their demographic details, sports, events, and medals.

noc_regions.csv: Maps National Olympic Committee (NOC) codes to regions.

📊 Key Steps and Analysis
1. Data Loading and Cleaning
Loaded both datasets using pandas.

Filtered data for Summer Olympics only.

Merged region information with athlete data using NOC codes.

Removed duplicate entries.

2. Feature Engineering
Created dummy variables for medals (Gold, Silver, Bronze).

Aggregated medal data using groupby operations for comprehensive analysis.

3. Medal Tally Calculation
Generated a sorted medal tally by country using groupby aggregation.

Calculated the total medals won by each country.

Created a custom function fetch_medal_tally(year, country) to retrieve medal data for specific years and countries.

4. Exploratory Data Analysis (EDA)
Used .unique().shape to explore diversity in:

Countries (NOC)

Sports

Events

Athlete ages

Tracked the number of participating nations over time.

5. Data Visualization
Used Plotly Express to create an interactive line chart of countries participating per edition.

Used Seaborn and Matplotlib for further visual exploration (code snippet incomplete).
