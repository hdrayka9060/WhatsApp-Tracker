# WhatsApp Tracker

This project is a Python-based WhatsApp tracker that monitors the online status of users in your chat box. It utilizes Selenium and Beautiful Soup for web scraping.

## Description

The WhatsApp tracker is part of a larger project aimed at predicting when a given user will appear online. This tracker specifically focuses on logging the times when users in your chat box come online.

## Prerequisites

Before using the tracker, ensure you have the following prerequisites installed:

- Python (version >= 3.6)
- Selenium
- Beautiful Soup
- Web browser driver (e.g., ChromeDriver for Google Chrome)

## Usage
1. Clone the Repository: Clone this repository to your local machine.
2. Configure the Tracker: Open the config.py file and provide your WhatsApp Web login details.
3. Ensure WhatsApp Web Login: Before using the tracker, ensure you are logged in to WhatsApp Web in your web browser.
4. Run the Tracker: Execute the tracker.py script to start monitoring the online status of users in your chat box.
5. View Logs: The tracker will log the times when users come online in a file named "contact_name.txt".

## Notes
- This tracker works on WhatsApp Web. Ensure that you are logged in to WhatsApp Web in your web browser before using the tracker.
- The tracker will continuously monitor the chat box until manually stopped.
- This tracker is aimed for data collection purposes to analyze user online behavior.

## Future Work
- This tracker is part of a larger project aimed at predicting user online status. 
- Future improvements may include machine learning algorithms to analyze online patterns and predict user behavior.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please feel free to open a pull request.
