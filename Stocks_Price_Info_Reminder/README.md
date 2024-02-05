# Stocks Price Info Reminder

## Description

The Stocks Price Info Reminder provides information and reminders about stock prices and news. This project demonstrates how Python can be used for real-time data monitoring and notifications.

##Working
Constants named with `STOCK` and `COMPANY_NAME` can be changed to user preferences. If provided with API keys and user email/password it works by finding the provided stock symbol's price, and if that price shows an increase or decrease of 5% from the previous day, then a notification with 3 news articles belonging to that stock's parent company is sent via email.

## Technologies Used

This project utilizes:
- The requests library to fetch stock price information from websites
- List manipulation for data processing and analysis
- Email-sending functionality using smtplib module for notifications
