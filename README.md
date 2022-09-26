# YoutubeDataset
Youtube data Statistics
Demo Project Assessment- Youtube statistics -->


Dataset Description -> 
 
The dataset contains two files for analyzing the relationship between the popularity 
of a certain video and the most relevant/liked comments of said video.


videos-stats.csv:

Title: Video Title.
Video ID: The Video Identifier.
Published At: The date the video was published in YYYY-MM-DD.
Keyword: The keyword associated with the video.
Likes: The number of likes the video received. If this value is -1, the likes are not publicly visible.
Comments: The number of comments the video has. If this value is -1, the video creator has disabled comments.
Views: The number of views the video got.


comments.csv:

Video ID: The Video Identifier.
Comment: The comment text.
Likes: The number of likes the comment received.
Sentiment: The sentiment of the comment. A value of 0 represents a negative sentiment, 
while values of 1 or 2 represent neutral and positive sentiments respectively.


Stage 1-->  
Cleaning the data -->
1. Removal of null values.
2. Removal of duplicate values.

Stage 2 --> transformations .

1. Number of videos of each keywords.
2. Number of videos published over time.
3. Videos with keywords arranged by maximum, minimum, average and total views
4. Top 10 most Liked Videos
5. Top 10 most Viewed Data Videos.
6. Mering video-stats and comments dataframes to get the Title column.
7. Dropping Missing Values.
8. Top 10 Videos with best Sentiments.
9. Top 10 Videos with worst Sentiments.
10.
