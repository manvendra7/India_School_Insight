# India_School_Insight
Most parents ask others which school is better for their children. So here we are trying to solve this problem of identifying good schools so that it could help parents to decide the good school for their childs.

## Data Science Process
* Data Ingestion
* Hypothesis Generation
* Data Cleaning and Visualization
* Hypothesis Testing 
* Model Building 
* Model Deployment

## Data Collection 
We have Scrapped the Data From https://schools.org.in/ for the schools in state of Uttar Pradesh. There are around 2.5 M schools in Uttar Pradesh. The challenge was to build the crawler to scrape the data from hirerarchy of pages. 

  **Building Crawler**
  - Get list of all the Districts
  - From all the Districts Build a crawler to get the link of all the Blocks
  - Crawl over all the Blocks link to get the link of all the Clusters
  - Crawl over all the Clusters link to get the link of all the schools
  - From all the school links scrape the needed information.
  - Store the data in csv file.
