# **New York City Rats Health Problem.**
  
## **Project objectives.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The objective of the project was to analyze the rodent problem, especially rats, in New York City through the databases available in NYC Open Data, to try to find out if the problem is getting better or worse.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this purpose, the following data were analyzed: 
1. ["Rats sightinghs"](https://data.cityofnewyork.us/Social-Services/Rat-Sightings/3q43-55fe), based on 311 Service Requests from 2010 to June 25, 2023, when i downloaded the dataset.
2. ["Rodent inspections"](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj)
3. ["Rats Heat Map"](https://data.cityofnewyork.us/Social-Services/Rats-Heat-Map/g642-4e55), also based on 311 Service Requests from 2010 to June 25, 2023, when i downloaded the dataset.

## **Project findings.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We found that the rat problem is getting worse year after year. In 2021 and 2022, records were broken for rat sightings. This means more calls for complaints. In addition, we noticed that there used to be large concentrations in certain places and now it is more homogeneous. In other words, has spread, causing the problem to become more severe.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On the other hand, rat bites increased and with this, cases of lectospirosis and rat fever. In 2021, there were deaths due to this.

## **Project data collection.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As I mentioned earlier, the project was based on public information available on the NYC Open Data site.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All files are available in the project folder on [GitHub](https://github.com/federicodt/nyc-rat-health-problem).

## **Project data analysis process & notebooks.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I used this notebooks to clean each dataset (Rat sightings, Rodent inspections and Rat heat map) and extract what I needed for my analysis.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I then used the notebooks to browse and analyze the available data. Also, to cross-reference and/or generate new DataFrames.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then, I plotted the findings in Matplotlib, Altair, or Seaborn. The heat maps were made with Folium. Additionally, I made a graph in D3.

## **Learnings and obstacles during the project.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the previous project, my first one, I used an html template for the first time. This time, I copied one that I thought was appropriate for the project and modified it. I hadn't used notebooks before either. In this one I used about five to clean up, analyze, crisscross and generate information. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For plotting the graphics I used Matplotlib, Altair and Seaborn. None of them I had used before. In addition, I did some plotting with Datawrapper and Flourish. Also, I added a graph in D3.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this article I had a lot of problems. First of all, the html template gave me difficulty modifying it. Every time I placed something, other thing went broken. When I inserted the graph made in D3, the 'base.css' collided with the 'style.css'. That gave me a few headaches.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;About the graphics, the ones I made in Altair, which were some, I couldn’t all embed in the 'index.html'. I tried a lot of things, until I found in a forum that happens to be a problem between the latest version of Altair and Chrome. Apparently, The latest Google browser changes do not allow you to embed certain graphics into Altair.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Regarding Altair, I had a hard time modifying it and configuring it to look the way I wanted. The Folium heat maps were also complicated. In all cases, it was the first time I used these tools.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I wanted to do a pretty deep analysis of the information, but time did not allow it. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I think the most difficult thing was the number of errors, obstacles and problems that arose throughout the project. But they also helped me to learn many things.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Thanks to the help of TAs and my colleagues, from whom I also learned a lot, i could finished the project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If I had more time, more skills and more confidence in them, I would have used API or scrapping techniques. Also, I would have made better graphics and a better web page.

## **Proyect link.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Are rats still a problem?](https://federicodt.github.io/nyc-rat-health-problem/)
