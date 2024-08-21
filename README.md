#Movie Performance Analysis Dashboard 

###Dashboard Snapshot : (https://github.com/Kanika151/Projects/blob/main/Untitled.png)



A comprehensive Movie Performance Analysis Dashboard provides insights into the performance of movies across multiple dimensions, including box office collections, IMDb ratings, OTT viewership, and audience preferences (most liked). The dashboard enables stakeholders to analyze and compare movie performance based on various attributes such as country, language, genre, number of votes, and streaming platforms.

A. **Key Requirements:**

1. **Box Office Collection Analysis:**
   1.1 Visualize and compare the total box office collections of movies across different countries, languages, and genres.
   1.2 Identify trends and patterns in box office performance over time.
   1.3 Assess the impact of release timing, marketing efforts, and other external factors on box office success.

2. **IMDb Rating and Audience Feedback:**
   2.1 Analyze IMDb ratings alongside the number of votes to understand the audience's reception and satisfaction levels.
   2.2 Correlate IMDb ratings with box office performance to identify critically acclaimed movies that also performed well commercially.
   2.3 Explore differences in IMDb ratings based on attributes such as genre, language, and country.

3. **OTT Viewership Analysis:**
   3.1 Track and visualize viewership data for movies available on streaming platforms.
   3.2 Compare OTT viewership with box office collections to evaluate the impact of digital releases on traditional movie performance metrics.
   3.3 Analyze how different genres, languages, and countries perform on various streaming platforms.

4. **Most Liked Movies Analysis:**
   4.1 Identify and rank movies based on audience preferences, such as "most liked" or highly rated by viewers.
   4.2 Understand the correlation between the "most liked" status and other performance indicators like box office collections and IMDb ratings.
   4.3 Explore audience preferences by genre, language, country, and streaming platforms to inform content creation and marketing strategies.

5. **Streaming Platform Performance:**
   5.1 Compare the performance of movies across different streaming platforms (e.g., Netflix, Amazon Prime, Hulu) in terms of viewership, ratings, and audience engagement.
   5.2 Identify the platforms where certain genres or types of movies perform best.

 **B. Stakeholders:**
- **Movie Producers and Distributors:** To understand the commercial success and audience reception of their films.
- **Streaming Platforms:** To identify popular content and improve content acquisition and marketing strategies.
- **Marketing Teams:** To optimize promotional strategies based on movie performance data.
- **Data Analysts and Researchers:** To conduct deeper analyses of movie performance trends and correlations.

**Outcome:**
The dashboard provides actionable insights that help stakeholders make informed decisions about movie production, distribution, marketing, and content strategy. By integrating and analyzing multiple performance indicators, the dashboard will serve as a valuable tool for understanding the holistic success of movies across different platforms and demographics.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that few columns had empty values were present except Box office Collection named "Box Office Collection", " "Streaming Platform".
- Step 5 : For "Box Office Collection"& "Streaming Platform" , null values were not taken into account as only less than 1% values are null in these columns
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for fields named "Genre".
- Step 9 : Four Card visuals were added to the canvas, one representing total movies, total Genres,Average Rating, No of OTTs, Total Languages. 
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
  Although, by default, while calculating average, blank values are ignored.

- Step 10 : Bar charts was also added to the report design area representing the Average Rating by Language, Total Movies available on OTT platforms & Distribution of Ratings. 

- Step 11: In the report view, under the insert tab, one text box was added to the canvas, depicting the title of Dashboard. 
 
- Step 12 : In the report view, under the insert tab using image option company's logo was added to the report design area. 

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/Kanika151/Projects/blob/main/Untitled.png)

# Insights

Following inferences can be drawn from the dashboard;

##Dashboard 1 : Top Rated Movies on Imdb

### [1] Total Number of Movies = 191

###[2] Average ratings = 8.15
           
### [3] Average Rating = 8.15 

    a) Marathi  - 8.55/10
    b) Kannada - 8.28/10
    c) Tamil- 8.24/10
    d) Malyalam - 8.18/10 
    e) Telugu - 8.16/10
  
    
  These ratings will change if different visual filters will be applied.  
  
  ### [4] Total Genre = 18 
       
  
      a) Action
      b) Adventure
      c) Biography
      d) Comedy
      e) Coming of age

##Dashboard 2 

### [5] Total No of Votes Received : 8M 

###[6] Highest Box Office Collection : Dangal with 304 M 

###[7] Biography Genre is the most successful on box office with highest collection of 5bn. Action being the second most successful. 

###[8] Hindi Language being the highest grosser. Telugu being second most successful after Hindi in terms of Regional Cinema. 

##Dashboard 3 

 ### [9] Netflix has the highest viewership & most successful. 

###[10] Most Popular or most liked movie is 3 idiots with highest no of reviews. 

###[11] 2016 has the Highest no of hits. 
 
 ### Highest Rated Movie : 12 th Fail ( 2023 ) 8.9/10
 
 1.1) 47.87 % customers travelled by Business class.
 
 1.2) 44.89 % customers travelled by Economy class.
 
 1.3) 7.25 % customers travelled by Economy plus class.
 
         thus, maximum customers travelled by Business class.
 
 ### Total Movies on Otts : 
 
 2.1) Amazon Prime Video has Max no of top rated Indian movies
 2.2)  52.44 % customers belong to '25-50' age group.
 
 2.3)  25.57 % customers belong to '50-75' age group.
 
 2.4)  0.31 % customers belong to '75-100' age group.
 
         thus, maximum customers belong to '25-50' age group.
         
### Genre 

3.1) Genre with top rated movies is Drama = 56/191
3.2) 81.69 % customers have customer type 'returning'.
       
       thus, more customers have customer type 'returning'.

### Type of travel

4.1) 69.06 % customers have travel type 'Business'.

4.2) 30.94 % customers have travel type 'Personal'.

        thus, m
