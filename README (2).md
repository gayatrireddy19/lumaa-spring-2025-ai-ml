# Movie Recommendation System (IMDB Top 1000)

## Overview
This is a **content-based recommendation system** that suggests movies based on user input.  
It uses **TF-IDF & Cosine Similarity** to compare user queries with **movie overviews & genres** and returns the **top 3-5 highest-rated IMDb movies** that match the user’s preferences.

---

## Dataset
- **Dataset Name:** `imdb_top_1000.csv`
- **Source:** [Kaggle] - https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows
- **Columns Used:**
  - **Series_Title:** Movie name
  - **Genre:** Movie genres (Action, Comedy, Horror, etc.)
  - **Overview:** Short description of the movie
  - **IMDB_Rating:** IMDb rating of the movie
  - **Similarity Score:** Computed based on user input

---
## Video Demo
- Link - https://drive.google.com/file/d/1Y9YhT89k8SWXPSx9503fnnAaVMc7ARl1/view?usp=drive_link

## Setup & Installation
- Run it in Jupyter Notebook or Google Colab
- You may want to install pandas and scikit-learn (Run the below command in your jupter notebook)
- pip install pandas scikit-learn
 
## Running
- Run the code in jupyter notebook
 
# Results

Enter your movie preferences:  I want to watch comedy movies

Top Recommendations:

| Series_Title    | Genre                    | Overview                                           |   IMDB_Rating |   similarity |
|:----------------|:-------------------------|:---------------------------------------------------|--------------:|-------------:|
| The Sting       | Comedy, Crime, Drama     | Two grifters team up to pull off the ultimate con. |           8.3 |       0.0875 |
| The Gold Rush   | Adventure, Comedy, Drama | A prospector goes to the Klondike in search of     |           8.2 |       0.0831 |
|                 |                          | gold and finds it and more.                        |               |              |
| The Circus      | Comedy, Romance          | The Tramp finds work and the girl of his dreams at |           8.1 |       0.0845 |
|                 |                          | a circus.                                          |               |              |
| The Truman Show | Comedy, Drama            | An insurance salesman discovers his whole life is  |           8.1 |       0.084  |
|                 |                          | actually a reality TV show.                        |               |              |
| Badhaai ho      | Comedy, Drama            | A man is embarrassed when he finds out his mother  |           8   |       0.1042 |
|                 |                          | is pregnant.                                       |               |              |
