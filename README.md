# Spotify Music Mood Analyzer

A machine learning project that predicts a user's mood based on their Spotify listening history and song audio features.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Overview

Spotify Music Mood Analyzer leverages machine learning to analyze a user's Spotify listening habits and predict the mood or emotions evoked by the songs they listen to. By examining song metadata, audio features, and listening patterns, the project aims to provide insights into how music impacts mood.

## Features

- Collects and processes Spotify listening history
- Extracts song metadata and audio features (title, artist, genre, etc.)
- Analyzes listening habits (time of day, duration)
- Uses a Random Forest classifier to predict user mood on a 1-5 scale (1 = sad, 5 = happy)
- Achieves high accuracy, precision, and recall on test data

## Dataset

The dataset includes:

- **Song Metadata:** Title, artist, and genre for each song
- **Listening Habits:** Time of day and duration for each session
- **Mood Labels:** Manual mood rating for each session (1-5 scale)

## Model

A Random Forest classifier is used due to its robustness for classification tasks and ability to handle high-dimensional data. The model is trained on extracted features and mood labels to predict user mood based on new listening data.

## Results

- **Accuracy:** 85% on the test set
- **Precision:** 80%
- **Recall:** 90%

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/isabhiii/Spotify-Music-mood-Analyzer.git
   cd Spotify-Music-mood-Analyzer
   ```
2. Prepare your Spotify listening history data following the dataset format described above.
3. Run the Jupyter notebooks (`Clustering_Spotify_Songs.ipynb`, `Spotify Songs Clustering.ipynb`) to preprocess data, train the model, and evaluate results.
4. (Optional) Use `getPlaylistData.py` to extract playlist data from Spotify.

## Future Work

- Improve model performance with advanced techniques (e.g., deep learning)
- Expand the dataset with more users and mood labels
- Develop a web application for interactive mood prediction

## Contributing

Contributions are welcome! Please open issues or submit pull requests to help improve the project.
