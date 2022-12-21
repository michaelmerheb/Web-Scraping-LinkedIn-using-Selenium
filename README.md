# Web-Scraping-LinkedIn-using-Selenium
This is my code to web scrape LinkedIn for Data Science jobs in Barcelona city.

# CODE OBJECTIVE
The following code outlines the process of obtaining certin data regarding all the job postings for the Data Scientist jobs in the Barcelona area that are posted on LinkedIn.
The code first goes about importing the required libraries to setup the environment. Instead of using ```BeautifulSoup```, the code utilizes ```Selenium``` with ```Python```.
The latter library automates the process of accessing LinkedIn, logging in, loading the job search page, and then scraping the LinkedIn website for the necessary data.

The obtained data for every job is the following:
1. Job title
2. Company name
3. Company location
4. The state of the posted job
5. Job posting date
6. Offer url
7. Number of applicants (in integer form)
8. Whether the job is promoted or not (boolean form)
9. Workspace (Hybrid, Remote, On-site, Other)
10. Job seniority
11. Employment type
12. Industry in which the job is in
13. Whether Python is required for the job (boolean form)
14. Whether applying through LinkedIn is an option (boolean form)
15. Number of employees (in integer form)
16. The company's number of followers (in integer form)

After the scraping is completed, the data collected is modified and a ```DataFrame``` is created.
