

**Project description:**  The purpose of this project was to tell a story using data visualizations. My team chose to look at the World Happiness Report and visualize the rankings on a map over a 5 year period (2015-2019). Additionally, my team wanted to uncover the nitty-gritty metadata determining whether a country was happy or awaiting happiness.

### Our World Happiness Dashboard is able to filter and change based on the following input: 
- GDP Per Capita
- Family Score
- Life Expectancy
- Government Trust Score 
- Generosity Score

In a nutshell, our process consisted of six steps:
- Create a database to store our data from the World Happiness Report.
- Use geocode to extract coordinates for each country in our data set.
- Use SQL Alchemy to query our database and then merge with coordinates using pandas.
- Convert DataFrame to a JSON file.
- Set up Flask endpoints to read HTML files.
- HTML file sets up Leaflet and reads JavaScript file for data.

### 3. Additional views of the interactive dashboard

<img src="images/world_happiness_image2.png?raw=true"/>

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
