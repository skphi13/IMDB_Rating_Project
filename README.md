## Introduction <a id='intro'></a>
In this project, I worked with data from the entertainment industry. The dataset contains records on movies and shows. The research will focus on the "Golden Age" of television, which began in 1999 with the release of *The Sopranos* and is still ongoing.

The aim of this project is to investigate how the number of votes a title receives impacts its ratings. The assumption is that highly-rated shows (we will focus on TV shows, ignoring movies) released during the "Golden Age" of television also have the most votes.

## Description of the data
The data is stored in the file `movies_and_shows.csv`. 

## Description of columns:

- `name` — first and last name of actor (director)
- `character` — character played (for actors)
- `role` — the person’s contribution to the title (it can be in the capacity either of actor or director)
- `title` — title of movie (show)
- `type` — show or movie
- `genres` — list of genres under which the movie (show) falls
- `release_year` — year when the movie (show) was released
- `imdb_score` — score on IMDb
- `imdb_votes` — votes on IMDb

## Conclusion
The research done confirms that highly-rated shows released during the "Golden Age" of television also have the most votes. While shows with score 4 have more votes than ones with scores 5 and 6, the top three (scores 7-9) have the largest number. The data studied represents around 94% of the original set, so we can be confident in our findings.
