# Movie Recommendation System

## Overview

This project implements a **Content-Based Filtering** movie recommendation system using movie metadata. It helps users discover movies similar to a selected title based on features like genres, cast, crew, and overview.

## Features

- Data preprocessing: merging datasets, handling nulls, and text cleaning
- Tag creation by combining key features
- Natural Language Processing (NLP) with stemming and vectorization
- Cosine similarity to find and rank similar movies
- Top 5 recommendations for a given movie

## Dataset

- Source: [Kaggle - TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
- Size: ~5000 movies
- Key columns used: `title`, `genres`, `overview`, `keywords`, `cast`, `crew`

## Setup Instructions

1. Clone the repository
2. Install dependencies:

```bash
pip install pandas numpy scikit-learn nltk
