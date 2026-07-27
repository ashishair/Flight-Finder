# Cheap-Flights-Finder
✈️ Cheap Flights Finder

A Python-based flight tracking and alert system that automates the search for low-cost flights and notifies users in real-time. The project integrates multiple APIs and tools to streamline flight data collection, management, and notification.
🚀 Features

    🔍 Flight Search Automation using Amadeus API

    📊 Data Management with Google Sheets API via Sheety

    📱 Real-time Alerts through Twilio API

    📧 Email Notifications using smtplib

    👤 User Behavior Analysis and tailored notifications

    🧱 Object-Oriented Design for modular, maintainable, and scalable code

    💸 Saves users money by identifying and alerting on early, low-fare bookings

🧰 Tech Stack

    Programming Language: Python

    APIs Used:

        Amadeus (Flight data)

        Sheety (Google Sheets integration)

        Twilio (SMS alerts)

    Libraries/Tools:

        requests, datetime, smtplib

        Google Sheets as a lightweight database

    Design Principles:

        Object-Oriented Programming (OOP)

        DRY (Don't Repeat Yourself) and modular architecture

📌 How It Works

    FLow of the Program can be understood through from this image.

   <p align="center">
  <img src="Images/Flow of the Program.png" alt="Program Flow" width="600">
   </p>


    Flight Data Initialization:
    User inputs cities and preferred travel details in a Google Sheet.

    IATA Code Lookup:
    The script fetches IATA codes via Amadeus API and stores them in the sheet.
  <p align="center">
  <img src="Images/Google Sheet.png" alt="Program Flow" width="600">
   </p>

    Price Check:
    The Amadeus API is used to fetch flight prices and availability.

    Alert Trigger:
    If a price falls below a set threshold, the system:

        Sends an SMS via Twilio

        Sends an email with flight details

    Logging and Monitoring:
    All interactions and changes are logged for user behavior analysis and optimization.

📈 Benefits

    Automates tedious flight searches

    Reduces human error in tracking best deals

    Saves users money with early-bird alerts

    Reduces manual work by 80% through automation
