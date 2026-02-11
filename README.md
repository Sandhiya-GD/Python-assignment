# Python-assignment
Python assignment 
# Python Data Collection Tool

## 📌 Overview

This project is a Python-based data collection tool developed as part of a technical assignment.

It collects public data from:

- A website using HTML scraping  
  👉 https://quotes.toscrape.com

- A public API using REST calls  
  👉 https://api.github.com/search/repositories

The collected data is normalized and exported into a single structured JSON file.

The implementation focuses on reliability, error handling, logging, and production-ready practices.

---

## ⚙️ Features

- Website scraping with pagination
- GitHub API consumption with pagination
- Configurable User-Agent header
- Optional GitHub API authentication
- Rate limit handling
- Structured logging
- Graceful failure handling
- Google Colab compatible
- Single JSON output

---

## 🛠️ Installation

### Prerequisites
- google colab
- pip

### Install Dependencies

```bash
pip install requests beautifulsoup4
