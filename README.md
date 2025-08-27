# DFS Projection Model

Brief template showing the web scraper and a basic projection model without giving too much away ;)

Current results: 16.4% edge, +86.4u profit

Inspiration from https://apanalytics.shinyapps.io/DARKO/, with the specific stat categories and exponential smoothing constants more tailored to capture game-to-game trends without overfitting. Data is pulled from https://www.pbpstats.com

This example is the NBA model, though the MLB model is also very profitable due to smaller total betting volume and larger sample sizes (162 games). In general batting and pitching is less streaky compared to shooting %.

## Future Features

- Live lineups based on injury reports (redacted)

- Bets sorted by EV based on web scraped prop lines and odds (redacted)

- Betting size generator that takes into account current bankroll, bet EV, and bet variance (redacted)
