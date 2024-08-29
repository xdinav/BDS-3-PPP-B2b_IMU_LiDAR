# BDS-3-PPP-B2b_IMU_LiDAR
Enhancing BDS-3 PPP-B2b real-time positioning performance by Tightly Integrating IMU and LiDAR in GNSS-degraded environment
Currently, BDS-3 can provide real-time precise point positioning (PPP) services via PPP-B2b signals. However, under the complex Global Navigation Satellite System (GNSS)-degraded environment, the BDS-3 PPP-B2b positioning performance is severely influenced. A tightly-coupled PPP/ inertial measurement unit (IMU)/ Light Detection and Ranging (LiDAR) combination is proposed, in which the original undifferenced pseudorange and carrier observations, IMU measurements, and LiDAR planar features are fused via an extended Multi-State Constraint Kalman Filter (MSCKF). Moreover, since only the real-time GPS and BDS precise corrections are provided via BDS-3 PPP-B2b signal, the Galileo satellites are further utilized using broadcast ephemeris to add more available satellites. And to improve the real-time computing efficiency, a planar feature tracking model based on the ground segmentation is adopted, which consists of the point cloud segmentation, planar feature extraction and fusion, and data correlation.
The on-board experimental hardware platform is shown as follows.

![platform](https://github.com/user-attachments/assets/a228e7d6-6155-4985-8975-dd9e97001eab)

The observation environments in the campus and park are shown in the following two figure. The download website is 

![campus](https://github.com/user-attachments/assets/d0b8820e-3cd2-48da-a535-c0e0e0027bc9)

![park](https://github.com/user-attachments/assets/69cd32d0-2b0e-479a-8093-a56b489bf385)
