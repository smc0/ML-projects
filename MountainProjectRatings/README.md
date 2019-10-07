This purpose of this project is to analyze rock climbing route ratings from a popular climbing website. Route features and comment data are used in separate models to predict a rating. Future work will include a multi-input model combining regression with both numeric and NLP features for more accurate predictions.

Analysis is spread across three notebooks (links to Jupyter Notebook Viewer):

1. https://nbviewer.jupyter.org/github/smc0/ML-projects/blob/master/MountainProjectRatings/MtnProjScraper.ipynb  
This notebook contains code to scrape data from route pages.

2. https://nbviewer.jupyter.org/github/smc0/ML-projects/blob/master/MountainProjectRatings/MtnProjDataVis.ipynb  
This notebook contains data preprocessing and exploratory analysis.

3. https://nbviewer.jupyter.org/github/smc0/ML-projects/blob/master/MountainProjectRatings/MtnProjModel.ipynb  
This notebook contains two regression models, one using numeric features and another incorporating NLP to process reviews.
