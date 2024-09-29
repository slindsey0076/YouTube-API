# YouTube-API
YouTube API Data Analysis

This project uses the YouTube Data API to fetch and analyze data from specific YouTube channels. The code is designed to retrieve channel statistics, video information, and other relevant metrics, and visualize the data using Python.

Key Features:
- API Integration: Utilizes the Google YouTube API (googleapiclient.discovery) to pull real-time data from YouTube channels.
- Data Handling: pandas is used to manage and manipulate the data, making it easier to process.
- Channel-Specific Analysis: By specifying a YouTube channel ID (currently set to LinusTechTips), the script pulls video metadata such as title, upload date, and view counts.
- Visualization: The project leverages seaborn and matplotlib to create data visualizations, providing insights into trends and patterns within the retrieved data.
- JSON Display: Uses IPython.display to display raw JSON output for easy inspection.

Getting Started:
1. Obtain a YouTube Data API key from Google.
2. Add your desired channel ID(s) to the script.
3. Run the notebook to fetch data and generate visualizations.

This project provides a foundation for analyzing YouTube channel performance and video metrics using Python.
