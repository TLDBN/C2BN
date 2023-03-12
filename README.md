# C2BN: Cross-modality and Cross-scale Balance Network for multi-modal 3D Object Detection

![Image](https://user-images.githubusercontent.com/59462530/224537346-bbb3a4f1-78a4-4ffa-a131-3a175c8efdac.png)

Multi-modal 3D object detection that classifies and locates objects in 3D space by combining point-clouds captured by lidars and RGB images captured by cameras, serves as the basis for autonomous driving. Most of the existing methods aggregate features from point-clouds and images by plain element-wise additions or multiplications. Although these methods improve detection accuracy, such simple operations have difficulties in balancing both modalities. Further, the multi-level features from images also suffer from imbalance problems in receptive fields. To address the above problems, we propose two novel modules: Cross-Modality balance Network (CMN) utilizes cross-modality attention mechanisms to balance the importance and receptive field of two modalities. Cross-Scale balance Module (CSN) employs cross-scale attention mechanisms to reduce the imbalance in multi-level features. Experiments are performed on the challenging benchmark: KITTI. The experimental results show consistent improvements in different 3D object detection frameworks, which verifies the effectiveness and generality of our proposed networks.

#Result
