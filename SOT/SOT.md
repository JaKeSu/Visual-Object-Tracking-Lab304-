---
title: SOT
created: '2022-07-22T14:08:52.659Z'
modified: '2022-07-22T14:18:45.612Z'
---

# Visual-Object-Tracking-Lab304
## Single-Object Tracking (SOT)
Here is a collection of outstanding SOT work from top conferences and journals. Some of them (such as SiamFC, DiMP, etc.) are highly influential in the field and attract much attention. The number of ⭐ in the table represents the level of attention it deserves, of course this is just a personal opinion. Hope it can be useful to you！

## OVERVIEW 
The table shows some related information about these trackers. Siamese, Transformer and ATOM display main method the tracker using in the Type column.
|Method|Type|Keywords|Ref@Paper|PageHome|Stars|
|:---:|:---:|:---:|:---:|:---:|:---:|
|SiamFC|Siamese|Anchor-based|[ECCV2016](https://arxiv.org/abs/1606.09549)|[Official](https://www.robots.ox.ac.uk/~luca/siamese-fc.html) or [Other( <font color=Red>**Recommended!!**</font>)](https://github.com/huanglianghua/siamfc-pytorch)|:star::star::star::star::star:|
|SiamRPN|Siamese|Anchor-based|[CVPR2018](https://openaccess.thecvf.com/content_cvpr_2018/html/Li_High_Performance_Visual_CVPR_2018_paper.html)|[Official](https://github.com/STVIR/pysot)|:star::star::star::star::star:|
|SiamRPN++|Siamese|Anchor-based|[CVPR2019](https://openaccess.thecvf.com/content_CVPR_2019/html/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.html)|[Official](https://github.com/STVIR/pysot)|:star::star::star::star:|
|SiamCAR|Siamese|Anchor-free|[CVPR2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Guo_SiamCAR_Siamese_Fully_Convolutional_Classification_and_Regression_for_Visual_Tracking_CVPR_2020_paper.html)|[Official](https://github.com/ohhhyeahhh/SiamCAR)|:star::star::star::star:|
|SiamGAT|Siamese|Anchor-free|[CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Guo_Graph_Attention_Tracking_CVPR_2021_paper.html)|[Official](https://github.com/ohhhyeahhh/SiamGAT)|:star::star::star:|
|TransT|Siamese+Transformer|Anchor-based|[CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Transformer_Tracking_CVPR_2021_paper.html)|[Official](https://github.com/chenxin-dlut/TransT)|:star::star::star::star:|
|SiamFC++|Siamese|Anchor-free|[AAAI2020](https://arxiv.org/abs/1911.06188)|[Official](https://github.com/megvii-research/video_analyst)|:star::star::star::star::star:|
|ATOM|ATOM|Anchor-based|[CVPR2019](https://openaccess.thecvf.com/content_CVPR_2019/html/Danelljan_ATOM_Accurate_Tracking_by_Overlap_Maximization_CVPR_2019_paper.html)|[Official](https://github.com/visionml/pytracking)|:star::star::star::star::star:|
|DiMP|ATOM|Anchor-based|[ICCV2019](https://openaccess.thecvf.com/content_ICCV_2019/html/Bhat_Learning_Discriminative_Model_Prediction_for_Tracking_ICCV_2019_paper.html)|[Official](https://github.com/visionml/pytracking)|:star::star::star::star:|
|PrDiMP|ATOM|Anchor-based|[CVPR2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Danelljan_Probabilistic_Regression_for_Visual_Tracking_CVPR_2020_paper.html)|[Official](https://github.com/visionml/pytracking)|:star::star::star:|
|Ocean|ATOM|Anchor-free|[ECCV2020](https://arxiv.org/abs/2006.10721)|[Official](https://github.com/researchmm/TracKit)|:star::star::star::star:|
|ACM|Siamese|Module|[CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Han_Learning_To_Fuse_Asymmetric_Feature_Maps_in_Siamese_Trackers_CVPR_2021_paper.html)|[Official](https://github.com/wencheng256/SiamBAN-ACM)|:star::star::star:|
|SiamBAN|Siamese|anchor-free|[CVPR2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Chen_Siamese_Box_Adaptive_Network_for_Visual_Tracking_CVPR_2020_paper.html)|[Official](https://github.com/hqucv/siamban)|:star::star::star:|
|MeanShift++|Machine Learning|-|[CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Jang_MeanShift_Extremely_Fast_Mode-Seeking_With_Applications_to_Segmentation_and_Object_CVPR_2021_paper.html)|-|:star::star::star:|
|RE-SiamNet|Siamese(Network+Dataset)|-|[CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Gupta_Rotation_Equivariant_Siamese_Networks_for_Tracking_CVPR_2021_paper.html)|[Official](https://github.com/dkgupta90/re-siamnet)|:star::star:|
|DaSiamRPN|Siamese|anchor-based|[ECCV2018](https://openaccess.thecvf.com/content_ECCV_2018/html/Zheng_Zhu_Distractor-aware_Siamese_Networks_ECCV_2018_paper.html)|[Official](https://github.com/foolwood/DaSiamRPN)|:star::star::star:|
|CFNet|Siamese|anchor-based|[CVPR2017](https://openaccess.thecvf.com/content_cvpr_2017/html/Valmadre_End-To-End_Representation_Learning_CVPR_2017_paper.html)|[Official](https://github.com/bertinetto/cfnet)|:star::star::star:|
|CSWinTT|Siamese+Transformer|corner-based|[CVPR2022](https://openaccess.thecvf.com/content/CVPR2022/html/Song_Transformer_Tracking_With_Cyclic_Shifting_Window_Attention_CVPR_2022_paper.html)|[Official](https://github.com/SkyeSong38/CSWinTT)|:star::star::star:|
|STARK|Siamese+Transformer|corner-based|[ICCV2021](https://openaccess.thecvf.com/content/ICCV2021/html/Yan_Learning_Spatio-Temporal_Transformer_for_Visual_Tracking_ICCV_2021_paper.html)|[Official](https://github.com/researchmm/Stark)|:star::star::star::star:|






