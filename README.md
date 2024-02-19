# 🎥 YouTube Analysis of Taylor Swift's Page

## 📊 Overview
This project analyzes Taylor Swift's YouTube channel using the YouTube Data API. The analysis includes fetching channel statistics, video details, and comments using Python. Visualizations are created using Seaborn and Matplotlib to understand the channel's performance and engagement metrics.

## 📚 Key Libraries
- `googleapiclient.discovery`: Used to interact with the YouTube API.
- `isodate`: Used to parse and manipulate ISO 8601 durations.
- `dateutil.parser`: Used to parse date strings into datetime objects.
- `pandas`: Used for data manipulation and analysis, particularly for handling the fetched data.
- `seaborn` and `matplotlib.pyplot`: Used for data visualization to gain insights into the channel's performance.

## 📝 Summary of Analysis
- Fetched channel statistics including subscribers, views, and videos.
- Retrieved video details such as title, description, view count, like count, and comment count.
- Analyzed comments for sentiment or engagement metrics.

## 📊 Visualizations
- Created bar charts to show the best and worst-performing videos based on view count.
- Plotted the distribution of views per video using a violin plot.
- Examined the relationship between view counts and engagement metrics like likes and comments using scatter plots.

## 🎯 Conclusion
This analysis provides insights into Taylor Swift's YouTube channel performance, helping to understand viewer engagement and video popularity trends.
