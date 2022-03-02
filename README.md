# Final Project: Movies industry success predictions and insights

![image](https://user-images.githubusercontent.com/96190122/156390528-b692879b-ca50-4271-9366-c4390c130c28.png)


**Authors:** Biagio Girlando; Lok Ming Bosco Au-Yeung

**Objective:** The goal is to build a model to predict worldwide box office performance as well as provide insights on succesfull and prolific producers, genres, directors and cast.

**Data:** 
The data will be scraped from 3 sources and joined in one dataset.

- The Numbers:
   - Link: https://www.the-numbers.com/movie/budgets/all (Info collected: budget, worldwide box office)

- IMDB:
   - Link: https://www.imdb.com/ (Info collected: User rating, main cast)
 
- Rotten Tomatoes
   - Link: https://www.rottentomatoes.com (Info collected: Critic rating, user rating, director, genre, distributor)

**Brief outline action plan:**
1. Web scraping
- Collect info from "The Numbers" as the information on budget and box office is the most difficult to find on the web for different movies. Scrape additional info from IMDB and Rotten Tomatoes creating a unified DF by using the title name as the primary key.

2. EDA and Data cleaning
- Clean the DF, drop missing values and make sure the data is consistent. Check for outliers and find correlations.

3. Clustering
- Cluster some of the features to facilitate the understanding of the model. Possible clustering include cast and directors, clusterd by number of movies they worked in.

 4. Data Transformation and Modelling
 - Standardize the values
 - X/Y split
 - Encode categorical features
 - Test and improve the model
 
 5. Visualization
 - Visualization of insights and patterns within the Data Frame created.
