# Auctions-SEE-CAO
Google Sheets Daily Updater
This Python script automates the process of fetching auction data from a specified API and updating a Google Sheet with the retrieved information. It includes features such as:

Dynamic Sheet Creation: Automatically creates a new sheet if it doesn't already exist for each auction.
Data Formatting: Applies formatting to the Google Sheets, including setting header colors, borders, and text styles for better readability.
Daily Updates: Utilizes GitHub Actions to run the script daily, ensuring that the Google Sheet is consistently updated with the latest auction data.
Features
Fetches auction data from a REST API.
Updates Google Sheets with detailed auction information.
Configurable for different auction identifiers.
Easy to set up and run on GitHub Actions for automated execution.
Prerequisites
A Google Cloud project with the Google Sheets API enabled.
OAuth 2.0 credentials stored securely.
Python environment with required libraries listed in requirements.txt.
Getting Started
Clone this repository to your local machine.
Set up your Google Cloud credentials.
Install required dependencies using pip install -r requirements.txt.
Modify the script as needed to customize API URLs and Google Sheets configurations.
Push your code to GitHub and configure the GitHub Actions workflow for daily execution.
Usage
The script is designed to be executed automatically via GitHub Actions. You can manually run it by executing the Python script in your local environment.

License
This project is licensed under the MIT License.
