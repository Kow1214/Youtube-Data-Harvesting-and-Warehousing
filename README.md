# Youtube-Data-Harvesting-and-Warehousing
This project is a Streamlit web application for harvesting and warehousing YouTube data. It interacts with the YouTube API, stores data in MongoDB, and performs various data analysis queries using PostgreSQL.
![image](https://github.com/Kow1214/Youtube-Data-Harvesting-and-Warehousing/assets/121381571/5a5df876-7f5e-4fa9-8485-c0f89a70e1ca)
**Features**
- **YouTube Data Collection:**
  - Fetches details about a specified YouTube channel including subscriptions, views, and videos.
  - Retrieves information about playlists associated with the channel.
  - Extracts video details, including statistics, tags, and comments.

- **Data Storage:**
  - Stores collected data in MongoDB for efficient and flexible document storage.
  - Migrates data to PostgreSQL tables for structured relational storage.

- **SQL Data Analysis:**
  - Executes SQL queries to derive insights from the stored data.
  - Example queries include finding the most viewed videos, channels with the most videos, etc.

