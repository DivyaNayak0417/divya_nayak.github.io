---
layout: post
title: Automated LinkedIn Job Listing Retrieval and Parsing using Python with BeautifulSoup.
---

<p align="center">
  <img width="800" height="400" src="{{ site.baseurl }}/images/Data_Scientist_job.jpg">
</p>

The objective of this project is to automate the process of fetching job listings from
LinkedIn by specifying job titles and locations using Python libraries. To extract job-specific information from LinkedIn, I employ web scraping techniques to parse the HTML pages, and for this parsing task, I utilize BeautifulSoup.

Beautiful Soup is a library that simplifies the extraction of data from web pages. It functions on top of an HTML or XML parser, offering Pythonic approaches for navigating, searching, and manipulating the parsed content. Below is a glimpse of the HTML page structure that we're working with.

<p align="center">
  <img width="800" height="400" src="{{ site.baseurl }}/images/html_page_for_jobs.jpg">
</p>

From the provided HTML page, I extract specific job-related information for positions located in California. The details I retrieve include:

1. Company Name
2. Job Title
3. Job Location

To obtain this data, I carefully analyze the HTML structure and employ specific tags to isolate the relevant information. The code snippet below demonstrates the tags I've utilized to extract the pertinent details and showcases the corresponding output.

<p align="center">
  <img width="1000" height="400" src="{{ site.baseurl }}/images/code_for_web_scrspping.jpg">
</p>


Output after extracting relevant deatils from HTML page

<p align="center">
  <img width="800" height="400" src="{{ site.baseurl }}/images/web_scrapping_output.jpg">
</p>

You can find the jupyter notebook on my github here <a href="https://github.com/DivyaNayak0417/Webscraping_Python/blob/main/Webscraping_Project.ipynb">Automated LinkedIn Job Listing Retrieval</a>
