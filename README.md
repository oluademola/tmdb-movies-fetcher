# TMDB Movie Fetcher

## Overview

`TMDB Movie Fetcher` is a Python library that fetches movie data from the TMDB API and saves it into a specified database. This library is useful for developers who need to integrate TMDB movie data into their applications.

## Features

- Fetches movies from the TMDB API.
- Saves fetched movie data into the database.
- Easy to configure with API base URL, bearer token, and movie base URL.

## Arguments

- api_base_url (str): Base URL of the TMDB API.
- bearer_token (str): Bearer token for authorization.
- movie_base_url (str): Base URL for movie poster paths.
- movie_model: Movie model.

## Installation

To install the library, you can use pip:

```bash
pip install oeademola-movies-fetcher
```

## Usage

```python
from tmdb_movies_fetcher_pkg.tmdb_movies_fetcher import fetch_movies_from_tmdb

# Configuration
api_base_url = "https://api.themoviedb.org/3"
bearer_token = "YOUR_BEARER_TOKEN"
movie_base_url = "movie_base_url"
movie_model = your_movie_model

# Fetch and save movies
fetch_movies(api_base_url, bearer_token, movie_base_url, movie_model)
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.
