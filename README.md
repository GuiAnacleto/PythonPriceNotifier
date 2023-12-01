# Web Price Tracker

Web Price Tracker is a dynamic Python project tailored for savvy online shoppers. This tool simplifies the often tedious process of price monitoring, empowering users to make informed purchasing decisions. With an emphasis on user convenience, it employs web scraping techniques, primarily leveraging BeautifulSoup and Scrapy, to extract real-time pricing information from specified product URLs.

## Project Structure

Web-Price-Tracker/
│
├── src/
│ ├── main.py
│ ├── scraper/
│ │ ├── init.py
│ │ ├── web_scraper.py
│ │
│ ├── storage/
│ │ ├── init.py
│ │ ├── data_storage.py
│
├── tests/
│ ├── test_web_scraper.py
│ ├── test_data_storage.py
│
├── requirements.txt
├── .gitignore
├── LICENSE
├── README.md


- **src:** Contains the main application code.
  - **main.py:** Entry point for the application.
  - **scraper:** Module for web scraping functionality.
    - **web_scraper.py:** Implementation of web scraping logic.
  - **storage:** Module for data storage functionality.
    - **data_storage.py:** Implementation of data storage logic.

- **tests:** Unit tests for the project.
  - **test_web_scraper.py:** Tests for the web scraping functionality.
  - **test_data_storage.py:** Tests for the data storage functionality.

- **requirements.txt:** List of project dependencies.

## Key Features

### Product Selection
Users can effortlessly input URLs of their preferred products, initiating the tracking process.

### Data Extraction
Utilizing advanced web scraping, the tool extracts comprehensive data, focusing on current prices, ensuring users stay up-to-date.

### Data Storage
The project incorporates a robust system for storing historical pricing data, enabling users to analyze trends over time.

### Price Drop Notification
To enhance user engagement, a notification system alerts users when a product's price falls below a user-defined threshold.

### User Interface (Optional)
For a seamless user experience, the tool optionally provides a user interface using Tkinter or Flask, making interaction intuitive.

## Usage

1. **Clone the Repository:**

git clone https://github.com/your-username/Web-Price-Tracker.git

2. **Install Dependencies:**

pip install -r requirements.txt

3. **Run the Main Script:**

python main.py

4. **Stay Informed:**
Monitor your favorite products effortlessly and make data-driven shopping decisions with Web Price Tracker.

## Note

Ensure compliance with the Terms of Service of targeted websites to maintain ethical scraping practices. Contributions, feedback, and feature suggestions are warmly welcomed.

Feel free to customize, contribute, report issues, or suggest improvements. Happy shopping with Web Price Tracker! 🛍️💻
