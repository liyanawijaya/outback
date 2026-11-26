# OUTBACK: A Multimodal Synthetic Dataset for Rural Australian Off-road Robot Navigation

<br> **Liyana Wijayathunga** <sup>1</sup>, **Dulitha Dabare** <sup>1</sup>, **Alexander Rassau** <sup>1</sup>, **Douglas Chai** <sup>1</sup>, **Shamsul Islam** <sup>2</sup><br>
<sup>1</sup> School of Engineering, Edith Cowan University, Perth, Australia
<br><sup>2</sup> School of Science, Edith Cowan University, Perth, Australia

# Introduction

One of the most important aspects of robot scene understanding is semantic segmentation of external environments. Urban environment semantic segmentation has been extensively investigated by researchers and many real-world and synthetic datasets have been utilised to develop highly accurate segmentation results. However, the number of off-road datasets available for robot navigation research remains limited.  To address this, we introduce a novel framework to generate varied photorealistic synthetic off-road datasets capable of supporting multiple sensor modalities. 
<br>
To evaluate this approach, a synthetic multimodal dataset for off-road ground robot navigation in typical Western Australian outback conditions has been created. The robot simulations for synthetic dataset generation were conducted using the NVIDIA Isaac Sim robotics simulator platform and the camera, LiDAR, and IMU sensor data was collected using four synthetic off-road environment scenarios. After revising some of the semantic classes introduced in our DICTA 2024 conference [paper](https://ieeexplore.ieee.org/abstract/document/10869581), we make available our OUTBACK off-road dataset in our [journal paper](https://link.springer.com/article/10.1007/s10846-025-02340-2), which consists of a total of 7641 image frames with respective annotations covering 16 semantic classes. Experiments on the dataset were performed using three state-of-the-art image segmentation models. These experiments examine the effectiveness of urban semantic segmentation deep learning models on rural off-road driving scenarios and additionally evaluate the Sim2Real transfer of an off-road semantic segmentation model pretrained on our synthetic dataset. The following figures from the OUTBACK dataset represent an RGB monocular image (left) and the corresponding coloured semantic annotation (right), respectively.
<br/>   <br/>
<!--|-------------------------|-------------------------|-->
<!--|![](rgb_23919.png)|![](semantic_segmentation_23919.png)|-->
<p float="left">
<img src="rgb_02779.png" width="45%" />
<img src="semantic_segmentation_02779.png" width="45%" />
</p>

# Simulation Setup
### Software
Unreal Engine 5<br>
NVIDIA Isaac Sim
### Robot Model
NVIDIA Carter v1
### Sensor Payload
RGB monocular camera <br>
LiDAR sensor<br>
IMU

# Dataset

You can download the annotated dataset at the following links-
<br>

**Version 2.0 - Second release of the extended OUTBACK dataset, which includes four environment scenarios containing camera and LiDAR sensor data**
<br>
The LiDAR depth and semantic annotation frames have been converted to the camera image plane and included in the dataset. 

Train data [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgByoaB8Om5cRrMx0OPjika5AVMODLDq1lUFgPJ0_borO7o?e=tDnjJk)
<br>

Validation data [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgBSgTyfOYpDSqiMYgNLp5U3AYqS02hcj0_V-oyuJqn2cqY?e=yPZ0qK)
<br>

Test data [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgApo5w011KIR4-DJsBCqJewAelYiMcf3OVsP4HTeJlQyXs?e=Cmtakt)
<br>

[Dataset splitting information](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgCKUbxtwrndRJKbYiVRc4QMAXIBkYUNzydDgwPBgrgXgo8?e=pILUWj)
<br>
<br>



**Version 1.0 - First release of the OUTBACK dataset, which includes two environment scenarios containing camera, LiDAR and IMU data**
<br>

Camera sensor data [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgCRgmfXs_9BS5KF6PRN1yykAcYKGXU7neqr4GV4c8IBkSQ?e=mGIEPb)
<br>

IMU sensor data [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgB_EpcoEmd6QYbuqPBvB1vWAeV_WRD2lEU2BCF-WTqQLM4?e=LLHptc)
<br>

LiDAR sensor data [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/IgClj47Di2CMQLADQK5p8roxAbk5pkRs-OPuz3F-cOopUro?e=kZacMo)
<br>


# Acknowledgement
The Isaac Sim synthetic environments were primarily developed using Unreal Engine assets provided by the open-source asset pack available at the given link. [Unreal Engine asset pack](https://www.unrealengine.com/en-US/blog/rural-australia-environment-collection-now-available-for-free) <br>
The source code for experiments in OUTBACK is heavily based on [MMSegmentation](https://github.com/open-mmlab/mmsegmentation). 
<br>

This project is released under the [Apache 2.0 license](LICENSE).

