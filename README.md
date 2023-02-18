# youtube-subscribers
# Data Description
Youtube channel: name of the youtube channel.
Subscribers: How many subscribers are there for the youtube channel.
Video views: How many number of views are there for the channel.
Video counts: same user repeats that video number of times. so The number of times that user has repeated the video is number of counts.
Category: in which category the channel is running. either entertainment or buissness or education.
Started: in which year the channel has been started.

# Analysis.
as the data is misleaded by data type we need to remove commas from the values of string. so we use df[Column name].str.replace(',',''). Now we  can change the data type to float or string.
Using data Preprocessing and feature engineering found which channel is most popular,
bar plot and 
correlation matrix.
