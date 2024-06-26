# NASA-NJSGC

## Plan
Title: Predicting Near-Earth Object Impact Risk Using Machine Learning and 3D Trajectory Data 

Objective: Develop a machine learning model to predict the potential impact risk of near-Earth objects based on their metadata

Optional: Capturing images from Close-Approach Viewer as additional input data. Can also be used to validate model's predictions visually 

Regression Model: What was previously a classification problem, because none of the objects are greater than 0 on the Torino Scale (a scale used to categorize impact hazard of NEOs), a better approach is to predict the Impact Probability.

Data Integration: [NEO Earth Close Approaches Data Table](https://cneos.jpl.nasa.gov/ca/), [SBDB Close-Approach Data API](https://ssd-api.jpl.nasa.gov/doc/cad.html), [Horizons API](https://ssd-api.jpl.nasa.gov/doc/horizons.html#command), [Asteroids NeoWs](https://api.nasa.gov/?search=horizons#browseAPI)

## To-Do
Read through entire CNEO website <br>
Extract NEO metadata from CNEOS website (downloading is not available for data-sets > 20000 rows, must use SBDB API) <br>
Read through these sources for classification algorithm: [https://cneos.jpl.nasa.gov/sentry/torino_scale.html], [https://methods-x.com/article/S2215-0161(23)00334-5/fulltext],[https://ieeexplore.ieee.org/document/10112391] 



### Week of 6/23 - 6/29
- [ ] advisor meeting (6/26)
- [ ] collect data and perform pre processing
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
