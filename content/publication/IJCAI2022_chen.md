+++
abstract = "Object detection through either RGB images or the LiDAR point clouds has been extensively explored in autonomous driving. However, it remains challenging to make these two data sources complementary and beneficial to each other.  In this paper, we propose AutoAlign, an automatic feature fusion strategy for 3D object detection. Instead of establishing deterministic correspondence with camera projection matrix, we model the mapping relationship between the image and point clouds with a learnable alignment map. This map enables our model to automate the alignment of non-homogenous features in a dynamic and data-driven manner. Specifically, a cross-attention feature alignment module is devised to adaptively aggregate pixel-level image features for each voxel. To enhance the semantic consistency during feature alignment, we also design a self-supervised cross-modal feature interaction module, through which the model can learn feature aggregation with instance-level feature guidance. Extensive experimental results show that our approach can lead to 2.3 mAP and 7.0 mAP improvements on the KITTI and nuScenes datasets, respectively. Notably, our best model reaches 70.9 NDS on the nuScenes testing leaderboard, achieving competitive performance among various state-of-the-arts.  "
date = "2022-04-22"
image = ""
image_preview = ""
math = false
publication = "IJCAI 2022"
publication_short = ""
selected = false
title = "AutoAlign: Pixel-Instance Feature Aggregation for Multi-Modal 3D Object Detection"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/abs/2201.06493"
url_project = "/project/deeplearning"
url_slides = ""
url_video = ""

[[authors]]
    name = "Zehui Chen"
    is_member = true
[[authors]]
    name = "Zhenyu Li"
    is_member = true
[[authors]]
    name = "Shiquan Zhang"
    is_member = true
[[authors]]
    name = "Liangji Fang"
    is_member = true
[[authors]]
    name = "Qinhong Jiang"
    is_member = true
[[authors]]
    name = "Feng Zhao"
    is_member = true
[[authors]]
    name = "Bolei Zhou"
    is_member = true
[[authors]]
    name = "Hang Zhao"
    is_member = true
+++


You can add information in $\LaTeX$ and *Markdown* here.
