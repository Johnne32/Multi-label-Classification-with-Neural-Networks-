# Multi-label Classification with Neural Networks
These codes were used to model the Planet: Understanding the Amazon from Space Kaggle datasets. I used a custom CNN architecture and a VGG16 pre-trained model achieving 0.91235 on the private leaderboard. 

## Overview

Every minute, the world loses an area of forest the size of 48 football fields. And deforestation in the Amazon Basin accounts for the largest share, contributing to reduced biodiversity, habitat loss, climate change, and other devastating effects. But better data about the location of deforestation and human encroachment on forests can help governments and local stakeholders respond more quickly and effectively.
In this competition, Planet and its Brazilian partner SCCON are challenging Kagglers to label satellite image chips with atmospheric conditions and various classes of land cover/land use. Resulting algorithms will help the global community better understand where, how, and why deforestation happens all over the world - and ultimately how to respond.

## File formats

train.csv - a list of training file names and their labels, the labels are space-delimited

sample_submission.csv - correct format of submission, contains all the files in the test set. For more information about the submission file, please go to the Evaluation page

[train/test]-tif-v2.tar.7z - tif files for the training/test set (updated: May 5th, 2017)

[train/test]-jpg[-additional].tar.7z - jpg files for the trainin/test set (updated: May 5th, 2017)

Kaggle-planet-[train/test]-tif.torrent - a BitTorrent file for downloading [train/test]-tif-v2.tar.7z (updated: May 5th, 2017)


#### Link to the files was collated by a user called Nikitarom since the image files were not available in the original project. Here is the link : https://www.kaggle.com/nikitarom/planets-dataset
