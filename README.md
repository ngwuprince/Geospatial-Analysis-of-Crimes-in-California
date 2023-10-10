# Geospatial-Analysis-of-Crimes-in-California

This project involves the analysis and visualization of San Francisco Police Department Incidents for the year 2016 using geospatial data analysis techniques. The data is sourced from the San Francisco public data portal and contains information about various crime incidents in the city. Below, you'll find an overview of the project and its steps.

**Datasets:**

The project uses the following dataset:
San Francisco Police Department Incidents for the year 2016:** This dataset contains information about crimes and incidents that occurred in San Francisco in 2016. It includes details such as incident number, category, description, day of the week, date, time, police district, resolution, address, latitude, longitude, and more.

**Overview:**

This project aims to analyze and visualize crime incidents in San Francisco for the year 2016. It involves the following steps:

- Importing Required Libraries: The necessary Python libraries, including NumPy, Pandas, and Folium, are imported for data manipulation and visualization.
- Loading the Dataset: The dataset containing information about crime incidents is downloaded and loaded into a Pandas DataFrame.
- Data Overview:** An overview of the dataset is provided, indicating its size and structure.
- Creating a Base Map:** A base map of San Francisco is created using Folium, with an initial zoom level set to 12.
- Adding Crime Incident Locations to the Map:** Crime incident locations are added to the map as circle markers, with pop-up information displaying the crime category.
- Clustering Crime Incidents:** To address map congestion, crime incident markers are grouped into clusters using the MarkerCluster plugin.

**Running the Code**

To run the code and visualize the San Francisco crime incidents for the year 2016 on an interactive map, follow these steps:

- Ensure that you have Python installed on your system.
- Install the required libraries, including Folium (`folium==0.5.0`), using the appropriate package manager (e.g., pip).
- Download the dataset (not included in this README) or use the provided dataset link.
- Execute the code in a Python environment.
