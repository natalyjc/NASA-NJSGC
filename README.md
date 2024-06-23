# NASA-NJSGC

## Plan
Title: Predicting Near-Earth Object Impact Risk Using Machine Learning and 3D Trajectory Data 

Objective: Develop a machine learning model to predict the potential impact risk of near-Earth objects based on their 3D trajectories and associated metadata

Optional: Capturing images from Close-Approach Viewer as additional input data. Can also be used to validate model's predictions visually 

Classification Method: Classify objects into risk levels (low, medium, high). Low risk are small objects passing at a significant distance. Medium risk are medium-size objects passing relatively close (must find a threshold number). High Risk are large objects with close approaches or potential collision courses. 

Data Integration: [NEO Earth Close Approaches Data Table](https://cneos.jpl.nasa.gov/ca/), [SBDB Close-Approach Data API](https://ssd-api.jpl.nasa.gov/doc/cad.html), [Horizons API](https://ssd-api.jpl.nasa.gov/doc/horizons.html#command), [Asteroids NeoWs](https://api.nasa.gov/?search=horizons#browseAPI)

## To-Do
Read through entire CNEO website
Extract NEO metadata from CNEOS website (downloading is not available for data-sets > 20000 rows, must use SBDB API)



### Week of 6/23 - 6/29
- [ ] advisor meeting (6/26)
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
- [ ]  work on report
- [ ]  work on presentation and slides
### Week of 7/28 - 8/3
- [ ] advisor meeting (7/29)
- [ ] work on finishing up report
- [ ] work on finishing up presentation and slides
### Week of 8/4 - 8/10
- [ ] advisor meeting (8/6)
- [ ] finish report
- [ ] finish presentation and slides
