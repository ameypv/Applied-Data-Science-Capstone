# Applied-Data-Science-Capstone
A data science project on segmenting and clustering neighborhoods in Toronto

The first notebook contains code on scraping the Canadian postal code data into a pandas dataframe, and pre-processing the dataframe as per the following conditions:
    - The dataframe will consist of three columns: PostalCode, Borough, and Neighborhood
    - Only process the cells that have an assigned borough. Ignore cells with a borough that is Not assigned.
    - More than one neighborhood can exist in one postal code area. Combine neighbourhoods with the same postal code area
    - If a cell has a borough but a Not assigned neighborhood, then the neighborhood will be the same as the borough.
