# Overview
## BUILD Dependencies
* `tf2-devel-gpu.Dockerfile | tf2-devel-gpu` - builds Tensorflow 2 from source
* `tf-gpu-ros.Dockerfile | tf-gpu-ros` - installs ROS Melodic
* `proseco-build.Dockerfile | build` - installs additional depedencies for building (e.g. Eigen, etc.)
## RUN Depedencies
* `proseco-ci.Dockerfile | ci` - installs depedencies for CI
* `proseco-devel.Dockerfile | devel` - installs depedencies for development
