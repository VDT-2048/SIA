# VI-RGBT3500
VI-RGBT3500 dataset and different illumination challenge scenes
The VI-RGBT3500 dataset contains 630 pairs of variable illumination images from the VT821, VT1000, and VT5000, 1190 pairs of images from the VDT2048, and all images from the VI-RGBT1500 dataset. Finally, we select 1775 pairs of images as the training dataset and the remaining 1725 pairs of images as the test dataset, as shown in Fig. 8.

![8](https://github.com/VDT-2048/SIA/assets/101933818/0a3d6ab7-5651-4efd-b6a7-fda21b64e6e7)


We divide the dataset into two main categories based on illumination: even illumination (EI) and uneven illumination (UEI). Even illumination is then divided into four subcategories: normal illumination (NI), low illumination 1 (LI1), low illumination 2 (LI2), and extremely low illumination (ELI). Normal illumination indicates that the salient object is in a well-lit scene, and illumination does not have any negative impact on the detection process. Extremely low illumination means the salient object is completely invisible in the RGB image. Then, the illumination condition between normal illumination and extremely low illumination is roughly divided into two levels (low illumination 1 and low illumination 2), where low illumination 2 is dimmer than low illumination 1, as shown in Fig. 7.

![7](https://github.com/VDT-2048/SIA/assets/101933818/84bb54d8-5e1f-46c5-b7c0-41238c98718f)


Uneven illumination is classified into three categories: uneven illumination A (UIA), uneven illumination B (UIB), and uneven illumination C (UIC). UIA represents a salient object located entirely in a well-illumination location, as shown in the first line of Fig. 3. UIB represents a portion of the salient object located in a well illumination location, as shown in the second line of Fig 3. The UIC represents a salient object located entirely in the low-illumination region, as shown in the third line of Fig. 3.

![3](https://github.com/VDT-2048/SIA/assets/101933818/8231900b-0ca1-4c87-bcde-3aabd9c2e9d2)


The variable illumination must cause the object to shadow. And the shadow of the object can seriously interfere with the detection process. Therefore, we treat images with shadows on the object as a separate class and are defined as shadow interference (SI).



# Download the dataset and code
The dataset is available at: VI-RGBT3500. 
https://pan.baidu.com/s/1zuAyVN4hHsEQWbgw0d9AUQ?pwd=nvb7 

The test datasets divided according to different illumination challenge scenes are available at: challenge scenes data(VI-RGBT3500).
https://pan.baidu.com/s/1zuAyVN4hHsEQWbgw0d9AUQ?pwd=nvb7 

# SIA code
The code is available at: SIA.
https://pan.baidu.com/s/1zuAyVN4hHsEQWbgw0d9AUQ?pwd=nvb7 

# Results of SIA
We provide the resutls of our SIA on VT3500 datasets at: saliency maps.
https://pan.baidu.com/s/1zuAyVN4hHsEQWbgw0d9AUQ?pwd=nvb7 

# Paper
https://www.sciencedirect.com/science/article/abs/pii/S0143816623003718


[2024-SIA RGB-T salient object detection network with salient-illumination awareness.pdf](https://github.com/VDT-2048/SIA/files/14155462/2024-SIA.RGB-T.salient.object.detection.network.with.salient-illumination.awareness.pdf)




# Citation
Kechen Song, Hongwei Wen, Yingying Ji, Xiaotong Xue, Liming Huang, Yunhui Yan, Qinggang Meng. SIA: RGB-T Salient Object Detection Network with Salient-Illumination Awareness [J]. Optics and Lasers in Engineering, 2024, 172, 107842.

# Related Work of RGB-T Salient Object Detection
[1]  Multiple Graph Affinity Interactive Network and A Variable Illumination Dataset for RGBT Image Salient Object Detection [J]. IEEE Transactions on Circuits and Systems for Video Technology, 2023, 33(7), 3104-3118.
https://github.com/huanglm-me/VI-RGBT1500

# Related Survey
RGB-T Image Analysis Technology and Application: A Survey [J]. Engineering Applications of Artificial Intelligence,  2023, 120, 105919.
https://www.sciencedirect.com/science/article/abs/pii/S0952197623001033

#  Related Work of Visible-Depth-Thermal Salient Object Detection
[1]  A Novel Visible-Depth-Thermal Image Dataset of Salient Object Detection for Robotic Visual Perception [J]. IEEE/ASME Transactions on Mechatronics, 2023, 28(3), 1558-1569.
https://github.com/VDT-2048/VDT-Dataset

[2]  Lightweight Multi-level Feature Difference Fusion Network for RGB-D-T Salient Object Detection [J]. Journal of King Saud University - Computer and Information Sciences, 2023
https://github.com/VDT-2048/MFDF

[3]  MFFNet: Multi-modal Feature Fusion Network for VDT Salient Object Detection[J]. IEEE Transactions on Multimedia, 2023.
https://ieeexplore.ieee.org/abstract/document/10171982
 
