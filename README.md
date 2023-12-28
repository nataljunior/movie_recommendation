# Movie Recommendation System

## Overview
This project aims to develop a movie recommendation system that provides suggestions based on user searches. It utilizes a dataset available on Kaggle containing approximately one million movie titles, overviews, languages, popularity, ratings, and other related information.

## Technique Used
The recommendation system employs the TF-IDF (Term Frequency-Inverse Document Frequency) technique. It analyzes the movie titles and overviews to generate recommendations.
TF-IDF stands for Term Frequency-Inverse Document Frequency. It is a numerical statistic used in natural language processing and information retrieval to evaluate the importance of a word in a document relative to a collection of documents or a corpus.

TF (Term Frequency) measures how frequently a term occurs in a document. It signifies the number of times a particular word appears in a document relative to the total number of words in that document. Words that occur more frequently within a specific document are deemed more important to that document.

IDF (Inverse Document Frequency) calculates the significance of a term in the entire document collection or corpus. It evaluates how rare or common a term is across multiple documents. Terms that appear frequently across many documents receive lower IDF scores, while those that are unique or rare in the corpus receive higher IDF scores.

Combining TF and IDF, TF-IDF assigns a weight to each term in a document, emphasizing terms that are frequent in the document but rare across the entire corpus. This weighting helps in identifying the relevance of a term in a specific document among a larger set of documents, commonly used in tasks like information retrieval, text mining, and content-based recommendation systems.

## Functionality
The system provides users with a table displaying five movie options based on the search query. The table includes details such as movie title, popularity, rating, and more.

## Current Status
The project has achieved satisfactory results, generating accurate movie suggestions. However, there are areas for improvement and future developments.

## Next Developments
- Optimize system performance for larger datasets (Phase 1 uses a subset of the dataset).
- Develop and enhance the user interface for better user interaction.
- When a user inputs text, it's mandatory for the input text to match precisely with the titles present in the dataset. To enhance user experience I want to implement something that can alleviate the necessity for exact title matching.
- Implement collaborative filtering algorithms to enhance recommendation accuracy (Ranking per popularity, rating or related)
- Incorporate user feedback and preferences to personalize recommendations (RLHF techniques)


## Contribution
Contributions are welcome!

## Acknowledgements
- Thanks to ASANICZKA, on Kaggle for providing the dataset used in this project, link: https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/code
- Gratitude to the open-source community for valuable resources and inspiration.

## Contact
For any inquiries or suggestions, feel free to contact me: natal_jr@hotmail.com.
