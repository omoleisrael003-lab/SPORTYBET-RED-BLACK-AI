# RED-BLACK AI + FOOTBALL PREDICTOR

A mobile-friendly research dashboard for football score estimates and a transparent Red/Black/Green probability baseline.

## Features
- Enter two real football team names; searches TheSportsDB for teams and recent match results.
- Basic Poisson scoring model estimates likely scorelines, home/draw/away, over-goals and both-teams-to-score probabilities.
- Virtual football section reports when provider-specific verified history is unavailable instead of inventing a prediction.
- Red/Black/Green displays an equal one-third baseline only, not a next-result prediction.

## Publish with GitHub Pages
1. Open repository **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then Save.
5. Wait for GitHub Pages to publish the site.

## Data and limitations
The real-football module uses TheSportsDB's public demo API endpoint. Availability, coverage, CORS behavior, and rate limits may vary. The model is a basic estimate, not a betting guarantee; it does not account for confirmed lineups, injuries, venue strength, odds, or calibrated backtesting. Virtual football is provider-specific and often independently generated; team names alone cannot reliably reveal a future result.