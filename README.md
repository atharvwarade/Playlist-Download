# SpotifySync

## Overview
SpotifySync is a Python script designed to help you download songs from your Spotify playlist to your local computer. The script utilizes Jupyter Notebook, Selenium, and BeautifulSoup to automate the process of accessing Spotify web pages, extracting song information, and triggering downloads.

## Prerequisites
Before running the script, make sure you have the following prerequisites:

1) Webdriver Installation: Ensure that you have a webdriver installed on your system. You will need to modify the code to specify the path to your webdriver. Popular choices include ChromeDriver and GeckoDriver (for Chrome and Firefox, respectively).

2) Browser Configuration: The browser you use with the script should support automatic saving of downloads. Note that certain browsers, like Brave, may have additional configurations required for automatic downloads.

3) Spotify Links: The Spotify links in your playlist should directly open in the browser without any pop-up windows or prompts to open the link in the Spotify app.

## Tech Stack
The script is implemented using the following technologies:

1) Jupyter Notebook: Interactive computing environment for running Python code and creating documents.

2) Selenium: Web testing library used for browser automation. In this script, it's employed to navigate Spotify web pages.

3) BeautifulSoup: Python library for pulling data out of HTML and XML files. Used here to parse the HTML content of Spotify pages and extract song information.

## Usage
Open the Jupyter Notebook file containing the script.

Modify the code to specify the path to your webdriver.

Run the script, and it will automate the process of accessing your Spotify playlist, extracting song information, and triggering downloads.

## Disclaimer
Please use this script responsibly and respect the terms of service of the platforms you interact with. Downloading copyrighted material without permission may violate the terms of service of Spotify or other platforms.

