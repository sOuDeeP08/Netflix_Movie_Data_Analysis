Netflix Movie Data Analysis Project

📌 Project Overview
This project performs an exploratory data analysis (EDA) on a dataset of approximately 9,000+ movies to uncover trends in popularity, genres, and ratings. By leveraging Python's data science stack, the project transforms raw movie metadata into actionable business insights regarding content trends and audience preferences.

📊 Dataset Description
The dataset used is mymoviedb.csv, which contains information about movies including:

Release_Date: The date the movie was released.
Title: The name of the movie.
Popularity: A metric representing the movie's current trendiness.
Vote_Count/Vote_Average: User ratings and the number of votes received.
Genre: Category of the movie (Action, Drama, etc.).

🛠️ Tech Stack
Language: Python
Libraries: - Pandas: Data manipulation and cleaning.
NumPy: Numerical operations.
Matplotlib & Seaborn: Data visualization.

⚙️ Data Workflow
Data Cleaning: - Handled date formatting to extract release years.
Dropped irrelevant columns for this specific analysis (Overview, Original_Language, Poster_Url).
Verified no missing values or duplicate records existed.

Feature Engineering:
Categorization: Created a Vote_Average category (popular, average, below_average, not_popular) using quartile-based splitting.
Genre Expansion: Cleaned and "exploded" the Genre column to allow for individual analysis of multi-genre movies.

Exploratory Data Analysis:

Visualized the distribution of movie genres.
Analyzed popularity trends across different years.
Identified top-performing content.

📈 Key Insights & Conclusions

Based on the analysis, here are the primary findings:
Most Frequent Genre: Drama is the most frequent genre in the dataset, appearing in more than 14% of the entries.
Audience Ratings: Approximately 25.5% of the movies in the dataset are classified as "Popular" based on their vote averages.
Popularity Peak: Spider-Man: No Way Home holds the highest popularity score in the dataset.
Production Trends: 2020 was identified as the year with the highest number of filmed movies in this dataset.
Genre & Popularity: While Drama is the most frequent, Action, Adventure, and Sci-Fi dominate the top spots for high-popularity metrics.

🚀 How to Run
Clone the repository:
git clone https://github.com/yourusername/your-repo-name.git

Install dependencies:
pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook:
jupyter notebook "Netflix Movie Data Analysis Project.ipynb"


🎨 Visualizations Included
The project includes several plots to support the analysis:
Genre Distribution Countplot: Shows the volume of movies per category.
Vote Average Distribution: Categorical breakdown of user satisfaction.
Release Year Histogram: Visualizes the growth of movie production over time.
