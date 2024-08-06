# NASA-NJSGC

![NJSGC Poster](https://github.com/user-attachments/assets/69d57861-1439-4989-84ac-a8827fbebda8)

## Summary
This repository includes two Python notebooks containing code on the data extraction process and the data preprocessing and modeling phases, a final report summarizing findings and a poster presentation (above) that was presented at the end of the internship. Additionally, the dataset includes Earth close approach data and orbital data of NEOs, excluding any entries with missing values.

Title: Predicting Hazardous Near-Earth Objects With Random-Forest and Class Imbalance Techniques

Objective: Develop a machine learning model to predict if near-Earth objects are potentially hazardous based on their metadata

Binary Classification Model: Extracting is_potentially_hazardous_asteroid from Asteroids - NeoWs API as target variable. Combining metadata from SBDB Close Approach API and NASA's Open API for NEOs

Data Integration: [NEO Earth Close Approaches Data Table](https://cneos.jpl.nasa.gov/ca/), [SBDB Close-Approach Data API](https://ssd-api.jpl.nasa.gov/doc/cad.html), [Asteroids NeoWs](https://api.nasa.gov/?search=horizons#browseAPI)

