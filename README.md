# T20 World Cup 2024 Match Analysis

## Overview

This project provides an in-depth analysis of the T20 World Cup 2024 match between India and the USA held on June 17, 2024. The analysis includes player performances, team statistics, and key events such as dismissals and reviews. Using Python and data visualization tools, we uncover significant insights into the match dynamics and performance patterns of both teams.

## Problem Statement

The objective of this project is to analyze the detailed delivery data from the T20 World Cup 2024 match between India and the USA. By examining various aspects such as run rates, wicket patterns, and key partnerships, we aim to understand the factors that contributed to the outcome of the match. This analysis can help in strategic decision-making and performance improvement for future matches.

## Dataset

The dataset contains comprehensive records of all deliveries bowled during the match. Below is the information about all the columns in the dataset:

- `batter`: The name of the batsman.
- `bowler`: The name of the bowler.
- `non_striker`: The name of the non-striker batsman.
- `runs_batter`: The runs scored by the batsman on that ball.
- `runs_extras`: The extra runs given (like wides, no-balls).
- `runs_total`: The total runs scored on that ball (batsman runs + extras).
- `wickets_0_player_out`: The name of the player who got out.
- `wickets_0_kind`: The mode of dismissal (e.g., lbw, bowled).
- `team`: The team playing the innings.
- `over`: The over number in which the ball was bowled.
- `ball`: The ball number in that over.
- `extras_wides`: Extra runs due to wide balls.
- `extras_byes`: Extra runs due to byes.
- `extras_noballs`: Extra runs due to no-balls.
- `extras_legbyes`: Extra runs due to leg byes.
- `extras_penalty`: Penalty runs awarded.
- `wickets_0_fielders_0_name`: Name of the fielder involved in the dismissal (if any).
- `wickets_0_fielders_1_name`: Additional fielder involved in the dismissal.
- `review_by`: The team or player requesting a review.
- `review_umpire`: The umpire involved in the review.
- `review_batter`: The batsman involved in the review.
- `review_decision`: The decision made after the review.
- `review_type`: The type of review (e.g., DRS).

## Implementation

1. **Data Loading and Preprocessing**:
    - Import necessary Python libraries.
    - Load the dataset and check for missing values and data types.
    - Clean and preprocess the data for analysis.

2. **Run Rate Analysis**:
    - Calculate the run rate per over for both India and the USA.
    - Visualize the run rate comparison using line plots.

3. **Wicket Analysis**:
    - Analyze the timeline and mode of wickets taken.
    - Visualize the wickets taken over the overs for both teams.

4. **Partnership Analysis**:
    - Examine key batting partnerships and their contributions.
    - Visualize the runs scored by different batting pairs over each over.

5. **Bowling Performance**:
    - Compare the economy rate and wickets taken by various bowlers.
    - Visualize the performance of bowlers in the match.

## Tools

- **Python**: For data manipulation and analysis.
- **Pandas**: For data loading and preprocessing.
- **Plotly**: For interactive data visualizations.
- **Jupyter Notebook**: For developing and documenting the analysis process.

## Key Insights

1. **Run Rate Comparison**:
    - India maintained a higher and more stable run rate of 5.84 compared to the USA's 5.50.
    - India's run rate was relatively more stable, especially in the death overs.

2. **Wicket Patterns**:
    - The USA experienced frequent wicket losses, disrupting their momentum.
    - India maintained longer partnerships, aiding their consistent scoring.

3. **Key Partnerships**:
    - India's productive partnerships, especially in the middle and death overs, significantly boosted their total score.
    - The USA's sporadic partnership contributions reflected their inconsistent performance.

4. **Bowling Performance**:
    - Arshdeep Singh emerged as the most effective bowler with the highest number of wickets and a commendable economy rate.
    - The USA's bowlers had higher economy rates and were less effective in taking wickets.

## Conclusion

India's strategy of consistent scoring, effective partnerships, and a balanced bowling attack proved successful against the USA's inconsistent batting performance and less impactful bowling. The analysis highlights the importance of maintaining a steady run rate and building strong partnerships to achieve success in T20 matches.

---

Feel free to customize this README further to suit your specific needs or add additional sections if required.
