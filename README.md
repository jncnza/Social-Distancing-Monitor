# Social Distancing Monitor
In this project, computer vision techniques are employed to monitor compliance with the social distance protocol. Additionaly, statistical data is recovered in order to obtain meaningful insights.

[![Demonstration](/media/video.png)](https://www.youtube.com/watch?v=pm3YnYfA7as)
Demonstrative Jupyter notebook [here](https://github.com/jncnza/Social-Distancing-Monitor/blob/master/social_distancing_monitor.ipynb)

## Features
* Get analytics such as
    - Number of persons at risk in a particular frame
    - Average exposition time for a person
    - Average number of people encountered for a person
* Identify persons at higher risk
* Identify the time with the highest number of persons at risk
* Visualize statistical graphics

## Instalation

### Install dependencies
#### Neccessary packages
* OpenCV\
        `conda install -c conda-forge opencv`
* pandas\
        `conda install -c conda-forge pandas`
* numpy\
        `conda install -c conda-forge numpy`
#### Just for statistical visualizations
* matplotlib\
        `conda install -c conda-forge matplotlib`
* seaborn\
        `conda install -c conda-forge seaborn`

### Clone the repository
        git clone https://github.com/jncnza/Social-Distancing-Monitor
        cd Social-Distancing-Monitor/

### Get the dataset
        !wget https://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/Datasets/TownCentreXVID.avi
        !wget https://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/Datasets/TownCentre-groundtruth.top

### Run the project
        python3 -i main.py
Tested on Ubuntu 18.04 using Python 3.7.

## Disclaimer
This project does not try to measure the exact actual metric distance among people, but rather just serve as an estimation of safe distance compliance.

## Credits
[pyimagesearch](https://www.pyimagesearch.com/2017/02/06/faster-video-file-fps-with-cv2-videocapture-and-opencv/)\
[Landing AI](https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/)\
[Active Vision Laboratory](https://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/project.html)
