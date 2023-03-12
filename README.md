# C2BN: Cross-modality and Cross-scale Balance Network for multi-modal 3D Object Detection

![Image](https://user-images.githubusercontent.com/59462530/224537346-bbb3a4f1-78a4-4ffa-a131-3a175c8efdac.png)

C2BN is a novel Camera-LiDAR fusion network. C2BN comprise two  modules: Cross-Modality balance Network (CMN) utilizes cross-modality attention mechanisms to balance the importance and receptive field of two modalities. Cross-Scale balance Module (CSN) employs cross-scale attention mechanisms to reduce the imbalance in multi-level features. 

## Performance on KITTI Dataset(3712 training, 3769 validation)

**C2BN (SECOND+TOOD) VS MVXNet:**
```
new 40 recall points
Car:      Easy@0.7       Moderate@0.7   Hard@0.7
bev:  AP: 94.01 / 92.29, 88.22 / 88.02, 85.66 / 85.65
3d:   AP: 90.53 / 88.11, 79.07 / 78.44, 75.79 / 73.99
```
## Performance on Waymo Dataset
This will be update later.

