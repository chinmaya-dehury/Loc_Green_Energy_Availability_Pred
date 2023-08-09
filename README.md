# Predicting Location-Based Green Energy Availability in Smart Buildings: A Case Study in Estonia
A supporting library for our paper [Predicting Location-Based Green Energy Availability in Smart Buildings: A Case Study in Estonia](https://doi.org/10.1016/j.measen.2022.100644)

This repo contains the related code and the data.
For further understanding please contact chinmaya.dehury@ut.ee

## Data and Codes
- The data folder contains all necessary data to use for implementation. All data files given in different time frames are clean data.<br >
- Codes are given in different time frames, and each given file consists of all ML models with corresponding results.

## Description
- The historical data are collected from PV panels and the nearby weather station. This is followed by data processing, including handling missing values, feature scaling and selection, target transformation, data splitting, etc.

<img src="https://am3pap006files.storage.live.com/y4mPVyiFt3ldiRDFPJJDwO0_2e78ZWq6g3odiu3caT8G7z2vOSzb7ZDe__lVOIIp9Mx3j08ruOS0h6ctJfJgmIxylpzDmNg9B_lsModMyqO566y2R7vQlvWZr_ipzMzZMgTSC4jSRnGZMlkbxJE6011FgswTKoZQowowdJYGSijPsRLrB3VIk72FcbzY61oLPLN?encodeFailures=1&width=720&height=389">



### Method Used <br >
- Machine Learning Models 
  - K-Nearest Neighbor (KNN)
  - XGBoost (Extreme Gradient Boosting)
  - MLP (Multilayer Perceptron)
  - Support Vector Regression
  - Random Forest
### Technologies Used
- Python  3.8.3 
- Jupyter Notebook  6.0.3 
- Pandas  1.0.5   
- Numpy  1.19.5  
- Sklearn  1.0.2  
- Scipy  1.5.0  
- Matplotlib  3.2.2  
- Seaborn  0.10.1 
- XGBoost  1.5.0 


If you publish something that usage this data/code, please refer this article as below:    
``` markdown
@article{HATAMIAN2023100644,
  title = {Location-aware green energy availability forecasting for multiple time frames in smart buildings: The case of Estonia},
  journal = {Measurement: Sensors},
  volume = {25},
  pages = {100644},
  year = {2023},
  issn = {2665-9174},
  doi = {https://doi.org/10.1016/j.measen.2022.100644},
  url = {https://www.sciencedirect.com/science/article/pii/S2665917422002781},
  author = {Mehdi Hatamian and Bivas Panigrahi and Chinmaya Kumar Dehury},
}
```

For more info, please see this open access article publish by Elsevier's "Measurement: Sensors", [PDF](https://doi.org/10.1016/j.measen.2022.100644). 
