# Scholarship Scraper and Excel Writer

## Description
This script scrapes scholarship information from the Grambling State University financial aid website and writes it to an Excel file.


![Result](https://github.com/Jemajr/Web-Scraper-GSU-Scholarship-Info-/blob/main/images/Scholarships_Excel.png "Result")


## How it Works
1. Sends a GET request to the URL:  [https://www.gram.edu/finaid/scholarships/privatescholar.php](https://www.gram.edu/finaid/scholarships/privatescholar.php)
2. Parses the HTML content using BeautifulSoup.
3. Extracts scholarship headings and links from the page.
4. Writes the scholarship information to an Excel file named `my_Scholarships.xlsx`.

## Output
The script creates an Excel file with two columns:
- **Scholarships**: The name of the scholarship.
- **Link to apply**: The URL to apply for the scholarship.

The Excel file is formatted with bold headers and adjusted column widths for readability.
