# bangkok-accidents-data


Top 50 Clusters with Most Frequent Accidents in Bangkok area 

- Incidents data from iTIC (https://live.iticfoundation.org/) and Longdo Traffic (https://traffic.longdo.com/)
- During 2020-01-01 - 2022-05-26

Preliminary analysis:
- Extract only accidents (type=3) 34,875 records
- Find top 100 points with the radius of about 100m (0.001 degree) that have highest concentration of accidents.
- Group the connected points together in clusters.
- Top 50 clusters are 20220619-accident_grids_itic_2022_2020-top-100.csv

