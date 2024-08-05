Movie Recommendation System

Overview
This project is a Movie Recommendation System designed to suggest movies to users based on their viewing history and preferences. The system analyzes user ratings and genres of previously watched movies to generate personalized recommendations. It utilizes a combination of data processing, genre analysis, and rating patterns to recommend movies that align with users' interests.

Features
User-Based Recommendations: Recommends movies based on the user's rating history.
Genre Analysis: Prioritizes movies from genres that the user frequently watches.
Top-Rated Movies: Suggests highly rated movies within the user's preferred genres.
Data Visualization: Visualizes the distribution of user's watched genres.

Technologies Used
Python: For data processing and analysis.
Pandas & NumPy: For data manipulation and numerical operations.
Matplotlib: For visualizing genre distribution.
CSV Files: For storing movie and rating data.

How It Works
Data Collection: The system collects user ratings and movie metadata, including genres.
Data Processing: It preprocesses the data by merging movie and rating datasets and converting necessary columns.
Genre Analysis: The system identifies the most-watched genres based on the user's rating history.
Recommendation Generation: It generates a list of recommended movies by selecting top-rated movies from the user's favorite genres.
Visualization: The system visualizes the user's genre preferences using pie charts.

Usage
To use the Movie Recommendation System:

Ensure you have the necessary CSV files (movies.csv and ratings.csv) in the correct directory.
Run the Python script and enter the user ID when prompted.
The system will display a pie chart of the user's watched genres and provide three movie recommendations.

Contributing
Contributions are welcome! If you'd like to improve the recommendation algorithm or add new features, please fork the repository and submit a pull request.
