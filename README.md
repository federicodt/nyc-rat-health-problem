# **New York City Rats Health Problem.**
  
## **Project objectives.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The objective of the project was to analyze the rodent problem, especially rats, in New York City through the databases available in NYC Open Data, to try to find out if the problem is getting better or worse.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this purpose, the following data were analyzed: 
1. ["Rats sightinghs"](https://data.cityofnewyork.us/Social-Services/Rat-Sightings/3q43-55fe), based on 311 Service Requests from 2010 to June 25, 2023, when i downloaded the dataset.
2. ["Rodent inspections"](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj)
3. ["Rats Heat Map"](https://data.cityofnewyork.us/Social-Services/Rats-Heat-Map/g642-4e55), also based on 311 Service Requests from 2010 to June 25, 2023, when i downloaded the dataset.

  

  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The second objective is to cross-check the data of both answers, in order to detect inconsistencies. In case of finding them, verify which is true, which is not, or if both are false.
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The third objective is to detect if the first lady always traveled as a companion of the President of Argentina, Alberto Ángel Fernández. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Finally, graph the findings.

## **Project findings.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The first finding was that the General Secretariat of the Presidency of Argentina lied in its response to the request for access to public information. The agency did not include all the flights of the First Lady and, on the other hand, altered some of the data of several of the flights. This emerged from crossing both answers. The information provided by EANA SE was collected from each airport in the country.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On other side, On the other hand, I found that the first lady used the planes and helicopters of the presidential air fleet during the lockdown for the Coronavirus Pandemic. By law, the first lady cannot use them, because she does not hold any position in the National State. The only exception is if she travels with the President of the Nation and her presence is justified. In addition to all this, there is the aggravating circumstance that public funds were used.

## **Project data collection.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As I mentioned earlier, two requests for access to public information were filed for this project. As a result of these, I obtained two responses, consisting of three files in "Microsoft 'Excel'" format:
1. `SGPN answer 1.csv`: first file of the response from the General Secretariat of the Presidency of the Argentine Nation.
2. `SGPN answer 2.csv`: second file of the response from the General Secretariat of the Presidency of the Argentine Nation.
3. `EANA SE answer.csv`: file of the response from EANA SE.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All files are available in the project folder on [GitHub](https://github.com/federicodt/project1/).

## **Project data analysis process.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;First, I used filters in each of the "Microsoft 'Excel'" spreadsheets to isolate the data from the first lady's flights. In this way, I found only a few.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then, I filtered by aircraft and destinations; mainly Posadas, Misiones, which is the city where the first lady's family lives.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Each flight was crossed-checked against the [agenda of activities of the President of the Argentine Nation](https://www.casarosada.gob.ar/informacion/actividad-oficial), in order to find out if there was any official trip.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Also, each flight, each flight, especially those to Posadas, Misiones, were checked against the first lady's social media accounts: [Instagram](https://www.instagram.com/fabiolaoficialok/), [Facebook](https://www.facebook.com/fabiolaoficialok/) and [YouTube](https://www.youtube.com/channel/UCs4ytErpRkwyD1Gj_LzLliQ).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Moreover, each flight was checked against the [FlightRadar24](https://www.flightradar24.com/) database, especially the search by [airport](https://www.flightradar24.com/data/airports), [aircraft](https://www.flightradar24.com/data/aircraft) and [flights](https://www.flightradar24.com/data/flights).

## **Notebooks.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;No notebooks were used for this project.

## **Learnings and obstacles during the project.**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I started from scratch with HTML and, based on a template, I was able to build the website and, by consulting several web pages, I was able to make modifications. I had never used Flourish and Datawrapper. Not only did I enjoy doing it, but I am beginning to understand the things I can do with these tools. Also, I started to feel less afraid to start a project and to tell a story with data.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If I had more time, more skills and more confidence in them, I would have used Python and Pandas to analyze the data. Besides, I would have used Qgis, to map the data. Also, I would have made better graphics.

## **Proyect link.**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[The illegal flights of the first lady of Argentina, during the Pandemic lockdown](https://federicodt.github.io/project1/)
