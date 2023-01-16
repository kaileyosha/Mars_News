# Mars_News
## Project Purpose
  The purpose of this project was to scrape news about Mars as well as relevant data from the internet using a working understanding of HTML and CSS. From there the task was to clean, process, plot, and analyze data about the planet Mars. 
## Deliverable One: Mars News 
  The first deliverable required first that I scrape text elements from a Mars news website. From there a for loop had to be created to iterate through the rows of text elements and pull only relevant information. In this case, relevant was defined as the title of each news article and the short summary. This information was then added to a dictionary in pairs, and appended to a list that when printed would show all relevant titles and summaries. 
## Deliverable Two: Mars Data
  This deliverable began with scraping data from a table in html and converting it to a pandas dataframe without using the read_html function. To do this, the data was first scraped from the table broadly using the tag 'tv' and the class 'data-row' and then it was further broken down in a for loop. After this data was obtained, the task then became making sure all of the data was converted to the correct datatypes for analysis. The deliverable concluded with analyzing multiple variables about the planet mars, graphing the data, and exporting the dataframe into a csv file. 
