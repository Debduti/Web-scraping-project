# Web-scraping-project
Objective of the project:

This project scraped Indeed website for open Data Analyst positions in and around Toronto,Canada. We extract information about various fields like Job Title,Location,Company Name,Keywords or Job description and Date of posting and that information is downloaded into a CSV file.

Tools Used:
1. Beautifulsoup
2. Pandas

Methodology:

We go to the Indeed Canada website and run a generic search for Data Analyst openings. We grab the URL and use that in our code to parse the requisite html tags- <div> and <span>.
We create a list of a few cities we want to check out job openings for. We pick up the information present for Job Title,Company Name,Job Summary,and Date of posting, and arrange them in contiguous columns. We can add or remove as many columns as we want to. We loop through all the openings for all the cities in the list and save them in a CSV file.
