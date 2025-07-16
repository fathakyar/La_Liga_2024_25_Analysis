# La Liga 2024/25 - Player and Team Performance Analysis

## Overview
This project presents an exploratory data analysis of the 2024/25 La Liga season, focusing on both player- and team-level statistics. The analysis aims to uncover trends, relationships, and standout performances using Python and a variety of visualization tools.

## Dataset Description
The dataset contains **601 unique players** and includes both basic and advanced performance metrics.

**Main features:**
- `Player`: Name of the player
- `Nation`: Nationality (3-letter country code)
- `Position`: Main playing position
- `Team`: Club name
- `Age`: Age in years
- `Match`: Appearances made
- `Minutes`: Total minutes played
- `Goals`: Goals scored
- `Assists`: Assists provided
- `Yellow_Cards`, `Red_Cards`: Disciplinary records
- `xG`, `xAG`: Expected goals and assists
- `Gls/90`, `Ast/90`, `xG/90`, `xAG/90`: Per 90-minute normalized performance metrics

*Note: Some columns such as `xG`, `xAG`, and per-90 stats were imported as strings and converted to numeric values for proper analysis.*

## Key Questions Explored
1. Which players are the most effective in scoring and assisting?
2. Who are the most aggressive or most utilized players?
3. Are there correlations between age, cards, team strength and performance?
4. Which teams overperform or underperform in relation to xG?
5. What do per 90 stats reveal about style and efficiency?
6. Who are the most versatile players according to multi-metric radar charts?

## Visual Tools Used
- Correlation heatmaps for per-90 relationships
- xG vs Goals scatter plot
- Player radar charts (multidimensional)
- Nation-based player distributions
- Team averages and performance summaries

## Technologies
- Python (Pandas, NumPy)
- Seaborn, Matplotlib, Plotly
- Google Colab

## Conclusion
This analysis shows how football data can provide insights that go beyond surface-level stats like goals or assists. Using exploratory analysis and visual storytelling, we can identify tactical profiles, efficiency gaps, and creative player roles. Future work may include multi-season comparisons, player clustering, or predictive modeling.
