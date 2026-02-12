# Web-Scraping-mini-project
A small Python project that fetches remote job listings from the Remotive Jobs API, cleans the data, and saves it into a structured CSV file using Pandas.

Features: 1)Fetches live remote job data from Remotive API
          2)Cleans HTML from job descriptions
          3)Extracts key job fields such as title, company, salary, tags, and location
          4)Converts results into a Pandas DataFrame
          5)Exports data to a CSV file for analysis or further use 
          
Tech Stack: 1)Python 3
            2)Requests
            3)Pandas
            4)BeautifulSoup4
            
API Source: Data is pulled from the public Remotive API (https://remotive.com/api/remote-jobs) Clone the repository: git clone https://github.com/your-username/remotive-jobs-scraper.git cd remotive-jobs-scraper

Install dependencies: pip install requests pandas beautifulsoup4

The script will: 1)Fetch remote job listings 
                 2)Clean and structure the data 
                 3)Save a CSV file named jobs.csv in the project directory 
                 
Output: 1)Job ID
        2)Title
        3)Publication Date
        4)Company
        5)Category
        6)Location
        7)Salary
        8)Tags
        9)Job Type
        10)Description
        11)URL 
Example Use Cases: 1)Job market analysis
                   2)Building job dashboards
                   3)Filtering remote opportunities 
                   4)Learning API data extraction with Python
                   
Notes: 1)The API returns a limited number of jobs per request.
       2)Data changes over time since it is live.
       3)No authentication is required for the Remotive API.
       
License: This project is for educational and personal use.
