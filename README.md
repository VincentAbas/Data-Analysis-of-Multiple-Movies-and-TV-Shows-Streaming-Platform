# Data-Analysis-of-Multiple-Movies-and-TV-Shows-Streaming-Platform (1920 - 2021)

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

# Deep Dive and Insights

## Genre Trends
 - Here shows the top 5 genres from 1920 - 2021
<img width="1049" height="522" alt="Genre Popularity over time" src="https://github.com/user-attachments/assets/e54f39b8-427b-42ad-b394-a754ed0e041b" />

  - Drama and Comedy
    
    - Movies and Tv Shows has been in a stalemate until the year 1994 where movies becomes a big hit especially movies with Drama and/or Comedy as their main or sub-genre as this is when the big hit movies like (This list is from [IMDB](https://www.imdb.com/list/ls070069226/)):
      - Forrest Gump with a rating of 8.8
      - The Shawshank Redemption with a rating of 9.3
      - Pulp Fiction with a rating of 8.8
      - And the one of the most known animation movie, The Lion King with a rating of 8.5
  
    - Not only that this is the year where the well known Actor Jim Carrey Makes a name of himself with the movies like The Mask, Ace Ventura: Pet Detective, Dumb and Dumber. The Drama and Comedy genres has been on a climb ever since.
  
    - But Why is Drama always enjoyed by the masses?
      - According to Oxford American article called "Why We Like Drama" by Graham Gordy. You can find it [here](https://oxfordamerican.org/magazine/issue-66-fall-2009/why-we-like-drama).
      
        - Elia Kazantzoglou a Greek-American film and Theatre director, producer, screenwriter, and actor says we love drama not because we enjoy suffering, but because we’re moved by triumph through adversity. It helps us process pain, discover meaning, and feel affirmed. Drama shows us people growing through struggle, and that resonates with our human desire to make sense of a chaotic world. That’s why, despite everything, we keep watching and writing.
        
## Media Types
<p align="center">
  <img  width="500" src="https://github.com/user-attachments/assets/5a857dc3-975c-4a14-a68f-f512a7d46186" />
  <img width="250" src="https://github.com/user-attachments/assets/f8f97c1c-54d7-4d96-8ea1-efee372c8f8d" />
</p>

  - Movie production is still on the rise as well as the TV show production however the numbers are far apart. It is surprisingly that tv shows are more popular than the movie according to this article [here](https://www.techspot.com/news/93794-tv-shows-far-more-popular-than-movies-other.html) by Shawn Knight as it is stated that roughly 75% of the viewing is for TV shows which is weird considering the fact that the production quantity of a movie is a lot higher than the tv shows accross multiple platforms.
    
And considering the fact that starting from Pre-Production of the movies it takes about a minimum of 14 months up to 21 months to deliver the full product according to this [article](https://stephenfollows.com/p/how-long-the-average-hollywood-movie-take-to-make?hubs_content=br.hubspot.com%2525252Fblog&hubs_content-cta=null&hubs_post=br.hubspot.com%25252525252Fblog%25252525252Fservice&hubs_post-cta=null&partner_key=jeanfran%252525252525C3%252525252525A7oistourel) and TV shows get about 12 - 18 months according to this [article](https://ken-aguado.medium.com/the-timeline-for-the-making-of-a-tv-series-3b1fcb7f8448). Why is the production of movies keeps increasing and not the TV shows? I think that a TV show requires a great amount of effort compared to movies in terms of making a script, story, and planning of it all as TV shows usually have a longer showing period compared to movies. And comparing The [highest grossing movie](https://www.boxofficemojo.com/chart/top_lifetime_gross/?area=XWW) **Avatar** accumulating $2.9 Billion and [The highest grossing TV show](https://www.brandvm.com/post/tv-shows-made-the-most-money) **The Simpsons** accumulating $14 Billion. Granted it will always depend on whether your medium is good enought to captivate your target audiences as well as to bring new audiences.


    
# Executive Summary of Findings 
  - You can view the Dashboard [here.](https://public.tableau.com/app/profile/vincent.abas/viz/StreamingPlatformAnalysisDashoard/Dashboard1#1)
 <img width="1015" height="596" alt="Dashboard" src="https://github.com/user-attachments/assets/05b71443-08ce-4ada-8e99-021e9d235403" />



  


