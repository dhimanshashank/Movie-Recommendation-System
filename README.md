# Movie Recommendation System

**Description**: This project is a movie recommendation system that suggests movies to users based on user inputs and provide the top 5 recommendations for the given input. It includes a Streamlit web application and a Jupyter Notebook with the core recommendation logic.

## Introduction

This project provides personalized movie recommendations using machine learning algorithms. It consists of a Streamlit web application for user interaction and a Jupyter Notebook for developing and testing the recommendation algorithms.

## Files

- `app.py`: Streamlit web application.
- `Movie-recommendation-system.ipynb`: Jupyter Notebook with recommendation logic.
- `movies_dict.pkl`: Pickled dictionary of movie data.
- `requirements.txt`: Python dependencies.
- `setup.sh`: Shell script to set up the project environment.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/movie-recommendation-system.git
    cd movie-recommendation-system
    ```
2. Run the setup script:
    ```sh
    bash setup.sh
    ```
   Alternatively:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

## Usage

1. Start the Streamlit web application:
    ```sh
    streamlit run app.py
    ```
   Open your browser and go to the provided URL.

2. Explore and modify the recommendation algorithms:
    ```sh
    jupyter notebook Movie-recommendation-system.ipynb
    ```

3. Load the movie data:
    ```python
    import pickle
    with open('movies_dict.pkl', 'rb') as file:
        movies_dict = pickle.load(file)
    ```
