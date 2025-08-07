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
<img width="1431" height="802" alt="Dashboard" src="https://github.com/user-attachments/assets/7c1ec798-2639-4915-98ea-8464ace0c870" />

  - Movies and Tv Shows has been in a stalemate until the year 1994 where movies becomes a big hit especially movies with Drama and/or Comedy as their main genre as this is when the big hit movies like (This list is from [IMDB](https://www.imdb.com/list/ls070069226/):
    - Forrest Gump with a rating of 8.8
    - The Shawshank Redemption with a rating of 9.3
    - Pulp Fiction with a rating of 8.8
    - And the one of the most known animation movie, The Lion King with a rating of 8.5
  
  - Not only that this is the year where the well known Actor Jim Carrey Makes a name of himself with the movies like The Mask, Ace Ventura: Pet Detective, Dumb and Dumber. The Genre Drama and Comedy has been on a climb ever since.
  
  - But Why is Drama always enjoyed by the masses?
    - According to Elia Kazantzoglou a Greek-American film and Theatre director, producer, screenwriter, and actor.
      - we love drama not because we enjoy suffering, but because we’re moved by triumph through adversity. It helps us process pain, discover meaning, and feel affirmed. Drama shows us people growing through struggle, and that resonates with our human desire to make sense of a chaotic world. That’s why, despite everything, we keep watching and writing.


