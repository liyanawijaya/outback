# OUTBACK: A Multimodal Synthetic Dataset for Rural Australian Off-road Robot Navigation

<br> Nipuna Wijayathunga, Dulitha Dabare, Alexander Rassau, Douglas Chai, Shamsul Islam

# Introduction

<p>One of the most important aspects of robot scene understanding is semantic segmentation of external environments. Urban environment semantic segmentation has been extensively investigated by researchers and many real-world and synthetic datasets have been utilised to develop highly accurate segmentation results. However, the number of off-road datasets available for robot navigation research remains limited.  To address this, we introduce a novel framework to generate varied photorealistic synthetic off-road datasets capable of supporting multiple sensor modalities. To evaluate this approach, a synthetic multimodal dataset for off-road ground robot navigation in typical Western Australian outback conditions has been created. The robot simulations for synthetic dataset generation were conducted using the NVIDIA Isaac Sim robotics simulator platform and the dataset consists of camera, LiDAR, and IMU sensor data of two synthetic off-road environment models, including 18 semantic classes. Experiments on the dataset were performed using three state-of-the-art image segmentation models. These experiments examine the effectiveness of urban semantic segmentation deep learning models on rural off-road driving scenarios and additionally evaluate the Sim2Real transfer of an off-road semantic segmentation model pretrained on our synthetic dataset.The following figures from the OUTBACK dataset represent an RGB monocular image (left) and the corresponding semantic annotation (right), respectively.<p>
<!--|-------------------------|-------------------------|-->
<!--|![](rgb_23919.png)|![](semantic_segmentation_23919.png)|-->
<p float="left">
<img src="rgb_23919.png" width="45%" />
<img src="semantic_segmentation_23919.png" width="45%" />
</p>

# Robot Plaform

NVIDIA Carter v1

# Sensor Payload

RGB monocular camera, LiDAR sensor, IMU

# Dataset

You can download the annotated dataset at the following links

- **RGB Images** [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/EvagmxpotyZDnwVRSSrZtYgBPA1sJ_oy_b0sznM7mc2cxg?e=jzvmKy)
- **RGB Image Semantic Annotations** [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/EoGuNjvv7RFOn9HBkQ7s05kBomQcjA7gX3558gxofaaSlg?e=b9CdDG)
- **IMU Sensor Data** [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/En8SlygSZ3pBhu6o8G8HW9YB5X9ZEPaURTYEIX5ZOpAszg?e=0T2T4a)
- **LiDAR Depth Data** [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/Etb842pOLoVOhAeQVswoLv8BOIArLFnWES-yX-alDPOFVQ?e=wuq6lW)
- **LiDAR Semantic Annotations** [Download](https://edithcowanuni-my.sharepoint.com/:f:/g/personal/lwijayat_our_ecu_edu_au/Et6_6MbN7htLvPgQC5gjY6IBXwA5OfuSKPdOHeiRdCkU0g?e=6npsHt)

# License

This project is released under the [Apache 2.0 license](LICENSE).

# Acknowledgement

The source code for experiments in OUTBACK is heavily based on [MMSegmentation](https://github.com/open-mmlab/mmsegmentation). 
