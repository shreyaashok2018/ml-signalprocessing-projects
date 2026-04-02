# Audio Classification using Signal Processing + Machine Learning

## Overview

This project builds an end-to-end audio classification pipeline using signal processing and machine learning techniques.

## Feature Extraction

* MFCC (mean + standard deviation)
* Spectral centroid
* Zero-crossing rate

## Models Used

* Random Forest (best: ~83.7%)
* Neural Network (~77.5%)

## Insights

* Feature engineering significantly improved performance
* Random Forest outperformed neural networks due to dataset size
* Cross-validation provided stable evaluation

## Dataset

Subset of ESC-50 dataset (dog, rain, engine, crying baby)

## Future Improvements

* Larger dataset
* Deep learning on spectrograms
* Real-time audio classification
