# F1 Driver Style Analysis

This project aims to analyze and classify the driving styles of Formula 1 drivers using various data analysis techniques and machine learning models.

## Table of Contents

- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [References](#references)

## Introduction

Understanding the driving styles of F1 drivers can provide insights into their performance and decision-making on the track. This project seeks to identify distinct driving patterns and classify drivers accordingly.

## Data Collection

Data was sourced from:

- **Telemetry Data**: Collected from official F1 data streams using the [f1dataR](https://github.com/SCasanova/f1dataR) package, which accesses data from the Jolpica API and the FastF1 Python library. :contentReference[oaicite:0]{index=0}

- **Race Statistics**: Historical race data, including lap times, sector times, and tire choices.

## Data Preprocessing

Steps involved:

1. **Data Cleaning**: Handling missing values and correcting inconsistencies.
2. **Feature Engineering**: Creating new features such as average cornering speed, braking patterns, and acceleration profiles.
3. **Normalization**: Scaling features to ensure uniformity.

## Exploratory Data Analysis

Analyzed various aspects of driver behavior:

- **Cornering Techniques**: Identified preferences for V-shaped vs. U-shaped cornering lines. :contentReference[oaicite:1]{index=1}
- **Braking Patterns**: Studied braking points and pressure application.
- **Throttle Application**: Examined acceleration habits out of corners.

## Modeling

Machine learning models were employed to classify driving styles:

- **Clustering Algorithms**: Used to group drivers based on similarity in driving metrics.
- **Classification Models**: Trained to predict a driver's style based on input features.

## Results

The analysis revealed distinct driving styles among drivers:

- **Smooth Oversteer**: Drivers like Max Verstappen exhibit smooth steering inputs with a preference for slight oversteer, allowing for high mid-corner speeds. :contentReference[oaicite:2]{index=2}

- **Aggressive Oversteer**: Drivers such as Charles Leclerc prefer a more aggressive approach, braking hard and late into corners, carrying high entry speeds. :contentReference[oaicite:3]{index=3}

## Conclusion

The classification of driving styles provides valuable insights into individual driver behaviors and can inform team strategies and driver coaching.

## Future Work

- **Real-Time Analysis**: Implementing real-time telemetry analysis to provide immediate feedback.
- **Predictive Modeling**: Using driving style data to predict race outcomes or tire wear.

## References

- [f1dataR: An R package to access Formula 1 Data](https://github.com/SCasanova/f1dataR)
- [Every F1 Driving Style we saw in 2024](https://www.driving-style.com/post/all-f1-driving-styles-in-2024)
- [F1 drivers' individual best tracks and driving styles](https://www.gtplanet.net/forum/threads/f1-drivers-individual-best-tracks-and-driving-styles.281065/)
