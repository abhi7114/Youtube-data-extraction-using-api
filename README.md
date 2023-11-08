Youtube Data Extraction Using API
This application utilizes the YouTube Data API to extract a comprehensive overview of a specified YouTube channel, including channel statistics, playlist information, and video details. Users can input a channel name, playlist title, or video title to retrieve relevant information.

Extracting Channel Details
Given a channel name, the application retrieves the channel ID, view count, subscriber count, video count, and a list of available playlists.

Accessing Playlist Information
If a user provides a playlist title, the application identifies the corresponding playlist ID and presents a list of playlist items.

Retrieving Video Details
By entering a video title, the application displays detailed information about the first matching video, including title, description, view count, and likes.

Extracting Video Comments
The application retrieves up to 2,000 comments associated with the specified video.

Visualizing Top Videos
Links to the 10 most recent videos for the channel are presented, providing users with direct access to the latest content.

Sentiment Analysis
Sentiment analysis is performed on the retrieved comments using the Vader library. The sentiment of each comment is determined based on its compound attribute. Comments with a compound attribute greater than 0.05 are classified as positive, those with a compound attribute less than -0.05 are categorized as negative, and the remaining comments are labeled as neutral.

API Key Acquisition
To utilize this application, obtain an API key from the Google Cloud Platform Console.

Conclusion
This application effectively extracts and analyzes YouTube data, providing users with insights into channel performance, video content, and audience engagement
