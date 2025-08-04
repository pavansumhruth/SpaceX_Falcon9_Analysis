# SpaceX Falcon 9 Launch Analysis

## Overview

This project is part of the IBM Data Science Professional Certificate, specifically within the 10th course titled **"Applied Data Science Capstone."** The goal is to analyze SpaceX Falcon 9 launch records using data science techniques to determine the success rate of launches under various conditions.

## Objective

- Collect, clean, and analyze SpaceX launch data
- Identify key factors that influence successful Falcon 9 launches
- Communicate findings using visualizations and data storytelling
- Apply real-world data science workflows

## Project Structure

```text
SpaceX_Falcon9_Analysis/
│
├── LICENSE
├── README.md
├── jupyter-labs-spacex-data-collection-api.ipynb
├── jupyter-labs-webscraping.ipynb
├── labs-jupyter-spacex-Data wrangling.ipynb
```
## Notebooks

### 1. Data Collection (API)
- Retrieves launch data using the SpaceX REST API
- Parses JSON responses and converts them to structured tabular data using `pandas`

### 2. Web Scraping
- Scrapes supplementary launch data (e.g., payload mass, launch site info) from Wikipedia using `BeautifulSoup`
- Integrates it with SpaceX API data to enrich the dataset

### 3. Data Wrangling
- Merges and cleans multiple datasets
- Prepares final dataset for analysis and visualization

## Technologies Used

- **Programming:** Python (`pandas`, `requests`, `BeautifulSoup`)
- **Notebook Environment:** Jupyter Notebooks via IBM Skills Network Labs
- **Data Sources:** SpaceX REST API, Wikipedia
- **Tools:** Git & GitHub
- **Visualization (Later stages):** `matplotlib`, `seaborn`

## Key Skills Practiced

- API interaction and JSON parsing
- Web scraping and HTML parsing
- Data cleaning and transformation
- Exploratory data analysis (EDA)
- Git version control and remote collaboration via GitHub

## Author

This repository was developed as part of the Capstone project in the IBM Data Science Professional Certificate on Coursera.

## License

This project is licensed under the [MIT License](LICENSE).
