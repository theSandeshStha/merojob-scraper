# Job Scraping Script

This project contains a script to scrape job postings from [merojob.com](https://www.merojob.com) and export the data to CSV files.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/merojob_scraper.git
    cd merojob_scraper
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script to scrape job postings:

    ```bash
    python merojob_scraping.ipynb
    ```

2. The script will create two CSV files:
    - `links_to_jobs.csv`: Contains links to individual job postings.
    - `job_informations.csv`: Contains detailed information about each job posting.

