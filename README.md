# Object_SLAM-
DEMO for ITS "Object SLAM with Robust Quadric Initialization and Mapping for Dynamic Outdoors"
submitted for IEEE Transactions on Intelligent Transportation Systems 

[![Object SLAM with Robust Quadric Initialization and Mapping for Dynamic Outdoors](https://res.cloudinary.com/marcomontalbano/image/upload/v1675908893/video_to_markdown/images/youtube--ghm2eYfhBDs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ghm2eYfhBDs "Object SLAM with Robust Quadric Initialization and Mapping for Dynamic Outdoors")

Abstract:
Object SLAM is a popular approach in autonomous driving and robotics, and accurate object perception is the current problem to be solved. State-of-the-art object SLAM algorithms for outdoors are based on assumptions and are sensitive to observation noise, which limits their application in real-world scenarios. 
To address these issues, we propose an object SLAM system with a novel quadric initialization algorithm that does not rely on the planar assumption and is robust to partial observations. An additional thread is used to efficiently refine the ellipsoid parameters within a local sliding window composed of keyframes and improve the accuracy of the quadric mapping. An automatic object data association algorithm capable of detecting object motion while associating objects across frames is also proposed to improve the robustness and accuracy of object association.  Furthermore, we propose a joint optimization framework to optimize camera poses, object landmarks, and static point clouds in the local mapping thread for global optimization while maintaining a globally consistent map.
Experimental results on the real-world KITTI dataset show that the proposed system is more robust and significantly outperforms current state-of-the-art methods in quadric initialization and mapping in outdoor scenarios. Overall, the proposed system demonstrates real-time performance.

