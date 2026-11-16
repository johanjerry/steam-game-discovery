# Steam Game Discovery

My app helps Steam players discover highly rated games by analyzing game genres, player reviews, and pricing.

> A course project for **MIST 4600: Computer Programming in Business** at the University of Georgia's Terry College of Business (Fall 2026).

## Problem

Steam has thousands of games, making it difficult for players to decide which games are worth purchasing. Players often have to compare genres, prices, and reviews individually. This project makes it easier to identify highly rated games and understand what types of games players enjoy.

## What it does

My app answers three questions:

1. **Genres:** Which Steam game genres have the highest average percentage of positive reviews?
2. **Game Modes:** Do multiplayer games receive better player ratings than single-player games?
3. **Pricing:** How do free games and paid games compare in player ratings?

## Data

The [Steam Games Dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) on Kaggle, collected in March 2025. The dataset is shared under the MIT License by its creator, artermiloff.

This project uses `steam_games.csv`, a smaller dataset containing 1,000 of the most-reviewed Steam games.

## Built with

- Python
- Pandas
- Google Colab
- GitHub
- Google Gemini API for game classification

## How to run it

1. Download the project notebook and `steam_games.csv` from this repository.
2. Open the notebook in Google Colab.
3. Upload the dataset to your Google Drive.
4. Run the notebook cells to load and analyze the data.
5. View the results comparing game genres and player ratings.

## Example output

The genre analysis function displays the top 10 Steam game genres ranked by their average percentage of positive player reviews.

The results help identify which genres receive the most positive feedback from players.

## AI Use Disclosure

*To be completed by the author.*

## Author

Johan Jerry

University of Georgia — Terry College of Business
