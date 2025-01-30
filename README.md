# Biodiversity and Species Observations Analysis

## Introduction
This project analyzes data from two datasets: `observations.csv` and `species_info.csv`. The objective is to explore biodiversity trends across national parks, focusing on species diversity, conservation status, and observations. By answering key analytical questions, we aim to provide insights that can support biodiversity preservation efforts.

## Datasets Overview
- **`observations.csv`**: Contains data on species observations across various national parks.
  - `scientific_name`: The scientific name of the species.
  - `park_name`: The national park where the observation was recorded.
  - `observations`: The number of times the species was observed.

- **`species_info.csv`**: Provides detailed information about different species.
  - `category`: The biological classification of the species (e.g., Mammal, Bird).
  - `scientific_name`: The scientific name of the species.
  - `common_names`: Common names associated with the species.
  - `conservation_status`: The conservation status of the species (e.g., Endangered, Threatened).

## Objectives
This project focuses on answering the following questions:
1. Which parks have the highest and lowest number of species observations?
2. What is the distribution of species by conservation status?
3. What is the distribution of `conservation_status` for animals?
4. Are certain types of species more likely to be endangered?
5. Are the differences between species and their conservation status significant?
6. Which species are observed most frequently at each park?

## Project Workflow
1. **Data Loading and Exploration:** Load and preview the datasets to understand their structure.
2. **Data Cleaning:** Handle missing values and inconsistencies to ensure accurate analysis.
3. **Exploratory Data Analysis (EDA):** Visualize data trends, including species distribution, park-specific observations, and conservation status.
4. **Insights and Documentation:** Draw key insights and summarize findings to address the objectives.

## Tools and Technologies
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook

## How to Run the Project
1. Clone this repository to your local machine.
2. Install the required Python packages.
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to follow the analysis and generate insights.

## Future Updates
This README will be updated with key findings and conclusions once the analysis is complete.


