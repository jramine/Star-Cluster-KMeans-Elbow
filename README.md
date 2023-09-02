# Star Cluster Analysis Project

## Overview
Stars typically form in clusters and associations, and understanding their dynamics within these clusters is a fundamental aspect of astrophysics. This project aims to analyze and gain insights from a simulated star cluster using data-driven techniques, with a particular emphasis on clustering stars using the K-Means method and determining the optimal number of clusters using the elbow method.

## Project Description
In this project, we explore the behavior of stars in a simulated star cluster through data analysis and clustering techniques. Our main objectives include:

1. **Clustering Stars**: We apply the K-Means clustering algorithm to the dataset containing positions and velocities of stars over time. By grouping stars into clusters, we aim to uncover patterns and structures within the star cluster.

2. **Elbow Method**: To determine the optimal number of clusters, we utilize the elbow method, a common technique in cluster analysis. This helps us find the most suitable division of stars within the cluster.

3. **Predictive Modeling**: We seek to predict the future positions and velocities of stars based on their initial conditions. Additionally, we explore the correlation in star motions and investigate whether a star's velocity can be predicted based on the velocities of its neighbors.

4. **Cluster Dynamics**: We analyze how the size of the cluster (effective radius) evolves over time and examine its time-series properties. We also study the movement of the cluster's center and assess the symmetry of the cluster around this center.

5. **Escape Prediction**: Stars can leave the cluster due to energy exchange in close encounters with other stars. We aim to predict which stars are more likely to escape and estimate when they might do so.

## Dataset Details
- Initial Number of Stars: 64,000
- Simulation Units: Standard N-body units (G = M = -4E = 1)
- Mass of Each Star: 1.5625e-05 (1/64,000)
- Total Mass of Cluster: Initially 1

## Usage
This project and dataset offer valuable insights into star cluster dynamics and can be of interest to researchers in astrophysics, physics, and data science. You can access the data by downloading the individual CSV files corresponding to different time snapshots.

## Contributing
If you'd like to contribute to this project, have suggestions, or want to collaborate, please feel free to open an issue or submit a pull request. We welcome contributions from the community to enhance our understanding of star cluster dynamics.

## License
This project is open-source and is made available under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). You are free to use, share, and adapt the project and dataset for both commercial and non-commercial purposes, provided you give appropriate credit to the original source.

Thank you for joining us in exploring the fascinating world of star clusters!
