# Youtube-Data-Harvesting-and-Warehousing

This project is a Streamlit web application for harvesting and warehousing YouTube data. It interacts with the YouTube API, stores data in MongoDB, and performs various data analysis queries using PostgreSQL.

***Home Page:***
![image](https://github.com/Kow1214/Youtube-Data-Harvesting-and-Warehousing/assets/121381571/31eba5ab-8771-43ed-a7c1-633a01055e93)

***Data Scrapping part:***
![image](https://github.com/Kow1214/Youtube-Data-Harvesting-and-Warehousing/assets/121381571/0c944625-b21d-40d6-ac7e-fb490b390fbc)

***Data Analyzing part:***
![image](https://github.com/Kow1214/Youtube-Data-Harvesting-and-Warehousing/assets/121381571/0659ad94-0c1f-4047-87b8-3bbcfc34afe7)

Enter the YouTube channel ID(s) and perform data collection, storage, and SQL queries as needed.

## Prerequisites
  ## Install the below packages using pip install in terminal:

    - pymongo
    - psycopg2
    - pandas as pd
    - streamlit as st
    - googleapiclient.discovery import build

  ## To Run the Streamlit app in the terminal:

  **Use command**: streamlit run VYoutubeproject.py
    
    Open the provided link (usually http://localhost:8501) in your web browser.

## Workflow:
  1. Create a Streamlit Dashboard.
  2. Obtain API credentials by enabling YouTube Data API in Google Developers console(**https://developers.google.com/youtube/v3/getting-started**).
  3. Using appropriate API requests extract YouTube Channel, Playlist, Video and Comment data.
  4. Store the extracted YouTube data into MongoDB using the 'pymongo' library.
  5. Migrate the data in MongoDB to SQL tables.
  6. Develop SQL queries within the Streamlit app to retrieve specific information from the SQL database.

## How to use the streamlit application:
  1. To gather and save data, enter the IDs of YouTube channels into the Streamlit app.
  2. Click the appropriate button to migrate data to SQL.
  3. For SQL queries and analysis, use the second tab.

## License

This project is licensed under the [MIT License](LICENSE).



**Thankyou**
