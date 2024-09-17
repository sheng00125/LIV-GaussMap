
# LIV-GaussMap: LiDAR-Inertial-Visual Fusion for Real-time 3D Radiance Field Map Rendering



## Overview

### Hardware platform

https://github.com/sheng00125/LIV_handhold

**LIV-GaussMap: LiDAR-Inertial-Visual Fusion for Real-time 3D Radiance Field Map Rendering**  
 
IEEE Robotics and Automation Letters, 2024.


![demovideo2](./fig/opt2.gif)



## Features

- **Real-time fusion** of LiDAR, IMU, and camera data.
- High-performance **3D radiance field map** rendering.

<div style="display: flex; justify-content: space-between;">
    <img src="./fig/HKU.gif" alt="GIF 1" style="width: 50%;">
    <img src="./fig/rb.gif" alt="GIF 2" style="width: 50%;">
</div>


## Dependencies

The following libraries and tools are required to run the project:

- [ROS (Robot Operating System)](https://www.ros.org/)
- [PCL (Point Cloud Library)](https://pointclouds.org/)
- [OpenCV](https://opencv.org/)
- [Eigen3](https://eigen.tuxfamily.org/dox/)
- [Ceres Solver](http://ceres-solver.org/)

To install dependencies, you can use the following command for Ubuntu:

```bash
sudo apt-get install 
```
## Datasets

## Installation

1. Clone the repository:

```bash
git clone git@github.com:sheng00125/LIV-GaussMap.git
cd LIV-GaussMap
```

2. Build the project using `catkin`:

```bash
catkin_make
source devel/setup.bash
```

## Usage

1. Launch the main application:

```bash

```

If you find this work useful, please consider citing our paper:

```
@article{hong2024liv,
  title={LIV-GaussMap: LiDAR-Inertial-Visual Fusion for Real-time 3D Radiance Field Map Rendering},
  author={Hong, Sheng and et al.},
  journal={IEEE Robotics and Automation Letters},
  year={2024},
  publisher={IEEE}
}
```



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or questions, feel free to open an issue or contact the authors of the paper.