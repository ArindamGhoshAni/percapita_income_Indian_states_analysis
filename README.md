# percapita_income_Indian_states_analysis

This project focuses on visualizing and analyzing the per capita income of Indian states using a choropleth map. It extracts data from a website and creates a geographical chart that differentiates the income levels across various states. The project aims to provide insights into the economic disparities and distribution of wealth in different regions of India.

Table of Contents
Introduction
Requirements
Methodology
Results
Introduction
The per capita income is an essential economic indicator that measures the average income earned per person in a specific region. This project extracts data from a specific website that lists the per capita income of Indian states and creates a choropleth map using the extracted data. The choropleth map visually represents the income levels across different states, enabling users to understand the income disparities and patterns in India.

Requirements
To run this project, you need the following requirements:

Python 3.9.0
BeautifulSoup
Requests
Pandas
Matplotlib
Geopandas
Methodology
Using web scraping techniques, the script fetches the per capita income data from the provided website. It parses the HTML content of the webpage using BeautifulSoup. The extracted data is then processed and transformed into a Pandas DataFrame for further analysis. The shapefile containing the geographical boundaries of Indian states is read using the Geopandas library. The per capita income data is merged with the shapefile based on the state names. The choropleth map is created using the merged data, where colour intensity represents the income levels of the states. State numbers and names are added to the map for better identification. The resulting visualization is displayed using Matplotlib.


Results
The project generates a choropleth map that visualizes the per capita income of Indian states. The map clearly represents the income disparities and patterns across different regions. Users can easily identify states with higher or lower income levels, allowing for a better understanding of the economic landscape in India.

