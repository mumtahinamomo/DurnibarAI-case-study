# Outcomes & Metrics

## North Star Metric
**Weekly Consistent Trackers (WCT)** = (# users who log on ≥3 distinct days in a week) / (WAU)

Rationale: captures habit formation and real value creation, not just opens.

## Supporting Metrics
- **Activation**: % new users who complete first plan and first log within 24h.
- **Time-to-log**: median seconds from open to submitted entry.
- **Retention**: D7/D30 retained (≥1 log in window). 
- **Motivation loop**: % users enabling streaks; avg days streak length.
- **Nutrition coverage**: % searches that return a match within 1 edit.

## Instrumentation Sketch
- Client events: `app_open`, `start_log`, `submit_log`, `enable_streaks`, `search_food`, `food_matched`.
- Cohorts: new vs. returning, persona (student/athlete/trainer), platform (iOS/Android/Web).
- Dashboards: Activation funnel, WCT weekly trend, Time-to-log distribution.
