# YouTube_Trending_Videos_Analysis
Analysis of top 500 trending YouTube videos using Google API

## Overview
This project analyzes trending YouTube videos in the US using the YouTube Data API. It explores how engagement metrics like views, likes, comments, and video characteristics (such as duration, tags, and category) relate to video popularity.

## What It Does
Fetches trending video data using the YouTube Data API v3

Cleans and processes the data (handles missing values, converts types)

Performs exploratory data analysis with clear visualizations

Analyzes engagement by category, video length, tag count, and publish time

## Key Features
Histograms and scatter plots of views, likes, and comments

Correlation matrix of key engagement metrics

Category-based and duration-based performance analysis

## Visuals that answer questions like:

Which video categories trend the most?

Does video length influence views?

What time of day sees the most engagement?

## Tech Stack
Python (Pandas, Seaborn, Matplotlib)

Google API Client (googleapiclient)

YouTube Data API v3

Jupyter Notebook or Google Colab

## How to Run
Get an API key from the Google Cloud Console

Replace 'Your_API_KEY' in the script

Run the script or notebook to:

Collect trending video data

Save it to a CSV file

Generate and view analytical plots

## Output
trending_videos.csv: Cleaned dataset of trending videos

Plots and visuals rendered inline for analysis

## Possible Insights
Impact of video duration on viewership

Performance trends by content category

Influence of tags and upload timing on engagement
