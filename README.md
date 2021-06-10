# Final Report: Consulting services for reallocation
Repository for the Coursera Capstone

## Introduction
A reallocation company works finding the best neighborhood for its clients given a specific city of interest for them to move there. They perform initial interviews to understand their needs and filter the kind of data analysis they will perform.

## Business Problem
To be able to provide its intended services, they need to verify, for a selected group of neighborhoods in the intended city, which one fits better for their clients. To do so, they use the information about leisure and food venues to segment the neighborhoods by clusters and to rank them accordingly.

### Target Audience
The client desires to reallocate to Madrid, but does have the restrictions of being inside M30 (route that revolves the inner districts of the city). For that, only the neighborhoods inside the districts of: Centro, Arganzuela, Retiro, Chamberí, Chamartín, Tetuan and Salamanca will be selected.

## Data
For this endeavor, we will need to gather data from different sources, like:
- Madrid's Community official data about neighborhoods in JSON format
https://datos.comunidad.madrid/catalogo/dataset/barrios_municipio_madrid/resource/b9cf6d43-79b0-400e-82de-ca00de21f6bb
- Geospatial data about the neighborhoods in Madrid using Geocoders
- Foursquare API data about venues based on the location of the neighborhoods
