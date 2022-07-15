# Visual-Object-Tracking-Lab304

### CV三大顶会论文分类汇总(2020-Now)(@[52cv](https://github.com/52CV))

### Multi-Object Tracking (MOT)
Here is a collection of outstanding MOT work from top conferences and journals. Some of them (such as SORT, DeepSORT, JDE, etc.) are highly influential in the field and attract much attention. The number of ⭐ in the table represents the level of attention it deserves, of course this is just a personal opinion. Hope it can be useful to you! Details Details are [here](https://github.com/Rongmiq/Visual-Object-Tracking-Lab304-/MOT/README.md)!
#### OVERVIEW (MOT17 test)
The table shows the results on the MOT17 test set and xx* means unofficial results. TBD, JTD, and Siam are short for Tracking-by-Detection, Joint-Detection-and-Tracking, and Siamese Network respectively. M, R, Tr, and G represent Motion information, ReID feature, Transformer, and Graph Neural Network respectively.
|    Method     | Type | Keywords  |                                                                         Ref@ Paper                                                                         |                                                         PageHome                                                         | MOTA ↑ | IDF1 ↑ | HOTA ↑ | IDs ↓ | Stars  |
|:-------------:|:----:|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------:|:------:|:------:|:------:|:-----:|:------|
|     SORT      | TBD  |     M     |                                                        [ICIP2016](https://arxiv.org/abs/1602.00763)                                                        | [Offical](https://github.com/abewley/sort) or [Other](https://github.com/ifzhang/ByteTrack/tree/main/yolox/sort_tracker) |  43.1  |  39.8  |  34.0  | 4852  | ⭐⭐⭐⭐⭐ |
|   DeepSORT    | TBD  |    M+R    |                                                        [ICIP2017](https://arxiv.org/abs/1703.07402)                                                        |                        [Other](https://github.com/ifzhang/ByteTrack/tree/main/yolox/sort_tracker)                        | 78.0*  | 74.5*  | 61.2*  | 1821* | ⭐⭐⭐⭐⭐ |
|    DeepMOT    |  -   |     -     |                                                        [CVPR2020](https://arxiv.org/abs/1906.06618)                                                        |                                  [Offical](https://gitlab.inria.fr/robotlearn/deepmot)                                   |  53.7  |  53.8  |  42.4  | 1,947 | ⭐⭐⭐   |
|   Trackor++   | TBD  |    M+R    |                                                        [ICCV2019](https://arxiv.org/abs/1903.05625)                                                        |                               [Offical](https://github.com/phil-bergmann/tracking_wo_bnw)                                |  56.3  |  55.1  |  44.8  | 1,987 | ⭐⭐⭐   |
|    TubeTK     | JDT  |     M     |                                                      [CVPR2020](https://arxiv.org/pdf/2006.05683.pdf)                                                      |                                     [Offical](https://github.com/BoPang1996/TubeTK)                                      |  63.0  |  58.6  |  48.0  | 4,137 | ⭐⭐    |
|    ArTIST     | TBD  |     M     |                                                        [CVPR2021](https://arxiv.org/abs/2012.02337)                                                        |                                     [Offical](https://github.com/fatemeh-slh/ArTIST)                                     |  62.3  |  59.7  |  48.9  | 2,062 | ⭐⭐    |
|      JDE      | JDT  |    M+R    |                                                        [ECCV2020](https://arxiv.org/abs/1909.12605)                                                        |                               [Offical](https://github.com/Zhongdao/Towards-Realtime-MOT)                                | 63.2*  | 65.0*  |   -    |   -   | ⭐⭐⭐⭐⭐ |
|   CTracker    | TBD  |   Chain   |                                                        [ECCV2020](https://arxiv.org/abs/2007.14557)                                                        |                                      [Offical](https://github.com/pjl1995/CTracker)                                      |  66.6  |  57.4  |  49.0  | 5529  | ⭐⭐⭐   |
|  CenterTrack  | JDT  |     M     |                                                        [ECCV2020](https://arxiv.org/abs/2004.01177)                                                        |                                   [Offical](https://github.com/xingyizhou/CenterTrack)                                   |  67.8  |  64.7  |  52.2  | 3,039 | ⭐⭐⭐⭐  |
|    TraDes     | JDT  |    M+R    |                                                      [CVPR2021](https://arxiv.org/pdf/2103.08808.pdf)                                                      |                                      [Offical](https://github.com/JialianW/TraDeS)                                       |  69.1  |  63.9  |  52.7  | 3555  | ⭐⭐⭐   |
|    CSTrack    | JDT  |    M+R    |                                                      [IEEE TIP2021](https://arxiv.org/abs/2010.12138)                                                      |                                       [Offical](https://github.com/JudasDie/SOTS)                                        |  74.9  |  72.6  |  59.3  | 3567  | ⭐⭐⭐   |
|  TransTrack   | Siam |    Tr     |                                                       [arxiv2021](https://arxiv.org/abs/2012.15460)                                                        |                                    [Offical](https://github.com/PeizeSun/TransTrack)                                     |  75.2  |  63.5  |  54.1  | 3,603 | ⭐⭐⭐   |
|    SOTMOT     | Siam |     -     | [CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Zheng_Improving_Multiple_Object_Tracking_With_Single_Object_Tracking_CVPR_2021_paper.pdf) |                                                            -                                                             |  71.0  |  71.9  |   -    | 5184  | ⭐⭐    |
|  TransCenter  | JDT  |   M+Tr    |                                                       [arxiv2021](https://arxiv.org/abs/2103.15145)                                                        |                                    [Offical](https://github.com/yihongXU/TransCenter)                                    |  73.2  |  62.2  |  54.5  | 4,614 | ⭐⭐    |
|     GSDT      | JDT  |   M+TrG   |                                                        [ICRA2021](https://arxiv.org/abs/2006.13164)                                                        |                                       [Offical](https://github.com/yongxinw/GSDT)                                        |  66.2  |  68.7  |  55.5  | 3,318 | ⭐⭐⭐   |
|  PermaTrack   | JDT  |     M     |                                                      [ICCV2021](https://arxiv.org/pdf/2103.14258.pdf)                                                      |                                     [Offical](https://github.com/TRI-ML/permatrack)                                      |  73.8  |  68.9  |  55.5  | 3,699 | ⭐⭐    |
|    FairMOT    | JDT  |    M+R    |                                                        [IJCV2021](https://arxiv.org/abs/2004.01888)                                                        |                                      [Offical](https://github.com/ifzhang/FairMOT)                                       |  73.7  |  72.3  |  59.3  | 3,303 | ⭐⭐⭐⭐⭐ |
|    SiamMOT    | Siam |     M     |                                 [CVPR2021](https://www.amazon.science/publications/siammot-siamese-multi-object-tracking)                                  |                                  [Offical](https://github.com/amazon-research/siam-mot)                                  |  76.3  |  72.3  |   -    |   -   | ⭐⭐⭐   |
|  CorrTracker  | JDT  |     M     |                                                        [CVPR2021](http://arxiv.org/abs/2104.03541)                                                         |                                                            -                                                             |  76.5  |  73.6  |  60.7  | 3,369 | ⭐⭐    |
| RelationTrack | JDT  |  M+R+Tr   |                                                       [arxiv2021](https://arxiv.org/abs/2105.04322)                                                        |                                    [Offical](https://github.com/Ahnsun/RelationTrack)                                    |  73.8  |  74.7  |  61.0  | 1,374 | ⭐⭐    |
|   TransMOT    | JDT  | M+R+Tr+G  |                                                       [arxiv2021](https://arxiv.org/abs/2104.00194)                                                        |                                                            -                                                             |  76.7  |  75.1  |  61.7  | 2,346 | ⭐⭐    |
|   ByteTrack   | TBD  |     M     |                                                        [ECCV2022](https://arxiv.org/abs/2110.06864)                                                        |                                     [Offical](https://github.com/ifzhang/ByteTrack)                                      |  80.3  |  77.3  |  63.1  | 2,196 | ⭐⭐⭐⭐⭐ |
|    OC_SORT    | TBD  |     M     |                                                       [arxiv2022](https://arxiv.org/abs/2203.14360)                                                        |                                      [Offical](https://github.com/noahcao/OC_SORT)                                       |  78.0  |  77.5  |  63.2  | 2,196 | ⭐⭐⭐⭐  |
| StrongSORT++  | TBD  |    M+R    |                                                       [arxiv2022](https://arxiv.org/abs/2202.13514)                                                        |  [Offical](https://github.com/dyhBUPT/StrongSORT) or [Other](https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet)  |  79.6  |  79.5  |  64.4  | 1,194 | ⭐⭐⭐⭐  |
