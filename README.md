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

- Secure eBird API key setup using a `.env` file loaded by `python-dotenv`, an environment variable, or a hidden prompt
- Retrieval of recent Wood Stork observations from the eBird API
- Comparison of observation counts across selected southeastern states
- Processing of observation dates, locations, state codes, and reported bird counts
- Visualizations showing recent Wood Stork observation patterns in graphs and map

Notebook: `Blochel_eBird_wost.ipynb`

## eBird API key setup

Install the project dependencies with:

```bash
pip install -r requirements.txt
```

The notebook currently looks for `.env.example` in the repository folder and reads
the `EBIRD_API_KEY` value from that file:

```bash
EBIRD_API_KEY=your_ebird_api_key_here
```

If `.env.example` is not present, the notebook prompts for the key with hidden
input. Install the dependencies, then run the setup cell before running the API
request cells.

The repository's `.gitignore` excludes `.env` files, but `.env.example` is
allowed to be tracked. Never commit a real API key, paste it into the notebook,
or store it in `.env.example`; use the placeholder shown above when sharing the
repository.
