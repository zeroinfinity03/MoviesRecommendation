# Movie Recommendation System

This project is a Movie Recommendation System that leverages machine learning algorithms and content-based filtering to suggest movies based on user preferences. It utilizes data from the TMDB dataset and provides an interactive web interface through Streamlit.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data and Model Details](#data-and-model-details)
- [Requirements](#requirements)
- [Technical Details](#technical-details)
- [Troubleshooting](#troubleshooting)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

The Movie Recommendation System is designed to provide personalized movie recommendations by analyzing various attributes of movies, such as genres, keywords, and overviews. The web application, built using Streamlit, allows users to input their preferences and receive tailored suggestions, complete with movie posters fetched from the TMDB API.

## Features

- **Content-Based Filtering**: Recommends movies by calculating similarities between movie descriptions, genres, and keywords.
- **Interactive Web Interface**: Built with Streamlit, providing an easy-to-use platform for users to get movie recommendations.
- **Dynamic Poster Fetching**: Uses the TMDB API to fetch and display movie posters alongside recommendations.
- **Data Exploration and Model Training**: Jupyter Notebook (`notebook.ipynb`) included for detailed data processing and model development steps.

## Project Structure

- **`app.py`**: The main Streamlit application file that runs the web app and serves movie recommendations.
- **`notebook.ipynb`**: Contains exploratory data analysis, preprocessing, and the machine learning model used for recommendations.
- **`tmdb_5000_movies.csv`**: The dataset used for building the recommendation system, containing movie metadata from TMDB.
- **`movie_list.pkl`**: A pickle file storing the processed list of movies and their features, used to speed up the recommendation process.
- **`requirements.txt`**: Lists all Python dependencies required to run the project.
  
## Setup and Installation

### Prerequisites

Ensure you have Python 3.7 or higher installed. It's recommended to use a virtual environment for managing dependencies.

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
