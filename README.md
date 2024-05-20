# Stellar Classification Dataset (SDSS17)

This repository contains a set of stellar classification data (SDSS17) collected by the Sloan Digital Sky Survey (SDSS). The dataset consists of 100,000 space observations, each described by 17 feature columns and 1 class column that identifies whether it is a star, galaxy, or quasar.

## Data source

The data was obtained from Kaggle and can be found at the following link: [Stellar Classification Dataset (SDSS17)](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17).

##Goal

The aim of this project is to develop machine learning models to predict the class of celestial objects (stars, galaxies or quasars) based on their spectral characteristics.

## Methodology

### Exploratory Data Analysis (EDA)

An exploratory data analysis (EDA) will be carried out to understand the distribution of characteristics and explore possible relationships between variables. This step is crucial to identify patterns, trends and possible anomalies in the data. Tools such as histograms, scatterplots and gloss analysis will be employed.

### Data Preparation

Data will be pre-processed to handle missing values, outliers and corrected for categorical variances if necessary. Normalization or standardization of features will also be considered to improve the performance of machine learning models.

###Modeling

Machine learning models will be trained. Models such as Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest and Gradient Boosting will be evaluated.

### Model Evaluation

Models will be evaluated based on detailed considerations for each type of problem. Metrics such as accuracy, precision, recall and F1 score will be used.

### Interpretation of Results

The results will be interpreted to understand the importance of the characteristics, the predictive capacity of the models and possible astronomical insights obtained.

## Dataset information

### Context

In astronomy, stellar classification is the classification of stars based on their spectral characteristics. The classification scheme for galaxies, quasars and stars is one of the most fundamental in astronomy. The initial catalog of stars and their distribution in the sky led to the understanding that they make up our own galaxies and, following the distinction that Andromeda was a galaxy separate from our own, numerous galaxies found themselves being cataloged as more powerful telescopes were built. This dataset aims to classify stars, galaxies and quasars based on their spectral characteristics.

###Content

The data consists of 100,000 space observations made by SDSS (Sloan Digital Sky Survey). Each observation is described by 17 feature columns and 1 class column that identifies whether it is a star, galaxy or quasar.

- **obj_ID**: Unique identifier of the object in the catalog of images used by CAS
- **alpha**: Angle of Right Ascension (without J2000 epoch)
- **delta**: Declination Angle (without J2000 epoch)
- **u**: Ultraviolet Filter in the photometric system
- **g**: Green Filter in the photometric system
- **r**: Red Filter in the photometric system
- **i**: Near Infrared Filter in the photometric system
- **z**: Infrared Filter in the photometric system
- **run_ID**: Run Number used to identify the specific scan
- **rerun_ID**: Rerun number to specify how the image was processed
- **cam_col**: Camera Column to identify the scan line within the execution
- **field_ID**: Field Number to identify each field
- **spec_obj_ID**: ID used only for optical spectroscopic objects (this means 2 different observations with the same spec_obj_ID must share the output class)
- **class**: Class of the object (galaxy, star or quasar)
- **redshift**: Redshift value based on the increase in wave length
- **board**: Board ID, identifies each board in SDSS
- **MJD**: Modified Juliana Data, used to indicate when a particular SDSS data set was obtained
- **fiber_ID**: Fiber ID that identifies the fiber that indicated light in the focal plane in each observation

## Conclusion
This project aims to not only apply advanced machine learning techniques, but also provide specific insights to the astronomical community, contributing to the understanding of the universe through the analysis of complex spectral data.