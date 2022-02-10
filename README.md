# Youtubilytics
 Statistical Analysis on Youtube Video content in Python<br>
<br>
During the course of this project, using Python only, we tried to answer questions such as :<br>
1) What are the common trends on YouTube in general?<br>
   • What are the popular categories in a particular month?<br>
   • Is there any discrepancy between different country? <br>
2) What factors affect the popularity of a YouTube video? <br>
   • Which categories of YouTube videos are the most popular?<br>
   • Which video category (e.g. entertainment, gaming, comedy, etc.) has the largest number of trending videos? <br>
   • What are the top 10 most popular tags?<br>
   • What types of tags frequently appear in the most top-trending videos?<br>
   • Which YouTube channels have the largest number of trending videos?<br>
3) What is the best posting time on Youtube to be on the top trending?<br>
   • When were the trending videos usually published? On which days of the week? At which times of the day?<br>
   
 <br>
 
#  Dataset<br>
Mainly three major data processing tasks took place:
<br>
1) Combining video data from 10 countries into one Excel file<br>
2) Each country dataset has a corresponding json file that defines the category id and category name for that country. I extracted and merged 
category names, extracted from the json file, with the original dataset.<br>
3) There were multiple instances of the top trending video during the life of the video. We ensured we kept the latest record of when the video
was trending with already accumulated results for its properties such as likes, dislikes, comments, shares, downloads, etc.<br>
4) Data manipulation such as normalizing the data, converting the datatype of the data, replacing nan with either a suitable number depending on the frequency of the mode value or removing those rows completely if they were very small in number, etc<br>
<br>
<br>

# Insights
<br>
1) Different culture in different countries and the time period can affect certain categories like Entertainment, People&Blogs<br>
2) “Entertainment” has the greatest number of trending videos<br>
3) The highest trending tags are “Funny” and “Comedy”.<br>
4) 45% of top 20 trending channels belong to the “Music” category<br>
5) Hour with the maximum downloads is on average, Tuesday at 5 am<br>
6) The best time to upload to increase chances of trending the video is 5 am on a Friday<br>
7) Most of the trending Youtube videos are published on weekdays rather than weekends.<br>

# Huge Thanks To
1) Professor John Bono, who gave us this humble opportunity as capstone project for his course(Data Processing and Analysis in Python)
<br>
2) Jiakun Luo (Team Member)<br>
3) Wenjing Cui (Team Member)<br>
4) Huyen Nguyen (Team Member)<br>
5) Cindy Chang (Team Member)<br>
