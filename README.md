# Playoff Matchup Adjustment Tracker

This project is a small product concept inspired by Databallr’s playoff matchup pages.

Databallr’s current matchup view is useful for series-level totals, but playoff adjustments happen game by game. This prototype adds a game-by-game matchup timeline layer to help users see when defensive responsibilities changed during a playoff series.

## Case Study

The first case study uses the OKC vs SAS playoff series, with Victor Wembanyama on offense as the default view.

## Features

- Select an offensive player
- View game-by-game defensive matchup time
- Highlight a specific defender across the series
- Hover to inspect matchup details
- See primary and secondary defender summaries by game

## Why This Matters

Series-level matchup totals can hide important game-by-game adjustments. This view makes it easier to see when a team changed its matchup plan, who became the primary defender, and how that responsibility evolved across the series.

## Technical Stack

- Python
- pandas
- Plotly
- Streamlit
- CSV-based matchup data