# social-distance-detector
In this project, computer vision techniques are employed to monitor compliance with the social distance protocol. Additionaly, statistical data is recovered in order to obtain meaningful insights.

[![Demonstration](/media/video.png)](https://www.youtube.com/watch?v=pm3YnYfA7as)
[Demonstrative Jupyter notebook](https://github.com/jncnza/social-distance-detector/blob/master/notebook/social_distance_detector.ipynb)

## Instalation
Tested on Ubuntu 18.04 using python 3.7
### Install dependencies
#### Neccesary packages
* OpenCV
        conda install -c conda-forge opencv
* pandas
        conda install -c conda-forge pandas
* numpy
        conda install -c conda-forge numpy
#### Just for statistical visualizations
* matplotlib
        conda install -c conda-forge matplotlib
* seaborn
        conda install -c conda-forge seaborn
### Clone the repository
        git clone https://github.com/jncnza/social-distance-detector/
        cd social-distance-detector/
### Get the dataset
        !wget https://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/Datasets/TownCentreXVID.avi
        !wget https://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/Datasets/TownCentre-groundtruth.top
### Run the project
