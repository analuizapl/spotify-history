# My streaming analysis

## Description

This project analyzes my music streaming data to gain insights into my listening habits and preferences. 
It uses the pandas library in Python to read, clean, and process the data and numpy, matplotlib, and seaborn for data visualization.

## Notes

1. It's necessary to have you streaming history from spotify  to read into the dataframes. 

```python
df_stream0 = pd.read_json('endsong/endsong_0.json')
df_stream1 = pd.read_json('endsong/endsong_1.json')
# ... 
df_stream28 = pd.read_json('endsong/endsong_28.json')
```

2. The code also saves the processed data to a CSV file called "completeStreaming.csv"
