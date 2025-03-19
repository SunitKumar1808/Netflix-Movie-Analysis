# Netflix Movie Data Analysis using Jupyter Notebook & Tableau
## Project Overview
Netflix is one of the world's largest streaming platforms, offering a vast collection of movies and TV shows across various genres, languages, and regions. Understanding content trends, audience engagement, and regional preferences is crucial for improving content recommendations and business decisions.

This project aims to analyze Netflix’s movie dataset using Jupyter Notebook for data processing and exploratory analysis and Tableau for interactive visualizations. The analysis focuses on identifying patterns in movie genres, release trends, country-wise distribution, movie duration, and content ratings to gain insights into Netflix’s content strategy.

## Objectives of the Analysis
The key objectives of this Netflix movie data analysis are:

Understanding Popular Genres – Identifying the most frequent movie genres.
Analyzing Release Trends – Observing how Netflix’s movie collection has evolved over time.
Exploring Country-Wise Contributions – Identifying the top countries contributing to Netflix’s movie library.
Movie Duration Analysis – Examining typical movie lengths and their impact.
Content Ratings Breakdown – Understanding the distribution of movies based on age classification.
By leveraging Python libraries like Pandas, Matplotlib, and Seaborn for data cleaning and exploratory data analysis (EDA) in Jupyter Notebook and Tableau for visualization, this project provides deep insights into Netflix's content trends.

Data Cleaning and Processing (Jupyter Notebook)
The dataset used in this analysis contains key attributes such as Movie Title, Genre, Release Year, Country, Duration, and Rating.

Data Preprocessing Steps in Jupyter Notebook
Loading the dataset and inspecting missing values.
Filtering only movies (excluding TV shows).
Handling missing values in important columns such as country and rating.
Converting movie duration to numerical format for better analysis.
Extracting the year from the ‘Date Added’ column to analyze trends over time.
Exporting the cleaned dataset for visualization in Tableau.
Visualizations & Graphs Used in the Analysis
1. Genre Popularity - Bar Chart
A bar chart is used to visualize the top 10 most popular movie genres on Netflix. The chart helps identify which genres dominate the platform and whether there are underrepresented categories.

# ✔ Insights:

Drama and Comedy are the most frequent genres in Netflix’s library.
Thrillers and Documentaries are also prominent, while genres like Horror are relatively fewer.
2. Yearly Growth of Netflix Movies - Line Chart
A line chart is used to track the number of movies added to Netflix over the years. This graph helps analyze trends in content expansion.

# ✔ Insights:

The number of movies on Netflix has increased significantly since 2015.
More movies are being added each year, indicating a growing content strategy.
3. Country Contribution - Horizontal Bar Chart
A horizontal bar chart is used to display the top 10 countries producing Netflix movies. This visualization provides insights into the global distribution of Netflix’s content.

# ✔ Insights:

The USA leads in movie production, followed by India and the UK.
Netflix has a strong presence in international markets, with significant content from Canada, Spain, and France.
4. Movie Duration Distribution - Histogram
A histogram is used to analyze the distribution of movie durations on Netflix. This helps understand the typical length of movies available on the platform.

# ✔ Insights:

Most Netflix movies range between 80 to 120 minutes, suggesting that viewers prefer standard movie lengths.
Short films (under 60 minutes) and extremely long movies (above 180 minutes) are rare.
5. Content Ratings Breakdown - Pie Chart
A pie chart is used to display the proportion of movies based on their content rating (e.g., PG-13, TV-MA, R). This helps understand the audience demographics targeted by Netflix.

# ✔ Insights:

TV-MA (Mature Audiences) is the most frequent rating, indicating that Netflix focuses heavily on adult content.
PG-13 and TV-14 ratings are also common, suggesting that Netflix targets both teenagers and general audiences.
Interactive Visualizations in Tableau
After performing the exploratory data analysis in Jupyter Notebook, the cleaned dataset is used to create interactive dashboards in Tableau. These visualizations allow users to explore genre trends, release trends, country-wise distributions, duration patterns, and ratings breakdowns dynamically.

# Tableau Dashboards & Visualizations
Genre Popularity Dashboard – A bar chart with filters to explore movie genres over time.
Yearly Growth Line Chart – An interactive timeline showing Netflix’s content expansion.
Country-Wise Contribution Heatmap – A world map visualizing content origin.
Content Ratings Breakdown – A pie chart displaying the percentage of movies in different rating categories.
Interactive Movie Duration Histogram – Allows users to filter movies based on their duration preferences.
By using filters and dynamic views, users can interactively explore Netflix’s content trends based on their areas of interest.

# Conclusion & Business Insights
## Key Takeaways from the Analysis:
📌 Netflix’s movie collection has grown significantly since 2015, with an increasing number of movies added every year.
📌 Drama and Comedy dominate Netflix’s content, making them the most preferred genres.
📌 The USA, India, and the UK contribute the most movies, highlighting Netflix’s stronghold in these regions.
📌 Most Netflix movies are between 80-120 minutes long, aligning with standard movie durations preferred by audiences.
📌 TV-MA content is the most frequent rating, indicating Netflix’s focus on mature audiences.

## Business Implications for Netflix:
📌 Content Strategy: Investing more in high-performing genres like Drama and Comedy can boost engagement.
📌 Regional Focus: Expanding localized content in emerging markets can attract more subscribers.
📌 Movie Length Optimization: Netflix should focus on producing movies under 2 hours, as they are preferred by most viewers.
📌 Age-Based Targeting: Since TV-MA is dominant, Netflix can refine its marketing strategies for adult audiences while ensuring family-friendly content availability.

