# OUTBACK: A Multimodal Synthetic Dataset for Rural Australian Off-road Robot Navigation



This is the code base for:

[OUTBACK: A Multimodal Synthetic Dataset for Rural Australian Off-road Robot Navigation].
<br> Nipuna Wijayathunga, Dulitha Dabare, Alexander Rassau, Douglas Chai, Shamsul Islam

# Introduction

One of the most important aspects of robot scene understanding is semantic segmentation of external environments. Urban environment semantic segmentation has been extensively investigated by researchers and many real-world and synthetic datasets have been utilised to develop highly accurate segmentation results. However, the number of off-road datasets available for robot navigation research remains limited.  To address this, this paper introduces a novel framework to generate varied photorealistic synthetic off-road datasets capable of supporting multiple sensor modalities. To evaluate this approach, a synthetic multimodal dataset for off-road ground robot navigation in typical Western Australian outback conditions has been created. The robot simulations for synthetic dataset generation were conducted using the NVIDIA Isaac Sim robotics simulator platform and the dataset consists of camera, LiDAR, and IMU sensor data of two synthetic off-road environment models, including 18 semantic classes. Experiments on the dataset were performed using three state-of-the-art image segmentation models. These experiments examine the effectiveness of urban semantic segmentation deep learning models on rural off-road driving scenarios and additionally evaluate the Sim2Real transfer of an off-road semantic segmentation model pretrained on our synthetic dataset.


# License

This project is released under the [Apache 2.0 license](LICENSE).

# Acknowledgement

The source code of GANav is heavily based on [MMSegmentation](https://github.com/open-mmlab/mmsegmentation). 
