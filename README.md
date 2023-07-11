# **New York City Rats Health Problem.**
  
## **Project objectives.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The objective of the project was to analyze the rodent problem, especially rats, in New York City through the databases available in NYC Open Data, to try to find out if the problem is getting better or worse.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this purpose, the following data were analyzed: 
1. ["Rats sightinghs"](https://data.cityofnewyork.us/Social-Services/Rat-Sightings/3q43-55fe), based on 311 Service Requests from 2010 to June 25, 2023, when i downloaded the dataset.
2. ["Rodent inspections"](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj)
3. ["Rats Heat Map"](https://data.cityofnewyork.us/Social-Services/Rats-Heat-Map/g642-4e55), also based on 311 Service Requests from 2010 to June 25, 2023, when i downloaded the dataset.

## **Project findings.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We found that the rat problem is getting worse year after year. In 2021 and 2022, records were broken for rat sightings. This means more calls for complaints. In addition, we noticed that there used to be large concentrations in certain places and now it is more homogeneous. In other words, has spread, causing the problem to become more severe.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On other side, On the other hand, I found that the first lady used the planes and helicopters of the presidential air fleet during the lockdown for the Coronavirus Pandemic. By law, the first lady cannot use them, because she does not hold any position in the National State. The only exception is if she travels with the President of the Nation and her presence is justified. In addition to all this, there is the aggravating circumstance that public funds were used.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On the other hand, rat bites increased and with this, cases of lectospirosis and rat fever. In 2021, there were deaths due to this.

## **Project data collection.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As I mentioned earlier, the project was based on public information available on the NYC Open Data site.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All files are available in the project folder on [GitHub]([https://github.com/federicodt/project1/](https://github.com/federicodt/nyc-rat-health-problem)).

## **Project data analysis process.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;First, I used filters in each of the "Microsoft 'Excel'" spreadsheets to isolate the data from the first lady's flights. In this way, I found only a few.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then, I filtered by aircraft and destinations; mainly Posadas, Misiones, which is the city where the first lady's family lives.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Each flight was crossed-checked against the [agenda of activities of the President of the Argentine Nation](https://www.casarosada.gob.ar/informacion/actividad-oficial), in order to find out if there was any official trip.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Also, each flight, each flight, especially those to Posadas, Misiones, were checked against the first lady's social media accounts: [Instagram](https://www.instagram.com/fabiolaoficialok/), [Facebook](https://www.facebook.com/fabiolaoficialok/) and [YouTube](https://www.youtube.com/channel/UCs4ytErpRkwyD1Gj_LzLliQ).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Moreover, each flight was checked against the [FlightRadar24](https://www.flightradar24.com/) database, especially the search by [airport](https://www.flightradar24.com/data/airports), [aircraft](https://www.flightradar24.com/data/aircraft) and [flights](https://www.flightradar24.com/data/flights).

## **Notebooks.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I used this notebooks to clean each dataset (Rat sightings, Rodent inspections and Rat heat map) and extract what I needed for my analysis.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I then used the notebooks to browse and analyze the available data. Also, to cross-reference and/or generate new DataFrames.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then, I plotted the findings in Matplotlib, Altair, or Seaborn. The heat maps were made with Folium. Additionally, I made a graph in D3.

## **Learnings and obstacles during the project.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I started from scratch with HTML and, based on a template, I was able to build the website and, by consulting several web pages, I was able to make modifications. I had never used Flourish and Datawrapper. Not only did I enjoy doing it, but I am beginning to understand the things I can do with these tools. Also, I started to feel less afraid to start a project and to tell a story with data.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If I had more time, more skills and more confidence in them, I would have used Python and Pandas to analyze the data. Besides, I would have used Qgis, to map the data. Also, I would have made better graphics.

## **Proyect link.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[The illegal flights of the first lady of Argentina, during the Pandemic lockdown](https://federicodt.github.io/project1/)
