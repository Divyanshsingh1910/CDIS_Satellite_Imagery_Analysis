# CDIS_Satellite_Imagery_Analysis
## CODES
This directory should contain the relevant code-files used for any task in the project. Make sure that the beginning of each file to clearly state the
obectives of the code in that file. Update the readme whenever you add the any new file/changes to this directory.

Luminosity_final:
https://colab.research.google.com/drive/15eIOPCA5FMzOJ2NT_8mmSEOgOpE3dugm?usp=sharing 

**`extractsatelliteimages.ipynb`** - Is a codefile in which we need to input a csv with lat, long, and image labels and will extract satellite images corresponding to that latitude and longitude. (Author: Trijal)

**`k_nearest_code_old.ipynb`** - Is a codefile through which we are extracting k- nearest neighbours using OSM features. We just need to change the values of variables to output different k nearest places. (Author: )

**`9images_final.ipynb`** - Is a codefile to divide an image into 9 equal patches, and find the lat longs of centres of each of the smaller 9 patches. (Author: )

**`features_only_haryana.ipynb`** - Is a codefile to filter features only of haryana, from entire Northern region. (Author: )


# Approaches we Tested 

## Approach 1

- Land-cover-classification-with-eurosat-data-resnet and land-cover-classification-with-eurosat-data-resnetv2 are used for extracting Deep Features
- Luminosity_final used for calculating Luminosity
- Ind_pak_relative_wealth_index used as a y label
- Output is the final csv used to train and test the model
- Predicting_Wealth_Index (2) is training and testing the model


## Approach 2 



## Approach 3 

- **K means Clustering**: Given a value of K segment the satellite images and give the relative area of k segments.
- **Deep features**: Trains a CNN model with satellite images as input and Avg. NTL as output and then we move back into the CNN layers and get the deep features of the Satellite image.
