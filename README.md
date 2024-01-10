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
## Usage

1. **Prerequisites:**
   - Python (3.6 or higher)
   - MongoDB
   - PostgreSQL

2. **Installation:**
   - Clone the repository:
     ```bash
     git clone <repository_url>
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Running the Application:**
   - Run the Streamlit app:
     ```bash
     streamlit run VYoutubeproject.py
     ```
   - Access the app in your web browser.
   - Enter the YouTube channel ID(s) and perform data collection, storage, and SQL queries as needed.

## Code Structure

- `VYoutubeproject.py`: Main Streamlit app script.
- `requirements.txt`: List of Python dependencies.

## Dependencies

- pymongo
- psycopg2
- pandas
- streamlit
- googleapiclient

## Contributing

If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

