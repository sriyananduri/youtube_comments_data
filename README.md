The youtube_data.ipynb file does the following:
1) Gets the comments from particular playlist IDs between a range of dates. First, it finds the video IDs from the playlists which fall in the give range of dates. Then, from each video ID, 15k comments are saved which fall under a given range of dates. Along with the comments, attributes like timestamp, publishing date, username of the author of the comment, number of likes for that comment, video ID is also taken.
2) Get video statistics from each video ID. This includes comment count, like count, and view count.
