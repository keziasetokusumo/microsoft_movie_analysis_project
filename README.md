# Microsoft Movie Analysis

Understanding the success of movies through data analytics

![RT_300EssentialMovies_700X250](https://user-images.githubusercontent.com/111642763/206069521-7a4f0ba1-f846-43c9-ac06-bbb5c6d8080a.jpg)

## Overview and Business Problem

Microsoft is looking to enter the film making space and their next venture is to launch a movie studio. As part of their plans to break into the industry, Microsoft needs to conduct an initial data analysis of current competitors to determine the types of movies they should produce. Popular movies in recent years can be linked to certain genres and persons. Microsoft can leverage this type of data analysis as time goes by to gain an understanding of the public's current preferences to operate their movie-making business.

### The Data

Public databases from sources such as [IMDB](https://www.imdb.com/) and [Box Office Mojo](https://www.boxofficemojo.com/) can be leveraged to gain a better understanding of the type of movies that competitor studios are releasing. They contain relevant information such as release year, cast, genre, gross proceeds, and more. See an example of an IMDB entry from the TV series Wednesday [here](https://www.imdb.com/title/tt13443470/?ref_=hm_fanfav_tt_i_1_pd_fp1). See an example of a Box Office Mojo entry from the movie Black Panther: Wakanda Forever [here](https://www.boxofficemojo.com/release/rl3573908993/?ref_=bo_hm_rd).

### Methods
This project begins by analyzing basic facts about the movie, such as the typical run time in this case. The analysis then pivots to determine which studio has yeilded the most in total gross proceeds up to date - the purpose behind this is to understand which company is currently leading the space. From there, Microsoft can narrow their focus to study the type of movies genres that the leading studio produces most often. Lastly, this project identifies popular persons to provide Microsoft with an initial direction of who to involve in their projects.

### Results

Most movies have a duration near 100 minutes, with the average run time at ~86 minutes

<img width="984" alt="Screen Shot 2022-12-09 at 12 16 55 PM" src="https://user-images.githubusercontent.com/111642763/206757251-b82a5e9d-b9d3-4bb9-b0d1-f5529448bd6c.png">


On average, BV Studios records the highest total gross proceeds per movie when compared to other major studios

<img width="963" alt="Screen Shot 2022-12-09 at 12 17 04 PM" src="https://user-images.githubusercontent.com/111642763/206757274-2a2efb45-5244-41bf-ba88-550ae32a1375.png">


BV Studios often releases movies with the following genre combinations: (1) Adventure/Animation/Comedy; (2) Action/Adventure/Sci-Fi; (3) Action/Adventure/Fantasy

<img width="1126" alt="Screen Shot 2022-12-09 at 12 17 15 PM" src="https://user-images.githubusercontent.com/111642763/206757321-68ba33a1-7871-40c3-bd5f-9323b9a8f434.png">



Of all movies recorded in IMDB, the top 10 with the highest rating and number of votes are linked to the persons shown in the visualization below

<img width="1114" alt="Screen Shot 2022-12-09 at 12 17 24 PM" src="https://user-images.githubusercontent.com/111642763/206757342-f567fda2-53f4-46d0-aa91-13e8232e4434.png">


### Conclusions / Recommendations
* Microsoft should keep their movie run times consistent with or near the industry average, ideally between 80-100 minutes
* Microsoft can leverage BV Studio's best practices, especially focusing on developing successful movies in action and adventure
* When people think of movies, they often only remember famous cast members, however, selecting the crew behind the camera is just as important - Microsoft can start by considering individuals such as Brian Baucum, Paul Greive, and Lindsay Thompson, among others

### Data Considerations and Limitations
* Look at the available budget and compare it to gross proceeds, as some companies have more resources than others
* Conduct data analysis of which type of movies have been popular during different years, as public preferences often change
* Much of a movie's success is also due to how well it's remembered - future data analysis can also look at how long a movie was being showed since release or how many replays a movie received on streaming platforms like Netflix/Hulu

## Additional Information
For detailed copy of the data analysis process and related code, please refer to the [Jupyter Notebook](https://github.com/keziasetokusumo/p1_project/blob/master/movie_analysis_jupyternotebook.ipynb). A summary of findings can also be found in this [deliverable](https://github.com/keziasetokusumo/p1_project/blob/master/p1_project_deliverable.pdf).

## Data Sources
* [Box Office Mojo](https://www.boxofficemojo.com/) tracks box-office revenue, related news, and analysis
* [IMDB](https://www.imdb.com/) is an online database for films and TV shows, including information such as cast, production crew, ratings, and reviews
