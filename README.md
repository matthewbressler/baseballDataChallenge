# baseballDataChallenge

In this project, we aim to use data on bat speed and swing length to assess players’ performance metrics. We started by observing league wide trends, then shifted to doing analysis on individual players. We looked at performance in different situations, and created a model to predict player performance.


# File Directory
- Data/
   - pitch_swing.csv
   - statcast_pitch_swing_data_20240402_20241030_with_arm_angle.csv
- Bat_SpeedZScore vs Count.ipynb: analysis on individual hitters and different situations
- EDA_MB.ipynb: exploratory data analysis on league trends
- baseballDataChallengeReport.pdf
- player_clustered_data.csv: player profile with cluster group
- player_kmeans_clustering.ipynb: k-means clustering to cluster players
- player_profile.ipynb: creating player profile
- prediction_model.ipynb: creating wOBA prediction model

## Important: Git LFS Required

This repository uses [Git Large File Storage (LFS)](https://git-lfs.github.com/) to manage large files. 
Make sure to download Git LFS to download the CSV files

### How to Set Up Git LFS
1. Install Git LFS:
   ```bash
   git lfs install
