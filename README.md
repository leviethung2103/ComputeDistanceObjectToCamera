# Real-time Distance Measurement between a camera and your face using webcam

## Introduction

This project is used to compute the distance from a known object in an image to our camera.

To accomplish this task we utilized the triangle similarity, which requires us to know two important parameters prior to applying our algorithm:

- The width (or height) in some distance measure, such as inches or meters, of the object we are using as a marker.
- The distance (in inches or meters) of the camera to the marker in step 1.
- Computer vision and image processing algorithms can then be used to automatically determine the perceived width/height of the object in pixels and complete the triangle similarity and give us our focal length.
- Then, in subsequent images we simply need to find our marker/object and utilize the computed focal length to determine the distance to the object from the camera.

Finally, we can get your hand dirty by measure the distance from you face to camera.

## Steps

### Calibration 
Firstly, we need to know the focal length of camera. 

### Estimate the width of object in pixels - camera 

### Run the demo on webcam

## Getting Started

### Dependent Packages

* numpy
* opencv-python 

**Conda (Recommended)**

```bash
# Tensorflow GPU
conda env create -f conda-gpu.yml
conda activate conda-gpu
```


## Video Example

Will be update later


## Usage
Check the instruction in my [JupyterNotebook](https://github.com/leviethung2103/ComputeDistanceObjectToCamera/blob/master/computeDistance.ipynb)

## Acknowledgments
[Pyimagesearch](https://www.pyimagesearch.com/2015/01/19/find-distance-camera-objectmarker-using-python-opencv/)
