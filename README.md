# Unit 6 - Pythonic Monopoly: Rental Analysis & Dashboard

Harold's company has just started a new Real Estate Investment division to provide customers with a broader range of portfolio options. Harold was tasked with building a prototype dashboard and needs help. 

The real estate team wants to trial this initial offering with investment opportunities for the San Francisco market. 

The goal of this dashboard is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.

Rental Analysis

The first step to building the dashboard is to work out all of the calculations and visualizations in an analysis notebook called  rental_analysis.ipynb

Dashboard

The Panel library is used to build an interactive dashboard for all of the visualizations. 

Within dashboard.ipynb, each visualization exists in separate functions (1 function per visualization). the Idea is to make it easier to build and modify the layout later. 

Each function returns the plot figure in a format that Panel can use to plot the visualization.

NOTE: Remember that in order to create maps visualizations using Plotly Express, you will need to create an account at mapbox ( https://www.mapbox.com/) and create an access token: https://docs.mapbox.com/help/how-mapbox-works/access-tokens/#creating-and-managing-access-tokens .

Enjoy! 