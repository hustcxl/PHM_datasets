**RoadMap**
<!-- TOC -->

- [1.Introduction](#1Introduction)
- [2.PHM Data Challenge 2019](#2fatigue-crack-growth-in-aluminum-lap-joint---phm-data-challenge-2019)
- [3.PHM Data Challenge 2009](#3gearbox-fault-detection-dataset-phm-data-challenge-2009)
- [4.Bosch Production Line Performance 2016](#4-bosch-production-line-performance)

<!-- /TOC -->

# PHM_datasets
## 1.Introduction
This repository is used to collect and organize PHM related open source data sets.

If results based on these data sets are published, please acknowledge the copyright owner.

In case of infringement, please contact me to delete it.

## 2.Fatigue Crack Growth in Aluminum Lap Joint - PHM Data Challenge 2019
* [Resource link by Matteo Corbetta](https://c3.nasa.gov/dashlink/resources/1014/)

Fatigue experiments were conducted on aluminum lap-joint specimens, and lamb wave signals were recorded for each specimen at several time points (i.e., defined as number of cycles in fatigue testing). Signals from piezo actuator-receiver sensor pairs were reported and it was observed that these signals were directly related to the crack lengths developed during fatigue testing. Optical measurements of surface crack lengths are also provided as the ground truth. The dataset is split in training and validation to facilitate the application of data-driven methods.

Dataset structure and main info: please see ReadMe file.

In case you use this dataset to publish research in conference proceedings and journals, please cite the papers recommended in the ReadMe file.

The data is organized by folder structures. The parent folder contains one file and two folders. The file is named “Read Me.docx” and has all the information for the testing description and data explanation. One folder is named “training” and contains all training data sets. The other folder is named “validation” and contains all validation data set. The folders are organized by specimens, named T1-T6 in the training folder and T7-T8 in the validation folder. All formatting is explained in detail this file.

This dataset was generated at Arizona State University by Prof. Yongming Liu, Dr. Tishun Peng, and their collaborators. Acknowledgements and relevant publications using this dataset are available in the ReadMe file.

The dataset was used for the PHM Data Challenge for the 2019 Conference on Prognostics and Health Management. Other than the dataset authors, the following people helped put together the 2019 PHM data challenge and make the dataset publicly available.

## 3.Gearbox Fault Detection Dataset, PHM Data Challenge 2009

* [Resource link](https://c3.nasa.gov/dashlink/resources/997/)

This PHM Data Challenge is focused on fault detection and magnitude estimation for a generic gearbox using accelerometer data and information about bearing geometry. Scoring is based on the ability to correctly identify type, location, and magnitude and damage in a gear system.

The Data Challenge was part of the 2009 Conference of the PHM Society

## 4. Bosch Production Line Performance
* [Resorce link](https://www.kaggle.com/c/bosch-production-line-performance/overview/ieee-bigdata-2016)

Because Bosch records data at every step along its assembly lines, they have the ability to apply advanced analytics to improve these manufacturing processes. However, the intricacies of the data and complexities of the production line pose problems for current methods.

In this competition, Bosch is challenging Kagglers to predict internal failures using thousands of measurements and tests made for each component along the assembly line. This would enable Bosch to bring quality products at lower costs to the end user.

## Hard Drive Reliability Sample
* [Resorce link](https://data.world/scuttlemonkey/hard-drive-reliability-sample)

Each day in the Backblaze data center, they take a snapshot of each operational hard drive. This snapshot includes basic drive information along with the S.M.A.R.T. statistics reported by that drive. The daily snapshot of one drive is one record or row of data. All of the drive snapshots for a given day are collected into a file consisting of a row for each active hard drive.

The first row of the each file contains the column names, the remaining rows are the actual data. The columns are as follows:

- Date – The date of the file in yyyy-mm-dd format.
- Serial Number – The manufacturer-assigned serial number of the drive.
- Model – The manufacturer-assigned model number of the drive.
- Capacity – The drive capacity in bytes.
- Failure – Contains a “0” if the drive is OK. Contains a “1” if this is the last day the drive was operational before failing.
- 2013-2014 SMART Stats – 80 columns of data, that are the Raw and Normalized values for 40 different SMART stats as


[:top:Back To Top](#1Introduction)

