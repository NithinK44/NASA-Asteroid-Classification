# NASA-Asteroid-Classification
## Content
The data is about Asteroids - NeoWs.
NeoWs (Near Earth Object Web Service) is a RESTful web service for near earth Asteroid information. With NeoWs a user can: search for Asteroids based on their closest approach date to Earth, lookup a specific Asteroid with its NASA JPL small body id, as well as browse the overall data-set.

## Acknowledgements
Data-set: All the data is from the (http://neo.jpl.nasa.gov/). This API is maintained by SpaceRocks Team: David Greenfield, Arezu Sarvestani, Jason English and Peter Baunach.

## Inspiration
Finding potential hazardous and non-hazardous asteroids
Features responsible for claiming an asteroid to be hazardous

## Procedure
- Implemented a classification model to distinguish between hazardous and non-hazardous asteroids based on their
  characteristics
 - Used SMOTE to address class imbalance in the target variable by 35 %.
 - Utilized XGBoost to visualize the relative importance of features in the model.
 - Optimized model performance through hyperparameter tuning which helped reduce variance.
