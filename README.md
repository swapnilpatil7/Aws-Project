# Aws-Project

Project Name:- Recommendation For Animation Series

Table Of Contents:-

- What is Recomendation System?
- Reason to Choose this Project
- Pandas Methods which are Used in this project
- Graphs which are used
- Workdone
- Result
- Conclusion
- Future Scope of Project

1) What is Recommendation System?


   - Based on Users preference, it can show what user want to see.
   - For example, MAL uses recommendation system. It suggest people new movies according to their preferences by watching and voting movies.
   - The purpose of recommender systems is recommending new things that are not seen before from people.

2) Reason to Choose this Project:-

   - During My childhood i like to watch Animation series. It is Entertaining and fun.
   - I choose this Project because I want to create Recommendation system. Because   

3) Pandas Methods which are Used in this project:-

   - head(), tail(), shape, size, columns, dtype, info(), description(),
   - duplicated(), isnull(),
   - sum(), fillna(), nlargest()
   - sort_values(), groupby(),
   -  max(), min()

4) Graphs which are used:- For plotting i have used matplotlib.pyplot and seaborn

   - Heatmap
   - Bar Graph
   - Countplot
   - Pie Chart
   - Boxplot

5) Workdone:-

   - I used duplicated so that if there are same values present in dataset i can see and then remove them.
   - By using isnull, we can see if there is any null value present in any columns.
   - By using fillna I have filled all the Nan values in the dataset
   - By using sort_values we get Highest rating, members.
   - I used groupby where i need the reference of some other column.
   - I used man and min get highest and lowest value.
   - I used countplot where the data is more and to visualize it properly.
   - I used Bar Graph to show episodes w.r.t. rating
   - With the help of Pie chart i show top 5 genre in columns.
   - Boxplot also help to visualise episodes w.r.t. rating of shows.

6) Result:- 

   From the above analysis we can say that, 
    - Most rated show is Taka no Tsume 8: Yoshida-kun no X-Files.
    - Most Popular show is Death note.
    - Least popular show is Platonic Chain: Ansatsu Jikkouchuu.
    - Longest running Show is Oyako club.

    Similarly, We learn that Some shows have highest Rating, but due to lack of members they are consider Avg Shows.
    Some shows have less episodes but due to members and rating they are popular, some shows even with long running can't make it upto Popular show.


7) Conclusion:- 

   - From the above Analysis we can conclude that, New users who are unaware of this vast world, Every User has its preference wheather user prefer shows on based on genre,     popularity or rating. 
   - Even with user prefernece, User still need Recommendation System that tell users not only user preference but also time duration. So that Users can choose shows based on user convenience.
   - Based on above Analysis, Users can choose shows based on Rating, Genre, Members and Time Duration.
   - That means, Even we do not consider above Preference is important in the shows.

    From the Above Analysis We learn that, 
    - Rating Based recommendation System
    - Members based recommendation system
    - Time Duration based recommendation system.
    - Correlation between vectors.

8) Future Scope of this Project:-

   - We can use this Recommendation system for Netflix Shows, Amazone Prime, and any OTT flatform for Recommendation.




