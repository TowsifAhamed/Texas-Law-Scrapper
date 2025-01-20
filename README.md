# Texas-Law-Scrapper

## Overview
A Python script to scrape Texas law chapters from the official statutes website and save them into a single text file.

## Features
- Dynamically generates chapter URLs.
- Scrapes and consolidates all chapters into one file.

## Requirements
- Python 3.6+
- Libraries: `requests`, `beautifulsoup4`

## Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the script:
   ```bash
   python texas_law_scraper.py
   ```
3. Output is saved in `all_texas_tax_chapters.txt`.

## Notes
- Handles HTTP errors and logs skipped chapters.
- Check URLs for proper formatting if errors occur.

## License
MIT License

