# seismicanomalies

## Introduction
This project was created over two days as part of the OGA/Agile Hackathon in Aberdeen, UK, November 16-18th 2018.

The aim of the project was to use machine learning to identify whether images of seismic data contained particular feature classes.
In this case four features were extracted from OGA lines in the mid-north sea. 
- Salt
- Gas Chimney
- Flat Stratigraphy
- Noise

## Method
1. Create a training dataset of images by capturing screen shots of data all at a common scale. The images are not of equal size.
2. Label the images so they can be categorized and put into a Pandas DataFrame
3. Noise images were created by subsampling a few large noise screenshots with random patches.
4. Randomly split the data within categories into training and test data. 
5. Concatenate the different categories together.
6. Output the data to pickle.
7. Import data and create new features using image processing. (Edge detection and Gabor filter).
8. Output expanded DF Pickle.
9. ML Feature Extraction
10. Training

## Team Members
Quentin Corlay
Amaechi Halim
Tony Hallam
Saleem Ramy
Shaji Matthew
Elia Gubbala
Zh Cui
