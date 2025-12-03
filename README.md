Prophet is ideal for daily business time series with:
Strong seasonality (daily, weekly)
Sudden changes due to holidays or operational events
Missing values handled automatically
 Non-linear trends
This fits public transport demand perfectly, which shows both weekday/weekend patterns and occasional spikes.
Model Components
Trend Component
Uses piecewise linear function to model changes over time (changepoints).
Handles real-world demand spikes in transport services.

Seasonality
Daily and weekly seasonality is automatically detected.
Weekends and weekdays behave differently — Prophet models this naturally.

Uncertainty Intervals
Outputs yhat_lower and yhat_upper to capture prediction uncertainty.
Helps in planning operational buffers.
