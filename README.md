# Hacker News Headlines Email Automation

This Python automation project scrapes the latest news from [Hacker News](https://news.ycombinator.com/) and sends the top headlines to a specified email address.

## 📌 Project Overview

The project performs the following steps:

1. Fetch news headlines from the Hacker News front page  
2. Scrape content such as the title and link of each news item  
3. Build the email body and format content  
4. Authenticate the sender's email using SMTP  
5. Send the email to the recipient  

## 📦 Required Libraries

To set up the environment, you'll need the following libraries:

- `requests` – for making HTTP requests  
- `bs4` (BeautifulSoup) – for web scraping  
- `smtplib` – for sending emails using SMTP  
- `email.mime` – for creating the email body structure  
- `datetime` – for including the current date and time in the email  

### 🔧 Installation

You can install the required packages using pip:

```bash
pip install bs4 requests
```
For macOS users, use:

```bash
pip3 install bs4 requests
```

> **Note:** The `smtplib`, `email`, and `datetime` modules are part of Python’s standard library and do not require installation.

# 📧 Contact

For questions or suggestions, feel free to reach out at aliyannshaikhh@gmail.com.
