Movie Recommender System

description: |
  This project implements a Movie Recommender System using collaborative filtering.
  It utilizes the MovieLens dataset, and the recommendation engine is built on 
  cosine similarity between movies. The user interface is created using Streamlit.

dependencies:
  - Python 3.7 or later
  - streamlit==0.87.0
  - requests==2.26.0

setup:
  - Clone the repository
  - Install the required dependencies using `pip install -r requirements.txt`

usage:
  - Run the Streamlit app by executing `streamlit run app.py`
  - Select a movie from the dropdown menu and click 'Show Recommendation' to get movie recommendations.

files:
  - `app.py`: Main application file containing Streamlit UI code.
  - `model/movie_list.pkl`: Pickle file containing the movie list data.
  - `model/similarity.pkl`: Pickle file containing the precomputed similarity matrix.

folder_structure:
  - `model/`: Directory containing model-related files.
  - `images/`: Directory for storing movie posters fetched from the API.

note:
  - You need an API key for The Movie Database (TMDb) to fetch movie posters. 
    Obtain your API key from [TMDb](https://www.themoviedb.org/documentation/api) 
    and replace the placeholder in the `fetch_poster` function in `app.py`.

example:
  - ![Screenshot 1](screenshots/screenshot1.png)
  - ![Screenshot 2](screenshots/screenshot2.png)

author: Your Name
email: your.email@example.com
