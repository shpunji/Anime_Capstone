# Anime_Capstone
What Anime Should I Watch

Capstone Project for Nashville Software School Data Analytics Cohort 12

Tableau Dashboard

Link: https://public.tableau.com/app/profile/shpunji/viz/NSSAnime/TitlePage

Motivation:

My motivation for this project was my own interest in anime. 
Sometimes when I finish one anime, I don't know what to watch next. The anime catalogue
can be overwhelming, with over 20,000 animes out there in the world. So I wanted a way
to narrow the search a little. I also wanted a way that I could get friends into anime 
if they don't watch already and are beginning to express interest.

Contents:

This project includes first a PowerPoint Presentation that explores the history of anime. What is anime to start with? The project also includes an interactive Tableau Dashboard that allows filtering amongst various parameters to find details about animes that might be a good watch for the viewer.

Data Question: 

When certain parameters are met, namely specific Genre choice and specific TV Rating, what are the best options for a new watcher of anime to watch? 
A stretch goal would be to add an episode count filter and perhaps a filter for average review rating.

Challenges With The Project:

1. Scraping the data was a little difficult with IMDB due to their use of JavaScript in webbuilding in order to keep their lists up to date on vote counts and ratings.
2. Building the Tableau Dashboard was tedious. I needed to download each individual title image and use a PNG cleaner to create proper use images for each page. Then I needed to manually link each image with the page shape to create clickable icon.
3. I needed to building a parameter for each anime in order to link each sheet to its own dashboard but still have that dashboard link properly to the final dashboard.

Sources: 

IMDB.com, rottentomatoes.com, myanimelist.com, kaggle.com, wikipedia.org, complex.com, and gitnux.org

Navigating the Dashboards:

The dashboards are relatively self-explanatory. The first being called the "Title Page" is just that, no interaction possible. 
The first interactive page is the "Genres" dashboard. Here you can see the different genre options and the legend for TV Rating. Clicking a genre category will take you to another dashboard that will ahve the titles that fit within that genre. On each of these dashboards you can click the image of the title that interests you and it will take you to the final dashboard that has the details of the anime you have selected.
There is a dashboard titled "All Anime" that has a slicer at the bottom. Here you can simply choose the anime you'd like based off of title alone and read the details of that show. This will be more useful for those who have a little more knowledge of anime and just want a quick synopsis of a show that maybe was recommended to them.

What's missing:

The dataset is quite large. At the time of this upload, there are only 6 genre categories finished, out of the 15 I have chosen to categorize under. Each category is about 3 hours worth of work so there will be more and more added as time goes until all 15 are included.
The "All Anime" Dashboard does include animes that are not categorized into Genres yet, so that a user may still decide if that show is something for them to watch, manually. 