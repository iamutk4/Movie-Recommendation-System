# Movie Recommendation System

This project implements a movie recommendation system using machine learning techniques. The system suggests movies similar to the user's favorite movie based on textual features. The dataset used contains metadata for various movies, including titles, genres, keywords, and overview.

## Workflow Overview:

1. **Data Collection and Preprocessing:** The dataset is collected from [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download) and preprocessed to extract relevant features needed for recommendation.

2. **Feature Selection:** Important features such as movie titles, genres, and overviews are selected for building the recommendation system.

3. **Vectorization:** The selected features are vectorized using the TfidfVectorizer to convert text data into numerical representations suitable for machine learning algorithms.

4. **Similarity Calculation:** Cosine similarity scores are computed between movies based on their vectorized features. This helps in measuring the similarity between movies.

5. **Recommendation Generation:** When the user provides their favorite movie, the system compares it with all movies in the dataset using cosine similarity and recommends the top 30 most similar movies.

## Libraries Used:

- `pandas`: For data manipulation and analysis
- `difflib`: For text comparison and similarity calculation
- `sklearn`: For machine learning tasks
  - `TfidfVectorizer`: For converting text data into numerical representations
  - `cosine_similarity`: For computing cosine similarity between movies

## Dataset:

The dataset used in this project is sourced from [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download). It contains information about various movies, including titles, genres, keywords, and overviews.

## Usage:

1. Clone the repository:

```
git clone https://github.com/iamutk4/Movie-Recommendation-System.git
```

2. Navigate to project directory

   ```
   cd movie-recommendation
    ```

3. Open the Jupyter notebook Movie-Recommendation-System.ipynb using Jupyter Notebook or JupyterLab
