World Food Prices Analysis Using Python Libraries .

1. Project Overview
The World Food Prices Analysis is an exploratory data analysis (EDA) and data science project developed using Python in Google Colab. The project analyzes historical and current global food price trends sourced from the World Bank Food Price Dataset. Using Python libraries such as Pandas, the project inspects, cleans, and evaluates food price metrics across multiple countries, dates, and market locations. It helps track food inflation dynamics and price movements over time to provide clear macroeconomic insights.


2. Project Objectives
- To load, clean, and explore global food price data from the World Bank dataset.  
- To inspect data dimensions, schema types, missing values, and statistical summaries using Pandas.  
- To track trends in the target food price indicator (Close) across dates and geographical locations.  
- To analyze food price inflation and its variations across different country markets.  
- To examine currency distributions and their correlation with local commodity prices.  
- To build a reproducible data workflow suitable for further visualization and modeling in Python.

3. Tools & Technologies Used
- Python – Primary programming language for data analysis.  
- Google Colab – Cloud-based interactive Jupyter notebook environment for development.  
- Pandas – Data wrangling, dataframe inspection (head(), shape, info(), describe()), and manipulation.  
- Matplotlib & Seaborn – Data visualization and statistical plotting.
- CSV Dataset – Cleaned World Bank food price data file (world_food_prices_cleaned.csv).

4. Key Attributes & Features
- Country & ISO3: Identifies countries and standard ISO codes where food prices are recorded.  
- Location: Specific regional markets and points of measurement.  
- Date: Timestamp indicating the timeline of recorded food price entries.  
- Price Indicators (Open, High, Low, Close): Market metrics recording range and final price levels within reporting intervals.  
- Target Variable (Close): The final benchmark food price indicator used for core evaluation.  
- Inflation & Currency: Economic variables measuring local inflation impacts and transactional currencies.

5. Key Insights
- Data Consistency: Exploratory inspection via .shape, .info(), and .describe() confirmed the structural integrity of the cleaned dataset for cross-country comparisons.  
- Price Trend Volatility: The Close indicator shows distinct seasonal and economic spikes across different years and global regions.  
- Inflation Sensitivity: Local food commodity pricing correlates strongly with regional inflation rate increases and domestic currency fluctuations.  
- Geographic Variance: Significant divergence in food basket costs occurs between import-dependent countries and self-sufficient agricultural producers

 6. Conclusion
The World Food Prices Analysis project offers a practical, data-driven assessment of global food commodity price trends and inflation effects. By leveraging Python and Pandas within Google Colab, the raw World Bank data was successfully explored and transformed into structured analytical outputs. This project
demonstrates end-to-end competencies in data exploration, statistical summary analysis, and reproducible research workflows using the Python data science stack.

7. Skills Learned
- Data Cleaning and Exploratory Data Analysis (EDA) with Pandas  
- Notebook Automation and Development in Google Colab  
- Statistical Data Summarization (.describe(), .info(), distributions)  
- Multi-variable Economic Data Interpretation (Inflation, Currency, Food Price Indexes)  
- Version Control and Project Publishing via GitHub
