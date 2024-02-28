# Machine Learning-based Quantification of Personal Fitness

### Introduction (Still needs more work)

Over the last few years, monitoring technology have taken a leap and helped free the many physical constraints carry-on sensors like GPS-trackers, accelerometers, and gyroscope posed. This has paved way for academic research in the field of tracking and classifying data collected from numerous human activities through means of wearable smartwatches. The aim of this research project is to deeply explore the various possibilities of context aware application in the field of strength training. The objective is achieved through means of collecting, preprocessing, and analyzing raw data collected from wristband gyroscope and accelerometer obtained during workout sessions.

Numerous works from past have been focused on tracking movements and analyzing user feedback through means of exercises. However, these systems do not entirely replace the tasks fulfilled by personal trainers. Weight training, similar to cardiovascular aerobic exercises is an essential aspect to health and fitness. However, there are yet to be many wearable devices that track the strength training exercises. At the moment there is only one wearable device that identifies exercise and tracks the repetitions in a set.

### Data Preparation

Data has been collected from Metamotions, a wearable device that offers real-time and continuous monitoring of motion and environmental sensor data. The raw data involves accelerometer and gyroscope measurements of all the participants involved during their workout session. Dataset was created after itering over numerous files of raw data, cleaning it, preprocessing it, and finally merging it into one pickle dataset. The reason the dataset was exported as pickle over csv is because it involved numerous timestamps in epoch. Snippet 1 next to the text gives a brief glimpse of the raw data files that has been gathered. Snippet 2 is a snippet of one of the files that measured benchpress movement of participant A. Snippet 3, the lower rightmost image is the picture of final dataset the project will be using.

### Exploratory Data Aanalysis
Since the data cleaning and preprocessing took such a long time only minor data exploration is done centered around the accelerometer and gyroscope measurements along different axes with the type of exercise (label).

### Initial Setup

Run the command `conda env create -f environment.yml` to install all the necessary packages. 

### Necessary Files

* **Data:** Raw data could be accessed from `./data/raw/MetaMotion`
* **Data Cleaning:** Data Cleaning and preprocessing have been done. The file can be found `./notebooks/create_dataset.ipynb`.
* **Final Dataset:** Final data set can be found in `./data/interim`
* **Data Visualization:** Only one visualization was done because cleaning the data took so long. The file can be accessed from `./notebooks/visualization.ipynb`.

### Citations

Citations can be found  `./reports/citation.bib`
