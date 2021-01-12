# 4. EU Life Quality Data 

This project explores the quality of life across various European countries by comparing countries across various indicators such as GDP, unemployment, underemployment, median income, pollution, average hours worked, percentage of population with low savings, crime, job satisfaction rates, life satisfaction rates and trust in the police, legal system and politics.

The data was drawn from the Eurostat database: https://ec.europa.eu/eurostat/data/database which contains a wide range of statistical data about the EU.

Each of the 18 tables in the database analysed here explores one of the above indicators across 31 EU countries.

The challenge in this project was to: 
1) join all or some of tables to compare countries' performance; and 
2) draw interesting insights and conclude which EU country might have the best quality of life overall based on different indicators.

This project demonstrates the following key data analysis techniques: 

1. import data from a Postgres databse into python for analysis with pandas;
2. use the SQLAlchemy python toolkit to pass data from csv files onto the Postgres database;
3. query the Postgres database with Python's pandas and SQL;
4. advanced querying with SQL using joins, filtering, basic subqueries, aggregate functions, correlated and nested subqueries;
5. perform exploratory data analysis;
6. visualise data using matplotlib & seaborn (with bar charts, scatter plots, regplots, lmplots & pair plots);and
7. use Tableau to visualise data and gain key insights.
