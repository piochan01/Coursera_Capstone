# Coursera_Capstone
Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.

This submission will eventually become your Introduction/Business Problem section in your final report. So I recommend that you push the report (having your Introduction/Business Problem section only for now) to your Github repository and submit a link to it.


# Problem Definition
The objective of this project is to help people who are planning to open a new restaurant in Toronto. The project will try to provide the right location by analysing data related to the demographic, competitors and income of each neighborhood in toronto.


# Datasets and information 

1. Toronto's data contains Demographic, Income per Neighborhood is publicly available on Toronto Government Website below:

   Toronto's Census data is obtained from : https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#8c732154-5012-9afe-d0cd-ba3ffc813d5a

   Toronto Neighborhoods' shapefile is obtained from : https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#a45bd45a-ede8-730e-1abc-93105b2c439f

2. Foursquare API will be used to obtain information about the restaurants of the neighborhoods in Toronto which is used to determine the competitors within the area

3. BeautifulSoup will also be used to scrap data from Wikipedia for information anlaysis regarding Toronto neighbourhoods


# Methodology

Methodology section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, and what machine learnings were used and why.

After getting the dataset from the Toronto Government Website, we will use a business approach to determine the right location to open a restaurant in Toronto.
The total number of neighborhoods in Toronto are 212 as shown from the dataset. Based on the their similarities in features, we will use the K-Means methodology to create and group them into clusters for data analysis. After that we will apply data visualization on the clusters. “Folium” will be used to create interactive map showing the neighborhood clusters in Toronto. 

