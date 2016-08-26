# Groups on SLAM

## [Field Robotics Center, Carnegie Mellon University](http://www.frc.ri.cmu.edu/index.php)
Prof. Micheal Kaess is the author of iSAM. 
His PhD is under supervision of Prof. Frank Dellaert in Georgia Tech, and Post Doc in Prof. John Leonard in MIT.
Now he seems focusing on RBGD mapping, and optimization algorithm in SLAM.

Prof. Sanjiv Singh is the supervisor of Ji Zhang who did a great work on 3D lidar SLAM.

### People
Prof. Micheal Kaess, Prof. Sanjiv Singh, Dr. Ji Zhang

### Research: Prof. Micheal Kaess

1. Optimization
	- 2006: _Square Root SAM: Simultaneous localization and mapping via square root information smoothing_
	- 2008: _iSAM: Incremental smoothing and mapping_
	- 2012: _iSAM2: Incremental Smoothing and Mapping Using the Bayes Tree_
	- 2014: _RISE: An Incremental Trust-Region Method for Robust Online Sparse Least-Squares Estimation_
	- 2009: _Covariance Recovery from a Square Root Information Matrix for Data Association_

2. RBGD Mapping
	- 2012: _Kintinuous: Spatially Extended KinectFusion_
	- 2015: _Real-time Large Scale Dense RGB-D SLAM with Volumetric Fusion_

3. Cooperative Mapping
	- 2010: _Multiple Relative Pose Graphs for Robust Cooperative Mapping_

### Research: Prof. Sanjiv Singh, Dr. Ji Zhang

1. 3D Lider SLAM
	- 2014: _LOAM: Lidar Odometry and Mapping in Real-time_

## [Borg Lab, Georgia Tech](https://collab.cc.gatech.edu/borg/)
Prof. Frank Dellaert is one of the earlist researchers on SLAM. Now they mainly focus on developing backend algorithm for mapping or BA, including GTSAM, DDF-SAM, ILBA.

### People
Prof. Frank Dellaert

### Research

1. GTSAM: C++ library for SLAM backend, based on iSAM
	- 2006: _Square Root SAM: Simultaneous localization and mapping via square root information smoothing_
	- 2008: _iSAM: Incremental smoothing and mapping_
	- 2012: _iSAM2: Incremental Smoothing and Mapping Using the Bayes Tree_
	- 2014: _RISE: An Incremental Trust-Region Method for Robust Online Sparse Least-Squares Estimation_
    - 2010-IROS Subgraph-preconditioned conjugate gradients for large scale slam

2. DDF-SAM: Decentralized Data Fusion, for cooperative SLAM.
	- 2010: _DDF-SAM: Fully Distributed SLAM using Constrained Factor Graphs_
    - 2012: _Fully Distributed Scalable Smoothing and Mapping with Robust Multi-robot Data Association_
    - 2013: _DDF-SAM 2.0: Consistent Distributed Smoothing and Mapping_

3. iLBA: Incremental Light Bundle Adjustment, open source
	- 2013: _Incremental Light Bundle Adjustment for Robotics Navigation_    


## [Multiple Autonomous Robotic Systems Lab (MARS), University of Minnesota](http://mars.cs.umn.edu/)
Focus on VINS, Prof. Stergios Roumeliotis is the second author of **MSCKF**. 
Cooperate with google, and participate in Project Tango. 
Focus on cooperative mapping and application on mobile devices.

### People
Prof. Stergios Roumeliotis

### Research

1. Cooperative Mapping
	- An offline VI-SLAM algorithm
	- Create optimization with constraint and solve with Lagrangian multipler
	- All features and KFs are variables
	- Speed up by blocking Hessian, efficient when small number of overlapping features observed
	- Both point features, free lines and "Manhatton lines"
    - 2015: _Resource-Aware Large-Scale Cooperative 3D Mapping from Multiple Cell Phones_
    - 2016: _Large-Scale Cooperative 3D Visual-Inertial Mapping in a Manhattan World_

2. Square Root Inverse Sliding Window Filter (SR-ISWF)
	- Compare with MSCKF
    - 2015: _A Square Root Inverse Filter for Efficient Vision-aided Inertial Navigation on Mobile Devices_

3. C-KLAM: Constrained Keyframe-Based Localization and Mapping
	- 2013: _C-KLAM: Constrained Keyframe Localization and Mapping for Long-Term Navigation_
    - 2014: _C-KLAM: Constrained Keyframe-Based Localization and Mapping_

4. Incremental Batch Least-Squares (IBLS): SLAM for resource constrained mobile devices (like Tango)
	- 2015: _A Square Root Inverse Filter for Efficient Vision-aided Inertial Navigation on Mobile Devices_
    - 2014: _Efficient Visual-Inertial Navigation using a Rolling-Shutter Camera with Inaccurate Timestamps_

5. Visual-Inertial Navigation System (VINS) using a Rolling-Shutter Camera

## [Prof. Anastasios Mourikis, UC Riverside](http://www.ee.ucr.edu/~mourikis/)
Prof. Anastasios Mourikis is the athor of MSCKF.

## [Marine Robotics Group, MIT](https://marinerobotics.mit.edu/)

### People
Prof. John Leonard

### Research
1.  Visual SLAM
	- 2016 ICRA: High-Performance and Tunable Stereo Reconstruction
    - 2015: Monocular SLAM-Supported Object Recognition

## [Autonomous Systems Lab, ETH](http://www.asl.ethz.ch/)
Seems more focus on different robot systems.

### People
Prof. Roland Siegwart

1. Calibration
	- Kalibr
    
2. VIO
	- 2015: Robust Visual Inertial Odometry Using a Direct EKF-Based Approach (ROVIO)
    - 2013: Keyframe-Based Visual-Inertial SLAM Using Nonlinear Optimization (OKVIS)

## [Computer Vision and Geometry Group, ETH](https://www.cvg.ethz.ch/)
To check their works from their [youtube channel](https://www.youtube.com/user/aslteam/videos)

### People
Prof. Marc Pollefeys, Dr. Lionel Heng

### Research
1. Calibration
	- 2015 JFR: _Leveraging Image-based Localization for Infrastructure-based Calibration of a Multi-camera Rig_
    
2. Visual Localization
	- Large scale
    - Place recognition
    


## [Robotics and Perception Group, University of Zurich](http://rpg.ifi.uzh.ch/index.html)

### People
Prof. Davide Scaramuzza

### Research

1. VINS	
    - 2016 TRO: On-Manifold Preintegration for Real-Time Visual-Inertial Odometry
    - 2014 ICRA: SVO: Fast Semi-Direct Monocular Visual Odometry
    - 2014 ICRA: REMODE: Probabilistic, Monocular Dense Reconstruction in Real Time
    
2. Monocular Dense Reconstruction

3. UAV

4. Event-Camera


## [Robot Vision Group, Imperial Colledge London](https://wp.doc.ic.ac.uk/robotvision/)
Prof. Andrew Davison is one of the most important researchers on SLAM in this world. His important works include: MonoSLAM, KinectFusion, DTAM, SLAM++ (Object based SLAM), ...

### People
Prof. Andrew Davison

### Research

1. Dense Visual Odometry

2. Event-Camera

3. Object SLAM

## [Dyson Robotics Lab, Imperial Colledge London](https://wp.doc.ic.ac.uk/sleutene/)
Dr. Stefan Leutenegger is the author of OKVIS, he received his PhD degree from Autonomous Systems Lab of ETH.

### People
Dr. Stefan Leutenegger, Prof. Andrew Davison

### Research

1. VINS
	- OKVIS
    - 2015 IJRR: _Keyframe-based visual–inertial odometry using nonlinear optimization_
    
2. Dense RBGD SLAM
    - 2015: _ElasticFusion: Dense SLAM Without A Pose Graph_
    
3. Event-Camera

## [Autonomous Intelligent Systems, University of Freiburg](http://ais.informatik.uni-freiburg.de/index_en.php)

## [Computer Vision Group, Technical University of Munich](http://vision.in.tum.de/)

### People
Prof. Daniel Cremers.

### Research
1. LSD-SLAM
	- One of the most popular visual SLAM algorithm
	- Semi-dense
    
2. DSO: direct sparse odometry

## [Robotics, Perception and Realtime Group, Univiersity of Zaragoza](http://robots.unizar.es/)



### People
Prof. Juan D. Tardos, 	Prof. Javier Civera

### Research
1. ORB-SLAM
	- One of the most popular visual SLAM algorithm
	- Sparse ORB feature
	- ORB based BoW for loop close detection
    
2. Visual-Inertial Direct SLAM
    

## KIT
## Dr. Andreas Geiger
## T. Barfoot – Autonomous Space Robotics Laboratory, University of Toronto

# Blogs and Websites

## [Tombone's Computer Vision BLog](http://www.computervisionblog.com/)

## [PaoPao Robitics](http://www.slamcn.org/)

# Tutorials

## [2014 CVPR Visual SLAM Tutorial](http://frc.ri.cmu.edu/~kaess/vslam_cvpr14/)

## [2015 ICCV SLAM Workshop](https://wp.doc.ic.ac.uk/thefutureofslam/)

## [2016 ICRA SLAM Tutorial](http://www.dis.uniroma1.it/~labrococo/tutorial_icra_2016/)

# Topics To Learn

## Point Clous to Mesh

Poisson reconstruction, VRIP(volumetric range image processing), ...

## SunJian's work

## Unsupervised Intrinsic Calibration of Depth Sensors via SLAM, 2013 RSS

## Visual Inertial Direct SLAM, UniZar & UniPenn, 2016 ICRA

## DPPTAM: Dense piecewise planar tracking and mapping from a monocular sequence, 2015 IROS

## DSO: Direct sparse odometry, TUM

## 

