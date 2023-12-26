# Movies-recommendation-system-using-CosineSimilarity

![Capturemovie](https://github.com/Mona-Bhagat/Movies-recommendation-system-using-CosineSimilarity/assets/148805047/70cb87b9-82bf-4f8c-ae4b-4648eff2aeec)


# Project Overview
This project aims to build a Movie Suggestion system using the Cosine Similarity metric. This system can be used by firms for tailored recommendations based on user preferences which makes users more likely to engage with the platform, increasing user satisfaction and retention.

# Data Sources
The primary dataset used for this analysis is the multivariate type of dataset "movie" file. 


# Tools
	• Excel CSV
 	• Google Colab
  • Following dependencies/libraries were imported:
  * pandas
  * numpy
  * import difflib # helps get the closest match to the movie as it may have spelling mistakes
  * from sklearn.feature_extraction.text import TfidfVectorizer
  * from sklearn.metrics.pairwise import cosine_similarity
  
# Steps involved

* Import of required libraries
* import of data
* Relevant features selection from data for recommendation 
* Replacing the null values with null string
* Combining all the 5 selected featres
* Converting the text data to feature vectors
* getting the similarity scores using cosine similarity
* Getting the movie name from the user
* finding the close match for the movie name given by the user
* getting a list of similar movies


# Results
We tested our model with a couple of very famous movies such as 'Jurassic Park' and 'Harry Potter and the Chamber of Secrets'. The model build was able to good results for 'Jurassic Park' choices such as  'The Lost World: Jurassic Park' and 'ET' 
which are science fiction and adventure movies. Further, we tested it with the animated movie 'Finding Nemo' and gave recommendations such as 'Shark Tale' which is related to fish, and an animated movie; to suggesting 'John Carter' which shares the
same director as Finding Nemo 'Andrew Stanton'. One of our 5 chosen features was the director, people at times prefer to watch movies made by the same director as their favorite movie.
The complete list is below:

![Jurassic Park](https://github.com/Mona-Bhagat/Movies-recommendation-system-using-CosineSimilarity/assets/148805047/5f04a9ac-a091-425c-846e-7e283d3dfacb)          ![Finding nemo](https://github.com/Mona-Bhagat/Movies-recommendation-system-using-CosineSimilarity/assets/148805047/1f72b68a-1800-4d67-bb3b-af38898fd3bc)



