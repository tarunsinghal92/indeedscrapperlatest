# Indeed Job Scraper (Latest)

Indeed Job Scraper for multiple cities and job roles. This is an updated version of code presented by Michael Salmon in https://medium.com/@msalmon00/web-scraping-job-postings-from-indeed-96bd588dcb4b with added functionality of fetching full text from job source.

## How to Run

Normal, 

> python main.py

Background, 

> nohup python main.py &

## Logs

Logs will be gerenated in **log.txt** file. Install watch to keep a track while running scraper in background.

> watch tail -n 30 log.txt

## Output

Files with prefix jobs_[num].csv would be generated, where **num** represent the index of the two loops running for fetchign data.
