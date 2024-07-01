# NASA-NJSGC

## Plan
Title: Predicting Near-Earth Object Potential Hazardous Using Machine Learning and 3D Trajectory Data 

Objective: Develop a machine learning model to predict if near-Earth objects are potentially hazardous based on their metadata

Binary Classification Model: Extracting is_potentially_hazardous_asteroid from Asteroids - NeoWs API as target variable. Combining metadata from SBDB Close Approach API and NASA API

Data Integration: [NEO Earth Close Approaches Data Table](https://cneos.jpl.nasa.gov/ca/), [SBDB Close-Approach Data API](https://ssd-api.jpl.nasa.gov/doc/cad.html), [Horizons API](https://ssd-api.jpl.nasa.gov/doc/horizons.html#command), [Asteroids NeoWs](https://api.nasa.gov/?search=horizons#browseAPI)

## To-Do
Read through these sources for classification algorithm: (https://cneos.jpl.nasa.gov/sentry/torino_scale.html), (https://methods-x.com/article/S2215-0161(23)00334-5/fulltext),(https://ieeexplore.ieee.org/document/10112391) 
Write a python script to iterate through ~15k entries to obtain certain features and label, taking into account the 2000 request limit from NASA API

### Week of 6/23 - 6/29
- [X] advisor meeting (6/26)
- [X] collect data and perform pre processing
- [ ] work on report
### Week of 6/30 - 7/6
- [ ] advisor meeting (7/1)
- [ ] have a completed large dataset to split into training, validation, and test sets
- [ ] work on report
### Week of 7/7 - 7/13
- [ ] advisor meeting (7/11)
- [ ] choose a model 
- [ ] train model on training set and tune model using validation set
- [ ] test model on unseen data, use metrics like accuracy, precision, recall and F1-score
- [ ] work on report
### Week of 7/14 - 7/20
- [ ] advisor meeting (7/16)
- [ ] continue model training, testing and evalution 
- [ ] work on writing report
### Week of 7/21 - 7/27
- [ ] advisor meeting (7/24)
- [ ] collect and obtain results from model
- [ ] work on poster
- [ ] work on report
- [ ] work on presentation and slides
### Week of 7/28 - 8/3
- [ ] advisor meeting (7/29)
- [ ] have finished poster
- [ ] work on finishing up report
- [ ] work on finishing up presentation and slides
- [ ] poster session (8/2)
