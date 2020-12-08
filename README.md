## INGV - Volcanic Eruption Prediction [ [Kaggle Competition](https://www.kaggle.com/c/predict-volcanic-eruptions-ingv-oe) ]
### Discover hidden precursors in geophysical data to help emergency response

In this competition, using  data science skills, we will  predict when a volcano next eruption will occur. 
We'll analyze a large geophysical dataset collected by sensors deployed on active volcanoes. 
If successful, the algorithm will identify signatures in seismic waveforms that characterize the development of an eruption. 

Data - 
This competition provides us with readings from several seismic sensors around a volcano and challenges us to estimate how long it will be until the next eruption. 
train.csv Metadata for the train files.
segment_id: ID code for the data segment. Matches the name of the associated data file.
time_to_eruption: The target value, the time until the next eruption.
[train|test]/*.csv: the data files. Each file contains ten minutes of logs from ten different sensors arrayed around a volcano. Size - 29 GB

## TODO:

- [ ] Preprocessed Data
- [ ] Append data Stats to DataFrame
- [ ] Fill NaN with other than "0"
- [ ] Compute Covariance
