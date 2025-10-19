# ⚽ English Premier League Match Prediction

A machine learning project that predicts English Premier League (EPL) match outcomes using historical data scraped from FBref.com.

## 📋 Overview

This project collects and analyzes Premier League football data to build predictive models for match outcomes. The pipeline includes web scraping, data preprocessing, and machine learning model development.

## 🔧 Technologies Used

- **Python 3.x**
- **Selenium** - Web browser automation for data scraping
- **BeautifulSoup4** - HTML parsing and data extraction
- **Pandas** - Data manipulation and analysis
- **Jupyter Notebook** - Interactive development environment

## 📊 Data Collection

The project scrapes data from [FBref.com](https://fbref.com/en/comps/9/Premier-League-Stats), including:

- Team standings and statistics
- Match scores and fixtures
- Historical performance data
- Venue information (Home/Away)
- Match dates and times

### Web Scraping Features

- Headless Chrome browser automation
- User-agent spoofing to avoid detection
- Automated data extraction from multiple team pages
- Structured data storage using pandas DataFrames

## 📁 Project Structure

```
football_prediction_epl/
├── data_crawl.ipynb    # Web scraping notebook for EPL data
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install selenium beautifulsoup4 pandas requests
```

You'll also need to install ChromeDriver for Selenium:
- Download from [ChromeDriver Downloads](https://chromedriver.chromium.org/downloads)
- Ensure it's in your system PATH

### Usage

1. Clone the repository:
```bash
git clone https://github.com/Eddietrantkt/football_prediction_epl.git
cd football_prediction_epl
```

2. Open the Jupyter Notebook:
```bash
jupyter notebook data_crawl.ipynb
```

3. Run the cells to start scraping EPL data

## 📈 Features

- ✅ Automated data collection from FBref.com
- ✅ Team statistics extraction
- ✅ Match fixture and results scraping
- ✅ Headless browser operation for efficient scraping

## ⚠️ Important Notes

- Please respect FBref.com's terms of service and robots.txt
- Add delays between requests to avoid overwhelming the server
- The scraper uses headless Chrome to minimize resource usage

## 🔮 Future Development

- [ ] Machine learning model implementation
- [ ] Feature engineering from raw data
- [ ] Model evaluation and comparison
- [ ] Prediction API development
- [ ] Real-time match prediction

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**Eddietrantkt**
- GitHub: [@Eddietrantkt](https://github.com/Eddietrantkt)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

⭐ If you find this project useful, please consider giving it a star!
