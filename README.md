# RAI Content Name Analysis
This project scrapes content titles from RAIplay (Italian national broadcaster's streaming platform) and analyzes the presence of gendered names in the titles using the Claude AI API.

## Overview
The project consists of two main components:

- A web scraper that collects content titles from various RAIplay categories
- An analysis tool that processes these titles to detect the presence of names and their gender
- A clean notebook to remove duplicates (I realized later that contents can belong to more than one category)

## Features

- Scrapes content titles from multiple RAIplay categories (Fiction, Film, Documentaries, etc.)
- Analyzes titles for the presence of:
  - Female first names
  - Male first names
  - Last names
  - Complete female names
  - Complete male names

Includes checkpoint system for reliable long-running analysis
Saves results in CSV format for further analysis

## Requirements

Python 3.10+
Playwright
Beautiful Soup 4
Pandas
Anthropic Claude API access
python-dotenv


The analysis generates a CSV file containing the original titles and analysis results, including:

Presence of different types of names
List of names found in each title
Genre/category of the content

## Contact

For info write to [m.dallastella@proton.me](mailto:m.dallastella@proton.me)