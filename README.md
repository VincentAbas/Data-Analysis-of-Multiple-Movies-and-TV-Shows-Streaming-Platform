# Data-Analysis-of-Multiple-Movies-and-TV-Shows-Streaming-Platform

# Data Source
  - Netflix - https://www.kaggle.com/datasets/shivamb/netflix-shows
  - Disney+ - https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows
  - Amazon Prime - https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows
  - Hulu - https://www.kaggle.com/datasets/shivamb/hulu-movies-and-tv-shows

# Data Preperation
  - The data preparation is done in python in google colab, you can see it [here.](https://github.com/VincentAbas/Data-Analysis-of-Multiple-Movies-and-TV-Shows-Streaming-Platform/blob/d92ecfcb7a1f273619a1236989b68645c5d3a205/Data%20Preperation%20of%20Streaming%20Platform%20Analysis.ipynb)
## Data Merging
  - Since all of the dataset have the same columns/parameters I just stacked it together.

## Data Cleaning
  - Removed Null Values.
  - Removed Duplicates.
  - Removed Unnecessary data/columns(too many missing data to be useful).
    
## One-Hot Encoding
  - I used One-Hot Encoding on the genres as there are movies/tv shows that listed multiple genres in one column. Since its a lot of genres I removed the duplicated ones like (Standup, Standup Comedy) and the genres that provide too little information.

# Executive Summary of Findings 
  - You can view the Dashboard [here.](https://public.tableau.com/app/profile/vincent.abas/viz/StreamingPlatformAnalysisDashoard/Dashboard1#1)


