
# Web Scraping Data Science Jobs

## Overview
The primary objective of this project is to design and implement a specialized web scraping tool tailored for extracting and analyzing data science job listings from a chosen online platform. The tool will focus on collecting essential details such as job titles, company names, experience requirements, salary ranges, and locations, offering valuable insights into the current data science job market landscape.

## Key Tasks
The Key steps for the proper execution of the projects are
- Source Selection 
- Web Scraping Precision
- Data Extraction 
- Data Organization
- Insights Generation
- Visualization 


##  Skills
- Python (Numpy, Pandas)
- Beautiful Soup, Scrapy
- Matplotlib, Seaborn
- Data handling, Data Analysis


## How to Use
1. Clone the repository to your local machine.
2. Open the Collab file in Jupyter notebook or VBS
3. Explore the various visualizations and filters to gain insights into e-commerce performance.
## Approach for the Scraping

    1. Import Necessary Libraries

    2. Utilize the BeautifulSoup library to parse and navigate HTML content for web scraping tasks.

    3. Define a sample HTML snippet representing a job listing to be used as the source for data extraction.

    4. Instantiate a BeautifulSoup object to represent and interact with the HTML content, enabling parsing and navigation through the HTML structure.

    5. Locate and extract the text content of the h1 and h2 tags representing the job title and company name, respectively, using the find() method.

    6. Identify the li tag containing the experience details by specifying a class filter. Utilize the stripped_strings attribute to retrieve all text content within the tag and concatenate them to obtain the required experience information.

    7. Locate the next li tag after the experience tag to extract the salary details. Retrieve the text content of the tag and remove any leading/trailing whitespaces to obtain the salary range.

    8. Search for the li tag containing the location details by identifying a tag with a 'title' attribute. Extract the value of the 'title' attribute to obtain the location information and remove any leading/trailing whitespaces.

    9. Display the extracted details in a structured format to provide a comprehensive view of the job title, company name, experience, salary, and location.

## Demo

.
