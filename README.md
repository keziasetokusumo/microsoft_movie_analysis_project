# Microsoft Movie Analysis

Understanding the success of movies through data analytics

![RT_300EssentialMovies_700X250](https://user-images.githubusercontent.com/111642763/206069521-7a4f0ba1-f846-43c9-ac06-bbb5c6d8080a.jpg)

## Overview and Business Problem

Microsoft is looking to enter the film making space and their next venture is to launch a movie studio. As part of their plans to break into the industry, Microsoft needs to conduct an initial data analysis of current competitors to determine the types of movies they should produce. Popular movies in recent years can be linked to certain genres and persons. Microsoft can leverage this type of data analysis as time goes by to gain an understanding of the public's current preferences to operate their movie-making business.

### The Data

Public databases from sources such as [IMDB](https://www.imdb.com/) and [Box Office Mojo](https://www.boxofficemojo.com/) can be leveraged to gain a better understanding of the type of movies that competitor studios are releasing. They contain relevant information such as release year, cast, genre, gross proceeds, and more. See an example of an IMDB entry from the TV series "Wednesday" [here](https://www.imdb.com/title/tt13443470/?ref_=hm_fanfav_tt_i_1_pd_fp1). See an example of a Box Office Mojo entry from the movie "Black Panther: Wakanda Forever" [here](https://www.boxofficemojo.com/release/rl3573908993/?ref_=bo_hm_rd).

### Methods
This project begins by analyzing basic facts about the movie, such as the typical run time in this case. The analysis then pivots to determine which studio has yielded the most in total gross proceeds up to date - the purpose behind this is to understand which company is currently leading the space. From there, Microsoft can narrow their focus to study the type of movies genres that the leading studio's most financially successful films contain. Lastly, the project identifies financially successful directors to provide Microsoft with an initial direction of who to involve in their projects.

### Results

Most movies have a duration near 100 minutes, with the average run time at ~86 minutes

<img width="984" alt="Screen Shot 2022-12-09 at 12 16 55 PM" src="https://user-images.githubusercontent.com/111642763/206757251-b82a5e9d-b9d3-4bb9-b0d1-f5529448bd6c.png">


On average, BV Studios records the highest total gross proceeds per movie when compared to other major studios that have released over 50 films

<img width="859" alt="Screen Shot 2022-12-17 at 1 53 57 PM" src="https://user-images.githubusercontent.com/111642763/208258170-7f55e13f-9c39-4bba-984b-1b7fce860bec.png">


Among BV Studios' 20 highest grossing films, the three most common genre combinations are: (1) Action/Adventure/Sci-Fi; (2) Adventure/Animation/Comedy; (3) Action/Adventure/Comedy

<img width="1029" alt="Screen Shot 2022-12-17 at 1 50 49 PM" src="https://user-images.githubusercontent.com/111642763/208258108-2a205d17-efca-4452-a65f-9fd65d9512a0.png">


The following directors were involved in the production for BV Studios' 20 highest grossing films that received strong ratings of 7 or above

<img width="1048" alt="Screen Shot 2022-12-17 at 1 51 49 PM" src="https://user-images.githubusercontent.com/111642763/208258256-aa4ebba3-3b0d-4e62-9365-87579ceb5deb.png">


### Conclusions / Recommendations
* Microsoft should keep their movie run times consistent with or near the industry average of 86 minutes, ideally between 75-100 minutes
* BV Studios' highest 20 grossing films were mostly within the genre combinations of Action/Adventure/Sci-Fi, Adventure/Animation/Comedy, and Action/Adventure/Comedy - Microsoft should focus on specializing in movies with these genres, especially the theme of Adventure
* When people think of movies, they often only remember famous cast members, however, selecting the crew behind the camera is just as important - Microsoft should look to hire directors such as Lee Unkrich and Ronnie Del Carmen, who were involved in the production for BV Studios' 20 highest grossing films that received strong ratings of 7 or above

### Data Considerations and Limitations
* Look at the available budget and compare it to gross proceeds, as some companies have more resources than others
* Conduct data analysis of which type of movies have been popular during different years, as public preferences often change
* Much of a movie's success is also due to how well it's remembered - future data analysis can also look at how long a movie was being showed since release or how many replays a movie received on streaming platforms like Netflix/Hulu

## Additional Information
For detailed copy of the data analysis process and related code, please refer to the [Jupyter Notebook](https://github.com/keziasetokusumo/p1_project/blob/master/movie_analysis_jupyternotebook.ipynb). A summary of findings can also be found in this [deliverable](https://github.com/keziasetokusumo/p1_project/blob/master/p1_project_deliverable.pdf).

## Data Sources
* [Box Office Mojo](https://www.boxofficemojo.com/) tracks box-office revenue, related news, and analysis
* [IMDB](https://www.imdb.com/) is an online database for films and TV shows, including information such as cast, production crew, ratings, and reviews

## Repository Structure
* images
* zippedData
* .gitignore
* README.md
* movie_analysis_jupyternotebook.ipynb
* p1_project_deliverable.pdf
