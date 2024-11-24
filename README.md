# Data Scraping Project: Yellow Pages IT Services in California

This project scrapes IT services company data from Yellow Pages in California using Python, `requests`, and `BeautifulSoup`. The scraped data includes details such as company names, websites, contact numbers, addresses, categories, and descriptions.

---

## 📝 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [How It Works](#how-it-works)
- [Output](#output)
- [Future Enhancements](#future-enhancements)

---

## 📖 Introduction
This script automates the process of gathering IT services company information from Yellow Pages. It scrapes multiple pages and stores the extracted data into a CSV file for analysis or further use.

---

## ✨ Features
- Scrapes company details like:
  - **Company Name**
  - **Website URL**
  - **Contact Number**
  - **Location/Address**
  - **Industry/Category**
  - **Company Description**
- Handles missing data gracefully.
- Saves output in a **CSV file** for easy access.

---

## 🛠 Technologies Used
- **Python** (Primary programming language)
- **Libraries**:
  - `requests` for sending HTTP requests
  - `BeautifulSoup` for parsing HTML content
  - `pandas` for data manipulation
- **Yellow Pages** as the data source.

---

## ⚙️ Setup and Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
