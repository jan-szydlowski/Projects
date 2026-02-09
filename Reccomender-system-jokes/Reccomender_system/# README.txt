# Jester Joke Recommender System

This project is a **Recommender System** implemented in a Jupyter Notebook (`.ipynb`). It is designed to predict and suggest jokes that a user is likely to enjoy based on their personal preferences.

## How it Works
The system is built using the **Collaborative Filtering** method. Instead of analyzing the text of the jokes, the algorithm finds patterns and similarities between different users' ratings to provide personalized recommendations.

### Getting Started
1. **Initial Profile:** When you run the notebook, you will be prompted to answer **10 questions** (rating 10 random jokes).
2. **Analysis:** Based on these ratings, the system creates a profile for you.
3. **Recommendation:** The recommender system then selects and displays a joke that best matches your sense of humor.

## Improving Accuracy
If you would like to increase the precision of the recommendations, you can increase the number of jokes you rate at the beginning:
* Open the notebook and locate the `user_vector()` function.
* Inside this function, there is a **clearly marked section** where you can change the number of jokes to be evaluated.
* Rating more jokes provides the system with more data, leading to better results.

## Data Source & Disclaimer
The jokes used in this project are sourced from the [Jester Collaborative Filtering Dataset](https://www.kaggle.com/datasets/aakaashjois/jester-collaborative-filtering-dataset).

> **Disclaimer:** These jokes are included strictly for humorous and educational purposes. They do not reflect the views or opinions of the developer. No offense is intended toward any individual or group.

---
**File Format:** `.ipynb` (Jupyter Notebook)