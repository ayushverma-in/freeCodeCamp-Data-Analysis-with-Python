# Page View Time Series Visualizer

Visualizes daily page-view data for the freeCodeCamp forum (2016–2019) using a line chart, a monthly bar chart, and year/month box plots to reveal trends and seasonality.

## Tech Used
Python, Pandas, Matplotlib, Seaborn

## How to Run
```bash
pip install -r requirements.txt
python main.py
```

## Output
- `line_plot.png` — daily traffic over time
- `bar_plot.png` — average views per month, grouped by year
- `box_plot.png` — year-wise trend and month-wise seasonality

## What I Learned
Working with time-indexed data, resampling/grouping by date parts (year, month), and visualizing trend vs. seasonality.
