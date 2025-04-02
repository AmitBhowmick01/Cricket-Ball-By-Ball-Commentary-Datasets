
# **Cricket-Ball-By-Ball-Commentary-Datasets**
![photo-1540747913346-19e32dc3e97e](https://github.com/user-attachments/assets/d4034726-964c-47ae-9db6-40e77817009f)

## Overview

This GitHub repository provides comprehensive match-wise commentary datasets for international tournaments. Each dataset includes detailed ball-by-ball commentary, featuring runs per ball, total runs scored per delivery, player performances, team scores, and other relevant match insights from the tournament.

## Usage

- **Research:** Use the datasets for statistical analysis, trend identification, and predictive modeling.

- **Visualizations:** Create engaging visualizations to showcase insights.

## Dataset Structure

Each match dataset includes the following columns:

- **matchID**: ID for the match in the dataset.
- **matchNo**: Match number of the tournament.
- **match**: Name of the match.
- **homeTeam**: Name of the home team.
- **currentInning**: Batting inning of the team.
- **inningID**: Inning in the match.
- **over**: Ball number within the over.
- **runningOver**: Number of the over running.
- **runs**: Number of runs scored off the ball.
- **batsmanRuns**: Runs scored by the batsman.
- **batsmanBall**: Ball faced by the batsman.
- **bowlerRuns**: Runs conceded by the bowler.
- **shortText**: Short description or event associated with the ball.
- **batsmanPlayerID**: ID of the batsman.
- **batsmanName**: Name of the batsman.
- **bowlerPlayerID**: ID of the bowler.
- **bowlerName**: Name of the bowler.
- **isBoundary**: Indicator if the ball resulted in a boundary (`True` for yes, `False` for no).
- **isWide**: Indicator if the ball was wide (`True` for yes, `False` for no).
- **isNoBall**: Indicator if the ball was a no-ball (`True` for yes, `False` for no).
- **isLegBye**: Indicator if the runs are leg-bye (`True` for yes, `False` for no).
- **isBye**: Indicator if the runs are bye (`True` for yes, `False` for no).
- **isWicket**: Indicator if there is a wicket (`True` for yes, `False` for no).
- **isBowlerWicket**: Indicator if the wicket is credited to the bowler (`True` for yes, `False` for no).
- **wicketText**: Description of the wicket event.
- **wktBatsmanName**: Name of the batsman who got out.
- **wktBowlerName**: Name of the bowler who took the wicket.
- **wktBatsmanRuns**: Runs scored by the batsman who got out.
- **wktBatsmanBalls**: Balls faced by the batsman who got out.
- **commentary**: Commentary text associated with the ball.

## Contributing
Contributions are welcome! If you have additional data or want to improve existing datasets, feel free to submit pull requests.
