# Exogenous Variables Extraction
Repository for extracting data for different commonly used exogenous features.
The repository consists of the following files
  - **Feature_list.csv** : Input file for web-scraping which contains the details for the variables like feature name, website URL for extracting data and the HTML elements to be used for scraping in the web scraping python script
  - **exog_variables.csv** : Final output file after a web-scraping execution which will have daily updated data for all the variables
  - **requirements.txt** : File containing the python dependencies for executing the web scraping script
  - **run_summary.json** : Output file giving a summary of when the last web-scraping happend along with failed extraction URLs if any
  - **web_scraping.ipynb** : Main execution script for extracting and updating the data for exogenous features
  - **web_scraping_jupyter_workflow.yml** : YAML file for triggering execution of web scraping script with the help of a cron job triggered using Github Actions

For more details, please refer this confluence page [Exogenous Features](https://blend360.atlassian.net/wiki/spaces/DSDH/pages/386007649/Exogeneous+Features) 
