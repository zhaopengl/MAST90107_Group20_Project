# MAST90107_Group20_Project

## Dataset folder contains all the datasets.
JapaneseDiet_sample_set.csv and WesternDiet_sample_set.csv are original datasets. <br />
new_data.csv is the one which remove trans attributes and QC instances from both original datasets and them combine them. <br />
final.xlsx is the one which adds result column based on new_data.csv. <br />
Trajan.csv is the final csv after pre-processing steps.
## Model folder contains all the models files.
AA_EPA is the file which contains the code using AA/EPA model. <br />
Robust_PCA is the file which compares PCA and RPCA. <br />
New_Clustering+Supervised is the file which uses normal PCA and Kmeans clustering with 2 clusters and 3 clusters in 5 fold cross-validation. <br />
AA_EPA-3group is the file which uses AA/EPA method to classify overlapping cluster instances. <br />
Supervised learning method and Kmeans-3groups is the file which uses supervised learning methods to classify overlapping cluster instances.
## Pre-processing folder contains all the pre-processing files.
batch_correction is the file which contains the code using batch correction. <br />
Trajan.xlsx is the file which each page in it contains each step of pre-processing steps. <br />
## MeetingMinutes folder contains all the meeting minutes.
