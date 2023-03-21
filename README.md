# 3D-VL-SOT
Currently, tasks in this repository include **3D Object Tracking (3DOT)** and **Vision Language Tracking (VL)** and **Un/Self-Supervised**. 
- [3D](#3d-object-tracking)
- [VL](#vision-language-tracking)
- [Un/Self-Supervised](#un-self-supervised)

## 3D Object Tracking
### 2022
- **CMT**: Zhiyang Guo, Yunyao Mao, Wengang Zhou, Min Wang, Houqiang Li. Context-Matching-Guided Transformer for 3D Tracking in Point Clouds. In _ECCV_, 2022. [Paper] [[Code]](https://github.com/jasongzy/CMT)
- **STNet**: Le Hui, Lingpeng Wang, Linghua Tang, Kaihao Lan, Jin Xie, Jian Yang. 3D Siamese Transformer Network for Single Object Tracking on Point Clouds. In _ECCV_, 2022. [[Paper]](https://arxiv.org/abs/2207.11995) [[Code]](https://github.com/fpthink/STNet)
- **M2-Track**: Chaoda Zheng, Xu Yan, Haiming Zhang, Baoyuan Wang, Shenghui Cheng, Shuguang Cui, Zhen Li. Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds. In _CVPR_, 2022 oral. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Beyond_3D_Siamese_Tracking_A_Motion-Centric_Paradigm_for_3D_Single_CVPR_2022_paper.pdf) [[Code]](https://github.com/Ghostish/Open3DSOT)
- **PTTR**: Changqing Zhou, Zhipeng Luo, Yueru Luo, Tianrui Liu, Liang Pan, Zhongang Cai, Haiyu Zhao, Shijian Lu. PTTR: Relational 3D Point Cloud Object Tracking with Transformer. In _CVPR_, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_PTTR_Relational_3D_Point_Cloud_Object_Tracking_With_Transformer_CVPR_2022_paper.pdf) [[Code]](https://github.com/jasonkks/pttr)
- **GPT**: Minseong Park, Hongje Seong, Wonje Jang, Euntai Kim. Graph-Based Point Tracker for 3D Object Tracking in Point Clouds. In _AAAI_, 2022. [[Paper]](https://www.aaai.org/AAAI22Papers/AAAI-5325.ParkM.pdf) [Code]
- **3D DetecTrack**: Junho Koh, Jaekyum Kim, Jinhyuk Yoo, Yecheol Kim, Dongsuk Kum, Jun Won Choi. Joint 3D Object Detection and Tracking Using Spatio-Temporal Representation of Camera Image and LiDAR Point Clouds. In _AAAI_, 2022. [[Paper]](https://arxiv.org/abs/2112.07116) [Code]

### 2021
- **MLVSNet**: Zhoutao Wang, Qian Xie, Yu-Kun Lai, Jing Wu, Kun Long, Jun Wang. MLVSNet: Multi-level Voting Siamese Network for 3D Visual Tracking. In _ICCV_, 2021. [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_MLVSNet_Multi-Level_Voting_Siamese_Network_for_3D_Visual_Tracking_ICCV_2021_paper.pdf) [[Code]](https://github.com/codewzt/mlvsnet)
- **BAT**: Chaoda Zheng, Xu Yan, Jiantao Gao, Weibing Zhao, Wei Zhang, Zhen Li, Shuguang Cui. Box-Aware Feature Enhancement for Single Object Tracking on Point Clouds. In _ICCV_, 2021. [[Paper]](https://arxiv.org/abs/2108.04728) [[Code]](https://github.com/Ghostish/Open3DSOT)
- **CenterPoint**: Tianwei Yin, Xingyi Zhou, Philipp Krähenbühl. Center-based 3D Object Detection and Tracking. In _CVPR_, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yin_Center-Based_3D_Object_Detection_and_Tracking_CVPR_2021_paper.pdf) [[Code]](https://github.com/tianweiy/CenterPoint)
- **PTT**: Jiayao Shan, Sifan Zhou, Zheng Fang, Yubo Cui. PTT: Point-Track-Transformer Module for 3D Single Object Tracking in Point Clouds. In _IROS_, 2021. [[Paper]](https://arxiv.org/abs/2108.06455) [[Code]](https://github.com/shanjiayao/PTT)
- **lttr**: Yubo Cui, Zheng Fang, Jiayao Shan, Zuoxu Gu, Sifan Zhou. 3D Object Tracking with Transformer. In _BMVC_, 2021. [[Paper]](bmvc2021-virtualconference.com/assets/papers/1445.pdf) [[Code]](https://github.com/3bobo/lttr)

### 2020
- **???**: Peiliang Li, Jieqi Shi, Shaojie Shen. Joint Spatial-Temporal Optimization for Stereo 3D Object Tracking. In _CVPR_, 2020. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Joint_Spatial-Temporal_Optimization_for_Stereo_3D_Object_Tracking_CVPR_2020_paper.pdf) [Code]
- **P2B**: Haozhe Qi, Chen Feng, Zhiguo Cao, Feng Zhao, Yang Xiao. P2B: Point-to-Box Network for 3D Object Tracking in Point Clouds. In _CVPR_, 2020. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_P2B_Point-to-Box_Network_for_3D_Object_Tracking_in_Point_Clouds_CVPR_2020_paper.pdf) [[Code]](https://github.com/HaozheQi/P2B)
- **3D-ZeF**: Malte Pedersen, Joakim Bruslund Haurum, Stefan Hein Bengtson, Thomas B. Moeslund. 3D-ZeF: A 3D Zebrafish Tracking Benchmark Dataset. In _CVPR_, 2020. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Pedersen_3D-ZeF_A_3D_Zebrafish_Tracking_Benchmark_Dataset_CVPR_2020_paper.pdf) [[Project]](https://vap.aau.dk/3d-zef/) [[Challenge]](https://motchallenge.net/data/3D-ZeF20/)
- **F-Siamese**: Hao Zou, Jinhao Cui, Xin Kong, Chujuan Zhang, Yong Liu, Feng Wen, Wanlong Li. F-Siamese Tracker: A Frustum-based Double Siamese Network for 3D Single Object Tracking. In _IROS_, 2020. [[Paper]](http://ras.papercept.net/images/temp/IROS/files/1722.pdf) [Code]

### Preprints
- **PTTR++**: Zhipeng Luo, Changqing Zhou, Liang Pan, Gongjie Zhang, Tianrui Liu, Yueru Luo, Haiyu Zhao, Ziwei Liu, Shijian Lu. PTTR++: Exploring Point-BEV Fusion for 3D Point Cloud Object Tracking with Transformer.[[Paper]](https://arxiv.org/pdf/2208.05216) [[Code]](https://github.com/Jasonkks/PTTR)
- **PCET**: Pan Wang, Liangliang Ren, Shengkai Wu, Jinrong Yang, En Yu, Hangcheng Yu, Xiaoping Li. Implicit and Efficient Point Cloud Completion for 3D Single Object Tracking. [[Paper]](https://arxiv.org/abs/2209.00522) [Code]

## Vision Language Tracking
### 2017
- **LPN**: Zhenyang Li, Ran Tao, Efstratios Gavves, Cees G. M. Snoek, Arnold W.M. Smeulders. Tracking by Natural Language Specification. In _CVPR_, 2017.[[Paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Tracking_by_Natural_CVPR_2017_paper.pdf) [Code]

### 2020
- **RTNL**: Qi Feng, Vitaly Ablavsky, Qinxun Bai, Guorong Li, Stan Sclaroff. Real-time Visual Object Tracking with Natural Language Description. In _WACV_, 2020. [[Paper]](https://arxiv.org/pdf/1907.11751v3.pdf) [Code]

### 2021
- **CapsuleTNL**: Ding Ma, Xiangqian Wu. Capsule-based Object Tracking with Natural Language. In _ACMMM_, 2021.[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475349)
- **SNLT**: Qi Feng, Vitaly Ablavsky, Qinxun Bai, Stan Sclaroff. Siamese Natural Language Tracker: Tracking by Natural Language Descriptions with Siamese Trackers. In _CVPR_, 2021. [[Paper]](http://openaccess.thecvf.com//content/CVPR2021/papers/Feng_Siamese_Natural_Language_Tracker_Tracking_by_Natural_Language_Descriptions_With_CVPR_2021_paper.pdf) [[Code]](https://github.com/fredfung007/snlt)
- **TNL2K**: Xiao Wang, Xiujun Shu, Zhipeng Zhang, Bo Jiang, YaoWei Wang, Yonghong Tian, Feng Wu. Towards More Flexible and Accurate Object Tracking with Natural Language: Algorithms and Benchmark. In _CVPR_, 2021. [[Paper]](http://openaccess.thecvf.com//content/CVPR2021/papers/Wang_Towards_More_Flexible_and_Accurate_Object_Tracking_With_Natural_Language_CVPR_2021_paper.pdf) [[Code]](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)

### 2022
- **ModaMixer**: Mingzhe Guo, Zhipeng Zhang, Heng Fan, Liping Jing. Divert More Attention to Vision-Language Tracking. In _NeurIPS_, 2022. [[Paper]](https://openreview.net/forum?id=NhrbIME2Ljl) [[Code]](https://github.com/JudasDie/SOTS)

### 2023
- **TransVLT**: Haojie Zhao, Xiao Wang, Dong Wang, Huchuan Lu, Xiang Ruan. Transformer vision-language tracking via proxy token guided cross-modal fusion. In _PR Letters_, 2023. [[Paper]](https://www.sciencedirect.com/science/article/pii/S0167865523000545?via%3Dihub)

### Preprints
stay tuned

## Un-Self-Supervised
### 2019
- **UDT**: Ning Wang, Yibing Song, Chao Ma, Wengang Zhou, Wei Liu, Houqiang Li. Unsupervised Deep Tracking. In _CVPR_, 2019. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Unsupervised_Deep_Tracking_CVPR_2019_paper.pdf) [[Code]](https://github.com/594422814/UDT)
- **LUDT**:Ning Wang, Wengang Zhou, Yibing Song, Chao Ma, Wei Liu, Houqiang Li. Unsupervised Deep Representation Learning for Real-Time Tracking. In International Journal of Computer Vision Volume 129 Issue 2 Feb 2021.  [[Paper]](https://594422814.github.io/LUDT/LUDT.pdf) [[Code]](https://github.com/594422814/UDT)

### 2020
- **MAST**: Zihang Lai, Erika Lu, Weidi Xie. MAST: A Memory-Augmented Self-supervised Tracker. In _CVPR_, 2020. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lai_MAST_A_Memory-Augmented_Self-Supervised_Tracker_CVPR_2020_paper.pdf) [[Code]](https://github.com/zlai0/MAST)

### 2021
- **PUL**: Qiangqiang Wu, Jia Wan, Antoni B. Chan. Progressive Unsupervised Learning for Visual Object Tracking. In _CVPR_, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/html/Wu_Progressive_Unsupervised_Learning_for_Visual_Object_Tracking_CVPR_2021_paper.html) [Code]

- **EMUT**: Adam W. Harley, Yiming Zuo, Jing Wen, Ayush Mangal, Shubhankar Potdar, Ritwick Chaudhry, Katerina Fragkiadaki. Track, Check, Repeat: An EM Approach to Unsupervised Tracking. In _CVPR_, 2021. [[Paper]](http://openaccess.thecvf.com//content/CVPR2021/papers/Harley_Track_Check_Repeat_An_EM_Approach_to_Unsupervised_Tracking_CVPR_2021_paper.pdf) [Code]

### 2022
- **ULAST**: Qiuhong Shen, Lei Qiao, Jinyang Guo, Peixia Li, Xin Li, Bo Li, Weitao Feng, Weihao Gan, Wei Wu, Wanli Ouyang. Unsupervised Learning of Accurate Siamese Tracking. In _CVPR_, 2022. [[Paper]](http://openaccess.thecvf.com//content/CVPR2022/papers/Shen_Unsupervised_Learning_of_Accurate_Siamese_Tracking_CVPR_2022_paper.pdf) [[Code]](https://github.com/florinshum/ulast)
- **UDAT**: Junjie Ye, Changhong Fu, Guangze Zheng, Danda Pani Paudel, Guang Chen. Unsupervised Domain Adaptation for Nighttime Aerial Tracking. In _CVPR_, 2022. [[Paper]](http://openaccess.thecvf.com//content/CVPR2022/papers/Ye_Unsupervised_Domain_Adaptation_for_Nighttime_Aerial_Tracking_CVPR_2022_paper.pdf) [[Code]](https://github.com/vision4robotics/udat)

### Preprints
- **TASST**: Xin Li, Wenjie Pei, Zikun Zhou, Zhenyu He, Huchuan Lu, Ming-Hsuan Yang. Self-Supervised Tracking via Target-Aware Data Synthesis. [[Paper]](https://arxiv.org/pdf/2106.10900v2.pdf) [Code]
