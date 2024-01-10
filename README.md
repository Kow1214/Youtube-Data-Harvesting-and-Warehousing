# Youtube-Data-Harvesting-and-Warehousing
This project is a Streamlit web application for harvesting and warehousing YouTube data. It interacts with the YouTube API, stores data in MongoDB, and performs various data analysis queries using PostgreSQL.
![image](https://github.com/Kow1214/Youtube-Data-Harvesting-and-Warehousing/assets/121381571/5a5df876-7f5e-4fa9-8485-c0f89a70e1ca)
Enter the YouTube channel ID(s) and perform data collection, storage, and SQL queries as needed.

## Prerequisites

  ## Install the below packages using pip install in terminal:

    - pymongo
    - psycopg2
    - pandas as pd
    - streamlit as st
    - googleapiclient.discovery import build

  ## To Run the Streamlit app in the terminal:

    **streamlit run VYoutubeproject.py**
    
    Open the provided link (usually http://localhost:8501) in your web browser.


## Workflow:
1. Create a Streamlit Dashboard.
2. Obtain API credentials by enabling YouTube Data API in Google Developers console(**https://developers.google.com/youtube/v3/getting-started**).
3. Using appropriate API requests extract YouTube Channel, Playlist, Video and Comment data.
4. Store the extracted YouTube data into MongoDB using the 'pymongo' library.
5. Migrate the data in MongoDB to SQL tables.
6. Develop SQL queries within the Streamlit app to retrieve specific information from the SQL database.

## How to use streamlit app:
1. Input YouTube channel IDs in the Streamlit app to collect and store data.
2. Migrate data to SQL by clicking the corresponding button.
3. Use the second tab for SQL queries and analysis.


## License

This project is licensed under the [MIT License](LICENSE).

