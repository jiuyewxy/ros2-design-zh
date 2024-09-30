.. openEuler-ros-document documentation master file, created by
   sphinx-quickstart on Thu Aug 22 16:15:03 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

ROS2 Design 中文翻译
==================================================
本文档是ROS2 Design（https://design.ros2.org/）部分文章的中文翻译。


==================================================

.. toctree::
   :maxdepth: 1
   :caption: Overview
   
   overview/why_ros2.md
   

.. toctree::
   :maxdepth: 1
   :caption: Middleware
   
   middleware/中间件.md
   middleware/基于DDS的ROS.md
   middleware/ROS2的中间件接口.md
   middleware/节点到参与者的映射.md
   middleware/ROSQoS截止时间活动性和生命周期.md

.. toctree::
   :maxdepth: 1
   :caption: Interface
   
   interface/index.md
   interface/idl_interface_definition.md
   interface/legacy_interface_defintion.md

.. toctree::
   :maxdepth: 1
   :caption: Security

   Security/index.md
   Security/ros2_access_control.md
   Security/ros2_dds_security.md
   Security/ros2_security_enclaves.md
   Security/ros2_threat_model.md
