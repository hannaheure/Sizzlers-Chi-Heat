# Sizzlers-Chi-Heat
This is a repository for our final project.

# The Project and How We Executed It

## Article for Our Project: 
- https://www.wbez.org/stories/more-chicagoans-lacked-heat-in-january-than-any-month-since-2019-amid-historic-cold/1867a9ae-61fb-48a7-8d3e-24cdcedce594

## Brief Description of the Project and Explaining our git scraper’s execution:
- The goal of our project was to recreate and automate the analysis of heat complaints in Chicago from the article above. We also needed to recreate each visualization in the story (two graphs) with Datawrapper.

- The "final_analysis" notebook contains a comprehensive view of all the code we used for this whole project. We used the "final_analysis" notebook to make sure we had everything in the python requirements checklist and the correct data for our graphs. After having the code we needed to recreate the graphs in the article, we created our graphs on Datawrapper by linking the data from our repo to our datawrapper graphs and then automated it by using a Git Scraper. We have automated the data and graphs to update once a month on the first of every month.

- We ended up creating 3 graphs
    - Graph 1 shows the the number of heat violations (AKA no-heat complaints) by month and year obtained via data from the Department of Buildings
    - Graph 2 is a map showing the number of heat complaints within each Chicago ward
    - Graph 3 is a map showing the number of heat complaints within each Chicago police district

# Describing each dataset in the project:
## Building violations dataset
- Description:
  - Violations issued by the Department of Buildings from 2006 to the present
- Where it came from:
  - Data provided by City of Chicago but came from the Department of Buildings
- How often it is updated:
  - Daily
- Period of data:
  - From January 2006 to present
  
## Ward dataset
- Description:
  - Ward boundaries in Chicago from May 2015 to May 2023
- Where it came from:
  - Data provided by City of Chicago
- How often it is updated:
  - As needed
- Period of data:
  - From May 2015 to May 2023
  
## Police dataset
- Description:
  - Current police district boundaries in Chicago
- Where it came from:
  - Data provided by City of Chicago but came from Police (owner)
- How often it is updated:
  - As needed, which is when police district boundaries are revised and implemented
- Period of data:
  - From December 2012 to July 2018
    - Note: The data is current since there has not been any change regarding the police district boundaries since 2018

# Links to Our Graphs

- Graph 1 Link: [(https://www.datawrapper.de/_/wvyxQ/)](https://www.datawrapper.de/_/wvyxQ/)

- Graph 2 Link: [(https://www.datawrapper.de/_/wvyxQ/)](https://www.datawrapper.de/_/PucTO/)

- Graph 3 Link [(https://www.datawrapper.de/_/wvyxQ/)](https://www.datawrapper.de/_/zeCDx/)
