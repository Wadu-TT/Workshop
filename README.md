# Workshop Repository

This repository contains various projects and datasets used for machine learning and data science workshops. Below is the detailed information about the datasets and the projects in this repository.

## Datasets

### MAGIC Gamma Telescope Dataset

The MAGIC Gamma Telescope dataset comes from the MAGIC (Major Atmospheric Gamma Imaging Cherenkov) telescope, which is used to observe gamma rays in the universe. This dataset contains data on high-energy gamma particles and background hadron particles.

- **Source**: [UCI Machine Learning Repository - MAGIC Gamma Telescope Dataset](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)
- **File**: `magic04.data`
- **Attributes**:
  - `fLength`: Continuous variable representing the length of the major axis of the ellipse.
  - `fWidth`: Continuous variable representing the length of the minor axis of the ellipse.
  - `fSize`: Continuous variable representing the 3rd root of the sum of the content of all the pixels in the image.
  - `fConc`: Continuous variable representing the ratio of sum of two highest pixels over the sum of all pixels.
  - `fConc1`: Continuous variable representing the ratio of highest pixel over the sum of all pixels.
  - `fAsym`: Continuous variable representing the distance from the highest pixel to the center, projected onto the major axis.
  - `fM3Long`: Continuous variable representing the 3rd root of the third moment along the major axis.
  - `fM3Trans`: Continuous variable representing the 3rd root of the third moment along the minor axis.
  - `fAlpha`: Continuous variable representing the angle of the major axis with the vector to the origin.
  - `fDist`: Continuous variable representing the distance from the origin to the center of the ellipse.
  - `class`: The class label: `g` for gamma signal, `h` for hadron background.

### Seoul Bike Sharing Demand Dataset

The Seoul Bike Sharing Demand dataset contains information about bike rental counts in Seoul, South Korea. It includes various features such as weather conditions, date, and time to understand the factors affecting bike rental demand.

- **Source**: [UCI Machine Learning Repository - Seoul Bike Sharing Demand Dataset](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)
- **File**: `SeoulBikeData.csv`
- **Attributes**:
  - `Date`: The date in MM/DD/YYYY format.
  - `Rented Bike Count`: The number of rented bikes.
  - `Hour`: The hour of the day (0 to 23).
  - `Temperature(°C)`: Temperature in Celsius.
  - `Humidity(%)`: Humidity percentage.
  - `Wind speed (m/s)`: Wind speed in meters per second.
  - `Visibility (10m)`: Visibility in 10 meters.
  - `Dew point temperature(°C)`: Dew point temperature in Celsius.
  - `Solar Radiation (MJ/m2)`: Solar radiation in Mega Joules per square meter.
  - `Rainfall(mm)`: Rainfall in millimeters.
  - `Snowfall (cm)`: Snowfall in centimeters.
  - `Seasons`: The season (Winter, Spring, Summer, Fall).
  - `Holiday`: Indicates whether the day is a holiday (No Holiday, Holiday).
  - `Functioning Day`: Indicates whether the day is a functioning day (Yes, No).

## Projects

### K-Nearest Neighbors (KNN) Classification

- **File**: `Knn.ipynb`
- **Description**: This project involves using the K-Nearest Neighbors (KNN) algorithm to classify data points in the MAGIC Gamma Telescope dataset. The notebook includes data preprocessing, scaling, and implementing the KNN algorithm.

### Bike Rental Demand Prediction

- **File**: `bikes_regression.ipynb`
- **Description**: This project involves predicting the bike rental demand using linear regression. The notebook includes data preprocessing, feature selection, and implementing the regression model on the Seoul Bike Sharing Demand dataset.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Wadu-TT/Workshop.git
