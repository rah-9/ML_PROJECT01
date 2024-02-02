# Movie Recommendation System

## Overview

This project implements a movie recommendation system using Natural Language Processing (NLP) techniques. The system analyzes movie descriptions and genres to provide personalized recommendations based on user preferences.

## Code Structure

The project is structured as follows:

- `Moviedataset.csv`: Dataset containing information about movies.
- `movie_prediction_model.py`: Python script containing the machine learning model for movie recommendations.
- `movie_list.pkl`: Pickle file storing the processed movie information.


## Requirements

- Python 3.x
- pandas
- scikit-learn

Install the required packages using:

```bash
pip install pandas scikit-learn
```
## Running model 

To run the movie_prediction_model.ipynb use Anaconda or Google Colab in your computer

## Files

- `Moviedataset.csv`: Raw dataset with movie information.
- `movie_list.pkl`: Processed movie information for recommendation..
- `README.md`: Project documentation.
- 
## Acknowledgments

- This project uses the CountVectorizer and cosine_similarity modules from scikit-learn for text processing and similarity calculations.
The dataset used is a sample movie dataset.
- Use the recommand() function to get movie recommendations: