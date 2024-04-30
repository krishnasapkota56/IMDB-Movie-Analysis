# IMDB-Movie-Analysis
Report to answer the following questions from IMDB Movie dataset.
Clean the data:
Drop irrelevant columns, remove null values, and ensure data consistency and quality.

Movies with highest profit:
Create a new column "profit" (gross - budget) and sort movies by profit.
Plot profit vs budget to identify outliers.
Find the movies with the highest profit:
Identify movies with the highest profit based on the "profit" column.

Top 250:
Create a new column "IMDb_Top_250" for top-rated movies with IMDb ratings > 25,000 votes.
Add a "Rank" column to indicate movie rankings.
Find IMDB Top 250:
Extract movies from "IMDb_Top_250" column.

Best Directors:
Group movies by director_name.
Find top 10 directors based on the highest mean imdb_score, alphabetically sorted in case of ties.
Find the best directors:
Identify top directors based on mean imdb_score.

Popular Genres:
Analyze genres data to identify popular genres.
Find popular genres:
Determine the most popular genres based on data analysis.
Charts:
Create columns for lead actors: Meryl_Streep, Leo_Caprio, Brad_Pitt.
Combine these columns and group by actor_1_name.
Find actors with the highest mean num_critic_for_reviews and num_users_for_review.

Decades Analysis:
Create a "decade" column based on title_year.
Group movies by decade and find the sum of users voted in each decade in df_by_decade.
Find critic-favorite and audience-favorite actors:
Identify actors with the highest mean num_critic_for_reviews and num_users_for_review.
