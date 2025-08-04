# SpaceX Falcon 9 Launch Analysis

## Overview

This project is part of the IBM Data Science Professional Certificate, specifically within the 10th course titled "Applied Data Science Capstone." The primary objective is to perform data wrangling, data visualization, and exploratory analysis on SpaceX Falcon 9 launch records to determine the success rate of SpaceX launches under various conditions.

## Objective

- Collect, clean, and analyze launch data.
- Identify key factors that influence successful Falcon 9 launches.
- Use visualizations to communicate insights effectively.
- Apply data science skills in a practical, real-world scenario.

## Project Structure

```text
SpaceX_Falcon9_Analysis/
│
├── LICENSE
├── README.md
├── jupyter-labs-spacex-data-collection-api.ipynb
├── jupyter-labs-webscraping.ipynb
├── labs-jupyter-spacex-Data wrangling.ipynb



## Notebooks Description

### 1. Data Collection (API)
- Utilizes the SpaceX REST API to collect historical Falcon 9 launch data.
- Converts JSON responses into structured data using `pandas`.

### 2. Web Scraping
- Scrapes supplementary information such as launch sites and payload mass from Wikipedia.
- Parses HTML content using `BeautifulSoup`.
- Integrates with API data to enrich the dataset.

### 3. Data Wrangling
- Merges and cleans the combined datasets.
- Handles missing values, formats timestamps, and standardizes fields.
- Prepares a final dataset suitable for downstream analysis and visualization.

## Technologies Used

- **Languages:** Python
- **Libraries:** `pandas`, `requests`, `BeautifulSoup`, `json`, `datetime`
- **Platform:** JupyterLab on IBM Skills Network Labs
- **Tools:** Git & GitHub
- **Data Sources:** SpaceX API, Wikipedia

## Key Skills Practiced

- REST API interaction
- HTML parsing and web scraping
- Data wrangling and cleaning
- Working with Jupyter Notebooks
- Git version control and project structuring
- Exploratory Data Analysis (EDA)

## Author

This repository was created as part of the capstone requirement for the **IBM Data Science Professional Certificate** on Coursera.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
