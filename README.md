# YouTube Channel Analytics: Impact of Upload Timing on Viewer Engagement

## Overview
This project explores the relationship between the timing of video uploads and viewer engagement on YouTube. By analyzing data from multiple channels, the project aims to provide insights into how upload timing affects metrics like views, likes, and subscriber growth.

**Guiding Question:** _"How does the timing of video uploads impact viewer engagement and channel growth?"_

## Key Insights
- **Upload Timing**: Analysis shows significant differences in engagement based on upload time.
- **Video Duration**: Shorter videos may perform better in terms of engagement.
- **Regular Uploads**: Consistency in upload schedule positively impacts viewer engagement.

## Key Insights
- **Regular Upload Schedules:** Channels that consistently upload videos at regular intervals tend to see steady growth in engagement and subscribers.
- **Peak Upload Times:** Uploading videos during peak times (e.g., evenings, weekends) leads to higher initial engagement.
- **Correlation Analysis:** Strong correlations were found between upload timing and engagement metrics, emphasizing the importance of strategic timing for content creators.

## Project Structure
The project is structured as follows:
1. **Data Collection:** Data gathered from the YouTube API, focusing on upload times and engagement metrics.
2. **Data Preparation:** Cleaning and preprocessing of data to ensure accuracy.
3. **Exploratory Data Analysis (EDA):** Initial analysis to understand data distribution and patterns.
4. **Correlation Analysis:** Examination of relationships between upload timing and engagement.
5. **Trend Analysis:** Identification of trends in engagement and growth over time.
6. **Comparative Analysis:** Comparison of timing effects across different channels.
7. **Conclusion:** Summary of findings and actionable insights for content creators.

## Technologies Used
- **Python:** Primary programming language for data analysis.
- **Pandas:** Used for data manipulation and analysis.
- **Seaborn & Matplotlib:** Visualization libraries for creating plots and charts.
- **YouTube Data API v3:** API used to collect data from YouTube.

## Setup Instructions
To run this project locally, follow these steps:

## Instructions for Creating the Conda Environment
To create the Conda environment and install the necessary libraries, follow these steps:

1. Create a New Environment:
   conda create --name youtube-analytics-env python=3.9
2. Activate the Environment:
   conda activate youtube-analytics-env
3. Install the Required Libraries:
   conda install pandas seaborn isodate google-api-python-client
4. Verify the Installation:
   conda list
   Ensure that pandas, seaborn, isodate, and google-api-python-client are listed among the installed packages.
5. Run the Jupyter Notebook:
   jupyter notebook
   Open the notebook and start running the cells.




