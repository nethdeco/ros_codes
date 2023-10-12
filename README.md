
## Frequently used libraries (Thanks for following work:)

* [LOAM](https://github.com/cuitaixiang/LOAM_NOTED) (LOAM: Lidar Odometry and Mapping in Real-time)
* [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) (VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator)
* [LIO-mapping](https://github.com/hyye/lio-mapping) (Tightly Coupled 3D Lidar Inertial Odometry and Mapping)
* [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) (ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM)
* [LiLi-OM](https://github.com/KIT-ISAS/lili-om) (Towards High-Performance Solid-State-LiDAR-Inertial Odometry and Mapping)
* [MSCKF_VIO](https://github.com/KumarRobotics/msckf_vio) (Robust Stereo Visual Inertial Odometry for Fast Autonomous Flight)
* [LOCUS](https://github.com/NeBula-Autonomy/LOCUS )  (Robust Lidar Odometry System )



## Frequently used ros commands 

```bash
rostopic echo --noarr /velodyne_points -n 1

rostopic echo /velodyne_points/fields -n 1

rostopic echo /velodyne_points/point_step -n 1
