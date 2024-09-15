# Netflix_recommendation
This project aims to create a recommendation system for Netflix shows and movies based on content similarity. 

# Table of contents
**Project Objective**  
To help users discover new shows and movies that are similar to ones they already enjoy.

**Methods Used**  
The project uses the following techniques:
o Data Cleaning: To preprocess and handle missing or inconsistent data.
o Similarity Calculation: Uses cosine similarity to find and rank shows or movies similar to a given title.
Recommendation Function: Recommends top 10 similar movies based on user input.

**Technologies Utilized**  
o Python  
o Pandas  
o NumPy  
o Scikit-learn  
o Natural Language Toolkit (NLTK

**Project Description**  
The dataset contains various Netflix shows and movies along with metadata such as:  
o Show Id: Unique identifier for the show/movie.  
o Title: The title of the show or movie.  
o Description: A brief summary of the content.  
o Genres: Genre tags associated with the content.  
o Director: The director(s) of the show or movie.  
o Genres: Genre tags associated with the content.  
o Cast: The main actors or actresses featured in the show or movie.  
o Director: The director(s) of the show or movie.  
o Production Country: The country where the show or movie was produced.  
o Release Date: The date the show or movie was originally released.  
o Rating: The viewer rating (e.g., TV-MA, TV-14).  
o Duration: The length of the show or movie.  
o IMDb Score: The IMDb rating for the show or movie.  
o Content Type: Indicates whether the entry is a movie or TV show.  
o Date Added: The date the show or movie was added to Netflix.

**Key Functions**  
o Data Preparation: Involved preprocessing and cleaning the text for further analysis.  
o Cosine Similarity: A core function that measures similarity between shows based on textual features.  
o Recommendation System: A function that suggests similar content based on a selected show or movie title.  

This recommendation system can serve as a foundation for further improvement, such as incorporating user ratings or personalized filtering.
