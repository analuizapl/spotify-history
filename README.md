# Spotify Streaming History Analysis

## Description

Because I am an avid listener of music, I decided to analyze and explore my Spotify listening history. 

This project focuses on exploring and analyzing personal Spotify listening history to gain insights into music streaming habits and preferences.

The analysis is divided into two notebooks: "Complete History" and "Genres Analysis."


## Prerequisites
To run the notebooks, make sure you have the following requirements met:

Jupyter Notebook or JupyterLab installed
Python 3.x
Required Python libraries: Pandas, NumPy, Matplotlib, Seaborn, WordCloud, Requests, dotenv

## Usage
1. Open Jupyter Notebook or JupyterLab.
2. Navigate to the directory where you cloned/downloaded the notebooks.
3. Open the desired notebook:
   - `complete-history.ipynb` for complete streaming history analysis
   - `genres.ipynb` for genres analysis
4. Before running the notebook, make sure you have a valid Spotify Client ID and Client Secret.
5. Update the `.env` file with your Spotify Client ID and Client Secret.
6. Run the notebook cells one by one to execute the code and generate visualizations.

7. To use the Power BI dashboard, open Power BI Desktop and open the `my-spotify-streaming.pbix` file. Connect the dashboard to the `completeStreaming.csv` file and explore the visualizations to gain insights into the streaming history data.

## Notebook Descriptions

### Complete History
The Complete History notebook analyzes the complete Spotify streaming history by processing the data and generating various visualizations. It provides insights into top artists, top songs, streaming days, and songs heard over the years.

### Genres Analysis
The Genres Analysis notebook complements the Complete History analysis by extracting genres associated with frequently streamed songs. It utilizes the Spotify API to retrieve artist information and extract genres. The notebook visualizes the genres, helping to understand musical preferences and trends in the streaming history data.

## Power BI Dashboard
my-spotify-streaming.pbix: A Power BI dashboard that visualizes and analyzes the data from the completeStreaming.csv file. 
The dashboard provides interactive visualizations, including charts, graphs, and summaries of streaming history data.

[Dashboard](https://www.novypro.com/project/streaming-history-analysis)

## Notes

1. Before running the analysis, ensure that the necessary data from Spotify's streaming history is available.

2. The code also saves the processed data to a CSV file named "completeStreaming.csv" for further analysis or external use.