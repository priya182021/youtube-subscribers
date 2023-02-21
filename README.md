# youtube-subscribers
# Data Description
Youtube channel: name of the youtube channel.
Subscribers: How many subscribers are there for the youtube channel.
Video views: How many number of views are there for the channel.
Video counts: same user repeats that video number of times. so The number of times that user has repeated the video is number of counts.
Category: in which category the channel is running. either entertainment or buissness or education.
Started: in which year the channel has been started.

# Analysis.
Since the data is misleaded by data type. Subscribers and Video Views are of integer format but since they contain commas Python considered it as string. we need to remove commas from the values of string. so we use df[Column name].str.replace(',','') to remove commas from string. Now we  can change the data type to float or integer.
Using data Preprocessing and feature engineering.
In category we observe url data so we discard that observation.
We then find top 10  channels which are popular.
also we see that T-series channel has highest number of views.
we plot barplot for top 5 Categories.
Also according to start year, how the channel has become popular we observe it by barplot.
correlation matrix is discovered.
