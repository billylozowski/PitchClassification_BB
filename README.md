This script is used to perform cluster analyses on some Trackman data collected during National Collegiate Athletic Association (NCAA) baseball games. Two different clustering analyses are utilised: Gaussian Mixture Model (GMM) and Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN). 

Gaussian Mixture Model (GMM):
The GMM approach assumes data is generated from a mixture of several Gaussian distributions, allowing for soft clustering (probabilistic assignment) and elliptical cluster shapes. This is particularly good when pitch types overlap (e.g., cutters vs. fastballs).

  Use case: model uncertainty in pitch classifications; helpful when pitches transition fluidly between types.


Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN):
HDBSCAN is a variant of DBSCAN (Density-Based Spatial Clustering) that does not require k, and handles varying densities well.

  Very good for identifying:
  - Dense pitch types
  - Sparse or rare types
  - Noise/outliers


All figures/plots can be found on GitHub [here](https://github.com/billylozowski/PitchClassification_BB/tree/main/Figures). HTML widgets (interactive plots) can be accessed at the following URLs:

[1. UMAP for RHP Break Profile (GMM)](file:///C:/Users/37784478/OneDrive%20-%20University%20of%20Nebraska/Documents/UNO%20Projects/PitchClassification_BB/Figures/UMAP%20for%20RHP%20Break%20Profile%20(GMM).html)
[2. UMAP for LHP Break Profile (GMM)](file:///C:/Users/37784478/OneDrive%20-%20University%20of%20Nebraska/Documents/UNO%20Projects/PitchClassification_BB/Figures/UMAP%20for%20LHP%20Break%20Profile%20(GMM).html)
[3. UMAP for RHP Break Profile (DBSCAN)](file:///C:/Users/37784478/OneDrive%20-%20University%20of%20Nebraska/Documents/UNO%20Projects/PitchClassification_BB/Figures/UMAP%20for%20RHP%20Break%20Profile%20(DBSCAN).html)
[4. UMAP for LHP Break Profile (DBSCAN)](file:///C:/Users/37784478/OneDrive%20-%20University%20of%20Nebraska/Documents/UNO%20Projects/PitchClassification_BB/Figures/UMAP%20for%20LHP%20Break%20Profile%20(DBSCAN).html)