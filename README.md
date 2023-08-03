# CVD-Mortality-Prediction
Adding environmental metals to CVD mortality prediction models to attempt to improve prediction performance. Secondary analysis using machine learning to additionally improve performance

First file is CVD Mortality Prediction Data Cleaning, where the data are read in, necessary variables are categorized, variables are standardized, and train/test datasets are created.
Second file is CVD Mortality Prediction Descriptive Statistics, where histograms of continuous variables as well as a correlation heatmap are created. Descriptive statistics for full dataset as well as split by train/test datasets are created in this file.
Third and final file is CVD Mortality Prediction Models, where the statistical analyses are run. Begins with recreation of Framingham Heart Study, then Cox Proportional Hazards Model with our NHANES continuous predictors, then elastic-net, and finally survival random forest. C-indices and NRI/Continuous NRI are calculated in this file. Individual associations between predictors and CVD mortality are examined in this file.
