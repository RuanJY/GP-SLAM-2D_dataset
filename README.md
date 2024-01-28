# GP-SLAM_2d_dataset

A mobile-robot-based SLAM data-set containing 2D laser scan from Hokuyo LiDAR, IMU, and odometry from wheel encoders.

Collected by Jianyuan RUAN in Yuquan campus, Zhejiang University.

## Main features:

- Precise and high frequency (40 Hz) 2D range measurement from Hokuyo LiDAR.

- The start point and end point coincide so that the accuracy assessment can be conducted easily. We use of rails to force the vehicle to return to the same location after completing a loop.

## Description:

**Platform**: 

“Apollo” differential drive mobile robot.

**Sensor**: 

- A [Hokuyo UTM-30LX-EW laser scanner](https://www.hokuyo-aut.jp/search/single.php?serial=170), 40 Hz, Maximum Range: 0.1 to 60m, Field of view 270°, Multi-echo, 1440 points per scan.
- Two wheel encoders
- A GY-85 IMU module. 

<div align=center><img width="500" src="https://github.com/RuanJY/DataSetZJU/blob/master/%E5%B0%8F%E8%BD%A6%E9%B8%9F%E7%9E%B0.jpg" alt="Fig. 1"/></div>

###  Yongqian Students’ Center

The first experiment was conducted on the second floor of Yongqian Students’ Center in Yuquan Campus, Zhejiang University, Hangzhou, China. The mobile robot moved clockwise through a corridor outside a lecture hall. The center lines of the corridor consists of two straight lines, one minor arc and one semicircle whose radius is about 8.5 m.

### Chow Yei Ching Science & Technology Building 

The second experiment was performed in another environment which is larger, and contains more unstructured objects. The environment, located in the fourth floor of the Chow Yei Ching Science & Technology Building in Yuquan Campus, Zhejiang University, Hangzhou, China, is 41 m × 34 m in size.
<div align=center><img width="800" src="https://github.com/RuanJY/DataSetZJU/blob/master/huanjing.jpg" alt="Fig. 2"/></div>

## Result of gp-slam 2d and G-mapping

Yongqian Students’ Center. The map are overlaid with map ground truth and trajectory of the mobile robot produced by slam. Left: gp-slam 2d, right: G-mapping

<div align=center><img width="800" src="https://github.com/RuanJY/DataSetZJU/blob/master/map6.1.jpg" alt="Fig. 3"/></div>

Chow Yei Ching Science & Technology Building. The map overlaid with map ground truth and trajectory of the mobile robot produced by slam. Left: gp-slam 2d, right: G-mapping

<div align=center><img width="800" src="https://github.com/RuanJY/DataSetZJU/blob/master/map6.2.jpg" alt="Fig. 4"/></div>

Please cite our paper if you use this data-set:
```@INPROCEEDINGS{8996403,
  author={J. {Ruan} and Z. {Fang} and B. {Li} and Y. {Wang} and W. {Zhao}},
  booktitle={2019 Chinese Automation Congress (CAC)}, 
  title={Evaluation of GP-SLAM in real-world environments}, 
  year={2019},
  volume={},
  number={},
  pages={3076-3081},
  doi={10.1109/CAC48633.2019.8996403}}
