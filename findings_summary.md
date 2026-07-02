# Airline Delay Analysis — Findings Summary

## Key Findings

1. Validated 611,735 raw flight records; 604,270 passed quality checks (1.22% rejection rate).
2. Airline G4 averages 17.5 min arrival delay, the highest among all carriers analyzed.
3. Correlation between flight distance and arrival delay is -0.021 (weak negative relationship).
4. ANOVA confirms a statistically significant difference in arrival delays across airlines (F=275.44, p<0.001).
5. T-test confirms G4 has significantly higher average delays than YX (t=-20.06, p=<0.001). Effect size is small (Cohen's d=0.32); the true difference in average delay is estimated between 17.0 and 20.7 minutes (95% CI).
6. MGM airport has the highest average departure delay (34.3 min) vs. the overall average of 12.4 min (2.8x higher).

## Files Generated
- `airline_delay_stats.csv` — mean/median/std delay by airline
- `airport_delay_stats.csv` — mean delay by origin airport
- `delay_by_airline.png` — bar chart visualization
