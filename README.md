# Public API Group Project
Group project using Python to retrieve, process, and visualize data from public APIs.

This repository contains Python API projects completed by each group member. Each project uses a different public API to retrieve data, process selected information, and display the results in a useful way.

# Kiara Baker — iNaturalist API

Project: Seasonal Patterns in Amphibian Observations

This project uses the iNaturalist API to retrieve amphibian observation data from 2025. Python was used to examine monthly patterns in the number of amphibian observations and to explore the most frequently represented amphibian species within a sample of individual observations.

The analysis includes:

- Retrieval of data using the iNaturalist API
- Processing and organization of API data with pandas
- Monthly amphibian observation totals for 2025
- Visualization of seasonal observation patterns
- Extraction of species-level taxonomic information
- Visualization of the most frequently represented species in a sample of observations

Notebook: `Kiara_iNaturalist_Amphibians.ipynb`

# Alex Blochel — eBird API

Project: Wood Stork Observation Patterns

This project uses the eBird API to retrieve recent Wood Stork (*Mycteria americana*) observations. The analysis explores where Wood Storks have been reported across the southeastern United States and organizes the returned records into structured pandas DataFrames for further analysis.

The project includes:

- Secure eBird API key setup using an environment variable or hidden prompt
- Retrieval of recent Wood Stork observations from the eBird API
- Comparison of observation counts across selected southeastern states
- Processing of observation dates, locations, state codes, and reported bird counts
- Visualizations showing recent Wood Stork observation patterns in graphs and map

Notebook: `Blochel_eBird_wost.ipynb`
