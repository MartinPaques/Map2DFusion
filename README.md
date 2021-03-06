# Map2DFusion - RPI Version
------------------------------------------------------------------------------
## Disclaimer:
This project is based on the previous Work on Map2DFusion, but i'm aiming at making a version of this software optimized for a raspberry pi 3.


## Brief Introduction
This is an open-source implementation of paper:
Map2DFusion: Real-time Incremental UAV Image Mosaicing based on Monocular SLAM.

Website : http://zhaoyong.adv-ci.com/map2dfusion/

Video   : https://www.youtube.com/watch?v=-kSTDvGZ-YQ

PDF     : http://zhaoyong.adv-ci.com/Data/map2dfusion/map2dfusion.pdf   

## 1. Compilation
### 1.1. Resources
  * Download the latest code with: 
    * Git: 
    
            git clone https://github.com/MartinPaques/Map2DFusion

### 1.2. Dependencies
- OpenCV  : sudo apt-get install libopencv-dev (will provide another way to install openCV to boost performances)
- Qt      : sudo apt-get install build-essential g++ libqt4-core libqt4-dev libqt4-gui qt4-doc qt4-designer
- QGLViewer : sudo apt-get install libqglviewer-dev libqglviewer2
- Boost   : sudo apt-get install libboost1.54-all-dev
- GLEW    : sudo apt-get install libglew-dev libglew1.10
- GLUT : sudo apt-get install freeglut3 freeglut3-dev.

### 1.3. Compilation

Work in progress

## 2. Usage
Obtain the sample sequence and launch:

    git clone https://github.com/zdzhaoyong/phantom3-village-kfs
    ./Map2DFusion DataPath=phantom3-village-kfs
    
More sequences can be downloaded at the [NPU DroneMap Dataset](http://zhaoyong.adv-ci.com/npu-dronemap-dataset).
## 3. Contact

If you have any issue compiling/running Map2DFusion for RPI 3 or you would like to know anything about the code, please contact the authors:

     Martin Paques -> martin.paques@estaca.eu



