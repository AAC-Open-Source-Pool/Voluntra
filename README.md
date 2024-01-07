<div align="center">
  <img src="https://imgur.com/zefmSJ3.png">
</div>
<p align="center">The volunteering website Voluntra is built on a user-friendly interface, ensuring easy navigation for both volunteers and organizations. Volunteers can create personalized profiles, showcasing their skills, interests, and availability. </p>


## Table of Contents
- [Introduction](#introduction) <br>
- [Requirements](#requirements) <br>
- [How to use](#installation-and-usage) <br>
- [Contribution](#contribution)

## Introduction 
Voluntra connects individuals like you with reputable organizations and impactful projects across the globe. We believe that everyone has something valuable to contribute, and our goal is to facilitate that connection between volunteers and causes, fostering positive change in communities worldwide.
  
## Requirements
|||
|--|--|
|[python 3.10.12](https://www.python.org)|<img src="https://imgur.com/5U1Qas4.png" width="130px" height="25px"></a><br>|
|[flair 0.12.2](https://github.com/flairNLP/flair)|<img src="https://i.imgur.com/4fOVzrO.png" width="130px" height="25px"></a><br>|
|[streamlit 1.27.1](https://streamlit.io)|<img src="https://i.imgur.com/KUaORTO.png" width="130px" height="25px"></a><br>|
|[easyocr 1.7.1](https://pypi.org/project/easyocr/)|<img src="https://imgur.com/prDaufp.png" width="130px" height="25px"></a><br>|
|[matplotlib 3.8.0](https://matplotlib.org)|<img src="https://imgur.com/u5TmBrV.png" width="130px" height="25px"></a><br>|
|[opencv 4.8.1.78](https://pypi.org/project/opencv-python/)|<img src="https://imgur.com/jEJpm7H.png" width="130px" height="25px"></a><br>|
|[numpy 1.26.0](https://numpy.org)|<img src="https://imgur.com/bQ6fhnn.png" width="130px" height="25px"></a><br>|
|[regex 2023.8.8 ](https://docs.python.org/3/library/re.html)|<img src="https://i.imgur.com/xQ8Kvmu.png" width="130px" height="25px"></a><br>|

## Installation and usage
- Clone the repository
- If you have a supported GPU, download CUDA and CUDNN on your system for faster running of the detection algorithm
- Install [Darknet](https://github.com/AlexeyAB/darknet) for object detection by following the instructions [here](https://github.com/AlexeyAB/darknet#how-to-compile-on-linux-using-make)
- Download and unzip darknetconfig.zip from the releases tab
- place the files from darknetconfig.zip in the following directories:
    `./darknet/cfg/yolov4-obj.cfg`
    `./darknet/data/obj.data`
    `/darknet/yolov4-obj_best.weights`
- Run `pip install -r requirements.txt` to download all necessary dependencies
- Run `streamlit run pii.py` to run the detection algorithm, and upload the picture to the website opened.

## Contribution 
**This section provides instructions and details on how to submit a contribution via a pull request. It is important to follow these guidelines to make sure your pull request is accepted.**
1. Before choosing to propose changes to this project, it is advisable to go through the readme.md file of the project to get the philosphy and the motive that went behind this project. The pull request should align with the philosphy and the motive of the original poster of this project.
2. To add your changes, make sure that the programming language in which you are proposing the changes should be same as the programming language that has been used in the project. The versions of the programming language and the libraries(if any) used should also match with the original code.
3. Write a documentation on the changes that you are proposing. The documentation should include the problems you have noticed in the code(if any), the changes you would like to propose, the reason for these changes, and sample test cases. Remember that the topics in the documentation is strictly not limited to the topics aforementioned, but are just an inclusion.
4. Submit a pull request via [Git etiquettes](https://gist.github.com/mikepea/863f63d6e37281e329f8)
