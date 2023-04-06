

**Project description:**The purpose of this project was to tell a story using data visualizations. My team chose to look at the World Happiness Report and visualize the rankings on a map over a 5 year period (2015-2019). Additionally, my team wanted to see the metadata for each country to see what factors are leading to their happiness or lack thereof.

### The Happiness Score factors were determined via some of the following measures: 
- GDP Per Capita
- Family Score
- Life Expectancy
- Government Trust Score 
- Generosity Score

In a nutshell, our process consisted of six steps:
  (1) Create a database to store our data from the World Happiness Report.
  (2) Use geocode to extract coordinates for each country in our data set.
  (3) Use SQL Alchemy to query our database and then merge with coordinates using pandas.
  (4) Convert DataFrame to a JSON file.
  (5) Set up Flask endpoints to read HTML files.
  (6) HTML file sets up Leaflet and reads JavaScript file for data.

### 3. Additional views of the interactive dashboard

<img src="images/world_happiness_image2.png?raw=true"/>

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
