# F1 Driver Style Analysis

This is a project to explore the drving style of all the drivers who participated in 2024 F1 Season.
The data was sourced from historical race data using the [FastF1 API](https://github.com/theOehrly/Fast-F1).

Driving style is determined by giving two scores to each driver. These scores are determined based on how aggressively or cautiously they drive.

The scores were determined using factors such as (but not limited to):
  - Positions gained
  - Throttle variation
  - G's experienced
  - Lap times
  - Track limit violations
  - DRS usage

These features where extracted and reduced to two values using PCA.

These scores are plotted on a 3D graph with the third axis denoting time as the season progresses.
This graph can be viewed [here](https://gunjitsinha.github.io/F1-Driver-Style/).
