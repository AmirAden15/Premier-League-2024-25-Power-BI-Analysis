# Premier League 2024/25 Performance Analysis

A Power BI portfolio project investigating which performance factors were most strongly associated with Premier League points in 2024/25, and which teams performed better or worse than their underlying shooting statistics suggested.

## Dashboard Preview

![Executive Overview](executive-overview.png)

## Questions Explored

- Which attacking and defensive factors were most strongly associated with league points?
- Which teams combined strong attacking output with strong defensive performance?
- How did shot volume and shooting efficiency differ across teams?
- Which teams earned more or fewer points than expected from their shots-on-target difference?

## Performance Analysis

This page explores shot volume, scoring efficiency, attacking and defensive balance, and the relationship between key performance factors and league points.

![Performance Analysis](performance-analysis.png)

## Overperformance Analysis

This page compares each team’s actual points with the points expected from its shots-on-target difference. Positive values indicate teams that exceeded the shot-based expectation, while negative values indicate teams that finished below it.

![Overperformance Analysis](overperformance-analysis.png)


## Data Preparation

The original dataset contained 380 rows, with one row representing each Premier League match. Home and away statistics were stored in separate columns.

Using Power Query, I transformed the data into a team-match table with one row per team per match. This produced 760 rows and allowed the same measures to calculate performance consistently across home and away fixtures.

I validated the transformation by confirming that:

- All 20 teams were present.
- Every team played 38 matches.
- The dataset contained 380 distinct matches.
- Calculated points matched the final league table.
- No required columns contained errors or missing values.
