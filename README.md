# movie-recommender-system-tmdb-dataset
**Overview**

This project is a Movie Recommendation System that uses content-based filtering and machine learning to provide personalized movie recommendations. The system is designed to analyze various attributes of movies and user data to suggest films that match individual user preferences.

**Features**

Personalized Recommendations: Suggests movies based on user preferences and past interactions.
Content-Based Filtering: Uses movie metadata to find similar movies.
Interactive Web Interface: Allows users to input their preferences and view recommendations through a user-friendly web application.

**Tools and Technologies**

Python: The primary programming language used for development.
Jupyter Notebook: For developing and experimenting with machine learning models.
Pandas: For data manipulation and analysis.
Scikit-learn: Implementing machine learning algorithms for the recommendation engine.
Streamlit: Creating an interactive web interface for users.

**How It Works**

Data Collection: The system collects data on various movie attributes such as genre, director, cast, and plot.
Model Training: Using Scikit-learn, the system trains a model based on these attributes to learn similarities between different movies.
User Input: Users input their movie preferences via the Streamlit web interface.
Recommendation Generation: The system uses the trained model to generate and display a list of recommended movies that match the user’s preferences.

**Usage**

Open the Streamlit web interface.
Select or type in your favorite movie.
Click on the "Show Recommendation" button.
View the recommended movies along with their posters.
