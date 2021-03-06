# Chicago-Crime-Analysis
Required Packages: 

Python: pandas, numpy, scikit-learn, itertools, matplotlib.pyplot, IPython.display, seaborn

R: tidyverse, ggmap, zipcode

Ajit Koduri and Zane Olds looking at the Chicago Crime Data provided by the CPD CLEAR's system as seen on Kaggle. Powerpoints contain pictures arising from data analysis, .ipynb files are code we have made to look into the the criminal occurrences in Chicago with Python using Jupyter Notebooks.

Chicago Crime Data.ipynb contains initial analysis of all crime between 2005 and February 2017, which has nearly 12 million instances. We looked into crime in Chicago through the course of time, crime by location, followed by crime by arrest rates. We used a Gaussian Naive Bayes model to create a model to determine whether an arrest will be made, which is 68.3% accurate. We list out the relevant graphics in ChicagoCrimeData.pptx.

map1.r contains the code for theft_density_by_year.pdf, a contour graph of the theft crimes in Chicago over the years overlaying the city, and top30blocks.pdf, a graph of the top 30 most commonly mentioned streets in the total database.

Chicago Sex Crimes Analysis.ipynb contains analysis of only sex crimes between 2005 and February 2017, which has a little over 100,000 instances. Here, we add in location of crimes by zip code demographic data we found from the U.S. Census Data in Chicago from 2010 which we document in Chicago_ZipCode_Data.csv. Chicago_Zip_Data.csv contains the zip code for each crime, which we found from geocoding the locations of the data. child_offenses.mp4, human_traff.mp4, prostitution.mp4, sex_assault.mp4, sex_offenses.mp4, and stalking.mp4 are animations of the heatmaps of each type of crime in Chicago as it progressed from 2005 to February 2017. We created models to again predict whether an arrest will be made using a Bernoulli Naive Bayes model (77.4% accurate), a Generalized Linear Model with normal ordinary least squares (81.6% accurate), and a Random Forest (87.5% accurate).

We follow up by looking at the sex crimes representation per zip code and noting how changes in number of crimes is mirrored in the change in number of arrests made there too.
