# Job Scraping Script

This project contains a Jupyter Notebook to scrape job postings from [merojob.com](https://www.merojob.com) and export the data to CSV files.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/merojob-scraper.git
    cd merojob_scraping
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Install Jupyter Notebook if you haven't already:

    ```bash
    pip install jupyter
    ```

## Usage

1. Start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. Open the notebook `merojob_scraper.ipynb` and run the cells to scrape job postings.

3. The notebook will create two CSV files:
    - `links_to_jobs.csv`: Contains links to individual job postings.
    - `job_informations.csv`: Contains detailed information about each job posting.
