# Movie Recommendation System using Cosine Similarity and TF-IDF Vectorizer

## 1. Project Overview

This project implements a movie recommendation system that suggests similar movies based on the content of a given movie. The system uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert movie descriptions into feature vectors and Cosine Similarity to measure the similarity between them. The goal is to recommend movies with similar plots or themes to the one a user is interested in.


## 2. Features
- **Data Preprocessing**: Text cleaning, vectorizing movie descriptions, and feature extraction using TF-IDF.
- **Similarity Calculation**: Computing Cosine Similarity between the TF-IDF vectors to find movies with the closest descriptions.
- **Recommendation System**: Based on a selected movie, the system suggests a list of similar movies.


## 3. Project Structure
    ├── movies.csv                       # Dataset file 
    ├── movie_recomentation.ipynb        # Jupyter notebook with end-to-end implementation
    ├── README.md                        # Project documentation
    ├── requirements.txt                 # Python dependencies
    └── .gitignore                       # Files to be ignored in version control

## 4. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- numpy

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/movie_recomendation.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook movie_recomendation.ipynb
```
## 5. Usage

Open the movie_recomendation.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**:  and preprocess the movie descriptions (e.g., feature selection, feature combining, etc.).
- **Vectorizing Text**: Use TfidfVectorizer to convert movie descriptions into numerical feature vectors.
- **Similarity Calculation**: Compute the pairwise Cosine Similarity between movies to find the ones most similar to the selected movie.
- **Recommendation**: Based on a user-selected movie, the system generates a ranked list of similar movies.



## 6. Exemple

**Movie input**: *The Godfather*

**Recomended Movies**:
    
1. The Godfather
2. The Godfather: Part III
3. Apocalypse Now
4. Closer
5. The Godfather: Part II
6. Mickey Blue Eyes
7. August Rush
8. Leaving Las Vegas
9. Machete

## 7. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 8. License

This project is licensed under the MIT License - see the LICENSE file for details.







