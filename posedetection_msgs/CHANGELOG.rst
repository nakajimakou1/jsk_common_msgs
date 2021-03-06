^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package posedetection_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

4.3.2 (2020-05-03)
------------------
* fix for noetic, need to use OpenCV2 instead of OpenCV (`#26 <https://github.com/jsk-ros-pkg/jsk_common_msgs/issues/26>`_)

  *  add noetic test to travis.yml, update jsk_travis 0.5.10

* Contributors: Kei Okada

4.3.1 (2017-11-08)
------------------
* add find_packaeg(OpenCV) for compile error with OpenCV 3.3.1 (`#20 <https://github.com/jsk-ros-pkg/jsk_common_msgs/issues/20>`_)
* Contributors: Kei Okada

4.3.0 (2017-07-15)
------------------

4.2.0 (2017-06-28)
------------------

4.1.1 (2017-05-17)
------------------

4.1.0 (2016-10-27)
------------------

4.0.0 (2016-09-21)
------------------

3.0.0 (2016-06-18)
------------------

2.0.1 (2016-01-21)
------------------
* include/posedetection_msgs/feature0d_to_image.h: add cv.hpp
* CMakeLists.txt : remove posedetection_msgs depends on OpenCV; remove opencv from catkin_package, what provide opencv to catkin_LIBRARIES
* Contributors: Kei Okada

2.0.0 (2015-06-19)
------------------
* move from jsk_common to jsk_common_msgs
* [posedetection_msgs/package.xml] add message_filters to depends
* Contributors: Kei Okada

1.0.72 (2015-06-07)
-------------------
* [posedetection_msgs] Change local topic name -> global of feature0d_to_image
* [posedetection_msgs] Use draw_features func in Feature0DView
* [posedetection_msgs] Remove no need namespace declaration in Feature0DView
* [posedetection_msgs] Remove no need headers in Feature0DView
* [posedetection_msgs] Add header file for feature0d_view
* [posedetection_msgs] Add header file for feature0d_to_image
* [posedetection_msgs] Visualize Feature0D with Image
* Contributors: Kentaro Wada

1.0.71 (2015-05-17)
-------------------

1.0.70 (2015-05-08)
-------------------

1.0.69 (2015-05-05)
-------------------

1.0.68 (2015-05-05)
-------------------

1.0.67 (2015-05-03)
-------------------
* [posedetection_msgs] Add feature0d_to_image node
* Contributors: Kentaro Wada

1.0.66 (2015-04-03)
-------------------

1.0.65 (2015-04-02)
-------------------

1.0.64 (2015-03-29)
-------------------
* [posedetection_msgs] Generate binary in lib directory as other catkin
  packages do
* Contributors: Ryohei Ueda

1.0.63 (2015-02-19)
-------------------

1.0.62 (2015-02-17)
-------------------

1.0.61 (2015-02-11)
-------------------

1.0.60 (2015-02-03)
-------------------

1.0.59 (2015-02-03)
-------------------
* Remove rosbuild files
* Contributors: Ryohei Ueda

1.0.58 (2015-01-07)
-------------------

1.0.57 (2014-12-23)
-------------------

1.0.56 (2014-12-17)
-------------------

1.0.55 (2014-12-09)
-------------------

1.0.54 (2014-11-15)
-------------------
* new srv and changed Object6DPose
* Contributors: Kamada Hitoshi

1.0.53 (2014-11-01)
-------------------

1.0.52 (2014-10-23)
-------------------

1.0.51 (2014-10-20)
-------------------

1.0.50 (2014-10-20)
-------------------

1.0.49 (2014-10-13)
-------------------

1.0.48 (2014-10-12)
-------------------

1.0.47 (2014-10-08)
-------------------

1.0.46 (2014-10-03)
-------------------

1.0.45 (2014-09-29)
-------------------

1.0.44 (2014-09-26)
-------------------

1.0.43 (2014-09-26)
-------------------

1.0.42 (2014-09-25)
-------------------

1.0.41 (2014-09-23)
-------------------

1.0.40 (2014-09-19)
-------------------

1.0.39 (2014-09-17)
-------------------

1.0.38 (2014-09-13)
-------------------

1.0.36 (2014-09-01)
-------------------

1.0.35 (2014-08-16)
-------------------

1.0.34 (2014-08-14)
-------------------

1.0.33 (2014-07-28)
-------------------

1.0.32 (2014-07-26)
-------------------

1.0.31 (2014-07-23)
-------------------

1.0.30 (2014-07-15)
-------------------

1.0.29 (2014-07-02)
-------------------

1.0.28 (2014-06-24)
-------------------

1.0.27 (2014-06-10)
-------------------

1.0.26 (2014-05-30)
-------------------

1.0.25 (2014-05-26)
-------------------

1.0.24 (2014-05-24)
-------------------

1.0.23 (2014-05-23)
-------------------

1.0.22 (2014-05-22)
-------------------

1.0.21 (2014-05-20)
-------------------

1.0.20 (2014-05-09)
-------------------

1.0.19 (2014-05-06)
-------------------

1.0.18 (2014-05-04)
-------------------

1.0.17 (2014-04-20)
-------------------

1.0.16 (2014-04-19)
-------------------

1.0.15 (2014-04-19)
-------------------

1.0.14 (2014-04-19)
-------------------

1.0.13 (2014-04-19)
-------------------

1.0.12 (2014-04-18)
-------------------

1.0.11 (2014-04-18)
-------------------

1.0.10 (2014-04-17)
-------------------

1.0.9 (2014-04-12)
------------------

1.0.8 (2014-04-11)
------------------

1.0.4 (2014-03-27)
------------------
* posedetection_msgs: add message_generation to package.xml

1.0.0 (2014-03-05)
------------------
* set all package to 1.0.0
* use USE_ROSBUILD for catkin/rosbuild environment
* remove debug code
* use ROS_Distributions instead of ROS_DISTRO for electric
* comment out : add catkin.cmake
* add depends to roscpp
* update to opencv2
* move depend opencv2 to jsk_common since posedetection_msgs is under jsk_common stack
* add rosdep2 for electric, will fixed in opencv2.4. https://code.ros.org/trac/ros-pkg/ticket/5437
* use rosdep opencv2 and pkg-config, as described in the wiki http://www.ros.org/wiki/opencv2
* moved posedetection_msgs, sift processing, and other packages to jsk_common and jsk_perception
* Contributors: Kei Okada, rosen
