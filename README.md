# himalaya-glof-risk
Mapping glacial lake outburst flood risk in the Eastern Himalaya with satellite imagery and machine learning

Phase 1:
  1. Import google earth engine library and geemap for visualisation and connect to them through google account
  2. Look at a lake in the study area by calling the compernicus image collection
     a) filtering the dates between 10Oct to 30Nov of 2022 (before flood) and 2023 (after flood) with pixel cloud percentage of 30%
     b) take the median of all the results for each of before and after series separately
     c) visualize the result
  3. Calling the FAO GAUL for selecting the study are borders: Bhutan, Nepal and state of Sikkim in India and visualize it
  4. Calling copernicus DEM 30, clip it to our study area after it was mosaiced; eventually visualize it
  5. Creating a mask of elevations of more than 4000 m from the clipped DEM
