# Star Cluster Dataset

## Table of Contents
- [Overview](#overview)
- [Dataset Details](#dataset-details)
- [Data Columns](#data-columns)
- [Research Questions](#research-questions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
Stars are often found in clusters and associations, and this dataset provides a snapshot of a simulated star cluster's positions and velocities over time. The dataset is generated using a direct N-body simulation and contains valuable information for understanding the dynamics of star clusters in astrophysics.

## Dataset Details
- Initial Number of Stars: 64,000
- Simulation Units: Standard N-body units (G = M = -4E = 1)
- Mass of Each Star: 1.5625e-05 (1/64,000)
- Total Mass of Cluster: Initially 1

## Data Columns
The dataset consists of several CSV files, each representing a snapshot of the star cluster at different time points. Each CSV file contains the following columns:

1. `x`, `y`, `z`: The positions of stars in standard N-body units.
2. `vx`, `vy`, `vz`: The velocities of stars in standard N-body units.
3. `m`: The mass of each star (identically 1.5625e-05).
4. `id`: Unique ID numbers assigned to each star particle.

## Research Questions
This dataset opens up several intriguing research questions and possibilities:
- Can we predict the future position and velocity of stars based on their initial conditions?
- What is the level of correlation in the motions of stars, and can we predict a star's velocity based on its neighbors?
- How does the size of the cluster (effective radius) evolve over time, and what are its time-series properties?
- How can we define and track the cluster's center, and is the cluster symmetric around it?
- Which stars are more likely to escape the cluster, and when will they do so?

## Usage
This dataset can be used for various research purposes in astrophysics, physics, and data science. You can access the data by downloading the individual CSV files corresponding to different time snapshots.

## Contributing
If you'd like to contribute to this project or have any suggestions, please feel free to open an issue or submit a pull request.

## License
This dataset is made available under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). You are free to use, share, and adapt this dataset for both commercial and non-commercial purposes, provided you give appropriate credit to the original source.

Happy researching!
