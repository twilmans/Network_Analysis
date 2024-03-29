# Network_Analysis
Code (pipeline and statistical analysis) used to run Weighted Gene Coexpression Network Analysis on 3500&lt; proteins measured in mice. This project was part of a collaborative effort from the NIH funded [Longevity Consortium](https://www.longevityconsortium.org) to identify mechanisms extending lifespan.

WGCNA - R code run in Jupyter Notebooks to analyze MS proteomics data (3969 proteins, 48 samples)
      - performs soft threshold analysis to optimize parameters for approximating a scale free topology
      - performs clustering (identification of modules of tightly interconnected proteins in the larger measured network)
      - calculates module eigenvectors for further statistical analysis 
