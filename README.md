#  A Comprehensive Survey for Multi-Modal Visual Object tracking

<p align="center">
<img src="https://github.com/Zhangyong-Tang/MultiModal-Visual-Object-tracking/blob/main/logo2.png" width="700">
</p>

#### We appreciate any efforts committed to the development of Multi-Modal Visual Object Tracking. Please feel free to connect us (zhangyong_tang_jnu@163.com) for discussion or missed works.


## :collision: Update Log 
* [2024.06.01] All the multi-modal tracking papers are added.
* [2024.05.29] All datasets are listed.
* [2024.05.28] All survey papers and RGBT papers are listed.
* [2023.12.16] The repository is started.

## Our contributions to the MMVOT community
* UniMod1K: Towards a More Universal Large-Scale Dataset and Benchmark for Multi-modal Learning. Xue-Feng Zhu, Tianyang Xu, Zongtao Liu, Zhangyong Tang, Xiao-Jun Wu & Josef Kittler. IJCV 2024. [[Paper](https://link.springer.com/article/10.1007/s11263-024-01999-8)] [[Code](https://github.com/xuefeng-zhu5/UniMod1K)]
* Generative-based Fusion Mechanism for Multi-Modal Tracking. Zhangyong Tang, Tianyang Xu, Xuefeng Zhu, Xiao-Jun Wu*, Josef Kittler. AAAI 2024.  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28325)] [[Code](https://github.com/Zhangyong-Tang/GMMT-AAAI2024)].
* TENet: Targetness Entanglement Incorporating with Multi-Scale Pooling and Mutually-Guided Fusion for RGB-E Object Tracking. Pengcheng Shao, Tianyang Xu, Zhangyong Tang, Linze Li, Xiao-Jun Wu, Josef Kittler. Arxiv 2024. [[Paper](https://arxiv.org/abs/2405.05004)] [[Code](https://github.com/SSSpc333/TENet)].
* Feature enhancement and coarse-to-fine detection for RGB-D tracking. Xue-Feng Zhu, Tianyang Xu, Xiao-Jun Wu, Josef Kittler. PRL 2024. FECD.
* Adaptive Colour-Depth Aware Attention for RGB-D Object Tracking. Xue-Feng Zhu, Tianyang Xu, Xiao-Jun Wu, Zhenhua Feng, Josef Kittler. SPL 2024. CDAAT. [[Paper](https://ieeexplore.ieee.org/abstract/document/10472092)] [[Code](https://github.com/xuefeng-zhu5/CDAAT)].
* Self-supervised learning for RGB-D object tracking. Xue-Feng Zhu, Tianyang Xu, Sara Atito, Muhammad Awais, Xiao-Jun Wu, Zhenhua Feng, Josef Kittler. PR 2024. SSLTrack.
* RGBD1K: A Large-Scale Dataset and Benchmark for RGB-D Object Tracking. Xue-Feng Zhu, Tianyang Xu, Zhangyong Tang, ZuchengWu, Haodong Liu, Xiao Yang, Xiao-Jun Wu, Josef Kittler. AAAI 2023. RGBD1K. [[Paper](https://arxiv.org/abs/2208.09787)] [[Code](https://github.com/xuefeng-zhu5/RGBD1K)].
* Exploring fusion strategies for accurate RGBT visual object tracking. Zhangyong Tang, Tianyang Xu, Hui Li, Xiao-Jun Wu, XueFeng Zhu, Josef Kittler. Information Fusion 2023. DFAT. [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253523001975)]. [[Code](https://github.com/Zhangyong-Tang/DFAT-Information-Fusion2023)].
* Temporal Aggregation for Adaptive RGBT Tracking. Tang, Zhangyong and Xu, Tianyang and Wu, Xiao-Jun. Arxiv 2022. TAAT. [[Paper](https://arxiv.org/abs/2201.08949)] [[Code](https://github.com/Zhangyong-Tang/TAAT)].


## Datasets and Benchmarks

### RGB-Mutli Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| UniMod1K| IJCV'2024 |[UniMod1K](https://github.com/xuefeng-zhu5/UniMod1K) |RGB+D+L: UniMod1K: Towards a More Universal Large-Scale Dataset and Benchmark for Multi-modal Learning|
| WebUAV-3M| TPAMI'2023 | [WebUAV-3M](https://github.com/983632847/WebUAV-3M) | RGB+L+Audio: WebUAV-3M: A Benchmark for Unveiling the Power of Million-Scale Deep UAV Tracking|

### RGBT Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| MV-RGBT| Arxiv'2024 |[MV-RGBT]() |Revisiting RGBT Tracking Benchmarks from the Perspective of Modality Validity: A New Benchmark, Problem, and Method|
| VTUAV| CVPR'2022 |[VTUAV](https://zhang-pengyu.github.io/DUT-VTUAV/) |Visible-Thermal UAV Tracking: A Large-Scale Benchmark and New Baseline|
| LasHeR| TIP'2021 | [LasHeR](https://github.com/BUGPLEASEOUT/LasHeR) |LasHeR: A Large-scale High-diversity Benchmark for RGBT Tracking|
| VOT-RGBT20| VOT Community： 2020 | [VOT-RGBT2020](https://pan.baidu.com/s/1fNgAVk4siqP2p-b1M2ZGmg) *CODE:TZYD*| The Eighth Visual Object Tracking VOT2020 Challenge Results|
| VOT-RGBT19| VOT Community：2019 |[VOT-RGBT2019](https://pan.baidu.com/s/1kYnTTWF9LIkrCH4NNsSlFQ) *CODE:TZYD* | The Seventh Visual Object Tracking VOT2019 Challenge Results|
| RGBT234| PR'2018 | [RGBT234](https://sites.google.com/view/ahutracking001/)|RGB-T object tracking: Benchmark and baseline|
| RGBT210| ACM MM'2017 | [RGBT210](https://drive.google.com/file/d/0B3i2rdXLNbdUTkhsLVRwcTBTMlU/view?resourcekey=0-vytg_w3hqlQfLhoiS2J8Dg) |Weighted Sparse Representation Regularized Graph Learning for RGB-T Object Tracking|
| GTOT | TIP'2016 | [GTOT](https://pan.baidu.com/s/1QNidEo-HepRaS6OIZr7-Cw) |Learning Collaborative Sparse Representation for Grayscale-Thermal Tracking|
| LITIV | CVIU'2012 | [LITIV](https://www.polymtl.ca/litiv/en/codes-and-datasets) |An iterative integrated framework for thermal–visible image registration, sensor fusion, and people tracking for video surveillance applications|
| OTCBVS | CVIU'2007 | [OTCBVS](http://vcipl-okstate.org/pbvs/bench/) |Background-subtraction using contour-based fusionof thermal and visible imagery|
| LSS-Dataset(from RGB) | TCSVT'2021 | [LSS-Dataset](https://pan.baidu.com/s/1x2hiqb2lSo54_4CI_L9YeQhttps://pan.baidu.com/s/1x2hiqb2lSo54_4CI_L9YeQ) ,code(Ye5Q)|SiamCDA: Complementarity-and distractor-aware RGB-T tracking based on Siamese network|
| LSS-Dataset(from TIR) | TCSVT'2021 | [LSS-Dataset](https://pan.baidu.com/s/1xD3Ox-9VbZnyRQSWOxQRNw),code(IHws) |SiamCDA: Complementarity-and distractor-aware RGB-T tracking based on Siamese network|


### RGBD Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| D2CUBE| CVRP'2023|[D2CUBE](https://github.com/yjybuaa/RGBDAerialTracking)|Resource-Efficient RGBD Aerial Tracking|
| ARKittrack| CVPR'2023 | [ARKittrack](https://github.com/lawrence-cj/ARKitTrack) |ARKitTrack: A New Diverse Dataset for Tracking Using Mobile RGB-D Data|
| RGBD1K | AAAI'2023 | [RGBD1K](https://github.com/xuefeng-zhu5/RGBD1K) |RGBD1K: A Large-Scale Dataset and Benchmark for RGB-D Object Tracking|
| DepthTrack | ICCV'2021 | [DepthTrack](https://github.com/xiaozai/DeT) |DepthTrack: Unveiling the Power of RGBD Tracking|
| CDTB | ICCV'2019 | [CDTB](https://www.votchallenge.net/vot2019/dataset.html) |CDTB: A Color and Depth Visual Object Tracking Dataset and Benchmark|
| STC | ICCV'2019 | [STC](https://pan.baidu.com/s/1Y3z2JH-oR68-stWFVnHUVw) code:TZYD|Robust Fusion of Color and Depth Data for RGB-D Target Tracking Using Adaptive Range-Invariant Depth Models and Spatio-Temporal Consistency Constraints|
| PTB | ICCV'2013 | [PTB](https://tracking.cs.princeton.edu/index.html) |Tracking Revisited using RGBD Camera: Unified Benchmark and Baselines|


### RGBE Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| CRSOT| Arxiv'2024 |[CRSOT](https://github.com/Event-AHU/Cross_Resolution_SOT) |CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras|
| FELT| Arxiv'2024 |[FELT](https://github.com/Event-AHU/FELT_SOT_Benchmark) |Long-term Frame-Event Visual Tracking: Benchmark Dataset and Baseline|
| COESOT| Arxiv'2022 | [COESOT](https://github.com/Event-AHU/COESOT)|Revisiting Color-Event based Tracking: A Unified Network, Dataset, and Metric|
| VisEvent| TCYB'2023 |[VisEvent](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark?tab=readme-ov-file)|VisEvent: Reliable Object Tracking via Collaboration of Frame and Event Flows|
| FE108/FE240hz| ICCV'2021 | [FE108/FE240hz](https://github.com/Jee-King/ICCV2021_Event_Frame_Tracking)|Object Tracking by Jointly Exploiting Frame and Event Domain|



### RGBL Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| WebUOT-1M| Arxiv'2024 |[WebUOT-1M](https://github.com/983632847/Awesome-Multimodal-Object-Tracking) |WebUOT-1M: Advancing Deep Underwater Object Tracking with A Million-Scale Benchmark|
| VastTrack| Arxiv'2024 |[VastTrack](https://github.com/HengLan/VastTrack) |VastTrack: Vast Category Visual Object Tracking|
| MGIT| NIPS'2023 |[MGIT](http://videocube.aitestunion.com/) |A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Causal Relationship|
| TNL2K| CVPR'2021 | [TNL2K](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)|Towards More Flexible and Accurate Object Tracking with Natural Language: Algorithms and Benchmark|
| LaSOT_EXT| IJCV'2021 |[LaSOT_EXT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|LaSOT: A High-quality Large-scale Single Object Tracking Benchmark|
| LaSOT| CVPR'2019 | [LaSOT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking|
| OTB99-L| CVPR'2017 | [OTB99-L](https://github.com/QUVA-Lab/lang-tracker) |Tracking by Natural Language Specification|


### RGBNIR Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| CMOTB| TNNLS'2024 |[CMOTB](https://github.com/mmic-lcl/Datasets-and-benchmark-code) |Cross-Modal Object Tracking via Modality-Aware Fusion Network and A Large-Scale Dataset|




## Surveys and Report
* RGBT ---- RGBT tracking: A comprehensive review. Mingzheng Feng, Jianbo Su*. Information Fusion 2024. [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253524002707)]
* RGBT ---- Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective. Zhihao Zhang, Jun Wang, Zhuli Zang, Lei Jin, Shengjie Li, Hao Wu*,Jian Zhao, Zhang Bo. ACM TOMM 2024. [[Paper](https://dl.acm.org/doi/10.1145/3651308)]
* RGBT---- Object fusion tracking based on visible and infrared images: A comprehensive review. Xingchen Zhang, Ping Ye, Henry Leung, Ke Gong, Gang Xiao*. Information Fusion 2020. [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253520302657)]
* RGBT---- A Survey for Deep RGBT Tracking. Zhangyong Tang, Tianyang Xu, and Xiao-Jun Wu*. Arxiv 2022. [[Paper](https://arxiv.org/abs/2201.09296)]
* RGBD---- A Survey of RGB-Depth Object Tracking. Zhou Ou, Ge Ying, Dawei Zhang*, Zhonglong Zheng. Journal of Computer-Aided Design & Computer Graphics 2024. [[Paper](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.null.2023-00537)]
* RGBD---- Rgbd object tracking: An in-depth review. Jinyu Yang, Zhe Li, Song Yan, Feng Zheng*, Aleš Leonardis, Joni-Kristian Kämäräinen, Ling Shao. Arxiv 2022. [[Paper](https://arxiv.org/abs/2203.14134)]
* RGBD/T ---- Multi-modal visual tracking: Review and experimental comparison. Zhang, Pengyu, Dong Wang*, and Huchuan Lu. Computational Visual Media 2024. [[Paper](https://link.springer.com/article/10.1007/s41095-023-0345-5)]
* RGBD/T/E/L ---- Awesome Multi-modal Object Tracking (MMOT). Chunhui Zhang, Li Liu, Hao Wen, Xi Zhou, Yanfeng Wang. Arxiv 2024. [[Paper](https://github.com/983632847/Awesome-Multimodal-Object-Tracking?tab=readme-ov-file#datasets)]




## Regular Papers 

### Unified (Model or Architecture for) Multi-Modal Tracking

* Towards a Generalist and Blind RGB-X Tracker. Yuedong Tan, Zongwei Wu, Yuqian Fu, Zhuyun Zhou, Guolei Sun, Chao Ma, Danda Pani Paudel, Luc Van Gool, Radu Timofte. Arxiv 2024. XTrack.
* Unified Sequence-to-Sequence Learning for Single- and Multi-Modal Visual Object Tracking. Xin Chen, Ben Kang, Jiawen Zhu, Dong Wang*, Houwen Peng, and Huchuan Lu. Arxiv 2024. [[Paper](https://arxiv.org/pdf/2304.14394)] [[Code](https://github.com/chenxin-dlut/SeqTrackv2)] 
* SDSTrack: Self-Distillation Symmetric Adapter Learning for Multi-Modal Visual Object Tracking. Xiaojun Hou, Jiazheng Xing, Yijie Qian, Yaowei Guo, Shuo Xin, Junhao Chen,
Kai Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu*, Yong Liu*. CVPR 2024. [[Paper](https://arxiv.org/pdf/2403.16002)] [[Code](https://github.com/hoqolo/SDSTrack)]
* Single-Model and Any-Modality for Video Object Tracking. Zongwei Wu, Jilai Zheng, Xiangxuan Ren, Florin-Alexandru Vasluianu, Chao Ma*, Danda Pani Paudel, Luc Van Gool, Radu Timofte. CVPR 2024. [[Paper](https://arxiv.org/abs/2311.15851)] [[Code](https://github.com/Zongwei97/UnTrack)]
* OneTracker: Unifying Visual Object Tracking with Foundation Models and Efficient Tuning. Lingyi Hong, Shilin Yan, Renrui Zhang, Wanyun Li, Xinyu Zhou, Pinxue Guo, Kaixun Jiang, Yiting Chen, Jinglun Li, Zhaoyu Chen, Wenqiang Zhang*. CVPR 2024. [[Paper](https://arxiv.org/pdf/2403.09634)]
* Knowledge Synergy Learning for Multi-Modal Tracking. He, Yuhang and Ma, Zhiheng and Wei, Xing and Gong, Yihong. TCSVT 2024. KSTrack.
* MINet: Modality interaction network for unified multi-modal tracking. Shuang Gong, Zhu Teng1*, Rui Li, Jack Fan, Baopeng Zhang, Jianping Fan. IVC 2024. [[Paper](https://www.sciencedirect.com/science/article/pii/S0262885624001756)]
* Visual Prompt Multi-Modal Tracking. Jiawen Zhu, Simiao Lai, Xin Chen, Dong Wang*, Huchuan Lu. CVPR 2023.  [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_Visual_Prompt_Multi-Modal_Tracking_CVPR_2023_paper.pdf)] [[Code](https://github.com/jiawen-zhu/ViPT)]
* Feature Disentanglement and Adaptive Fusion for Improving Multi-modal Tracking. Zheng Li, Weibo Cai, Junhao Dong, Jianhuang Lai, and Xiaohua Xie. PRCV 2023.
* Prompting for multi-modal tracking. Yang, Jinyu and Li, Zhe and Zheng, Feng and Leonardis, Ales and Song, Jingkuan. ACM MM 2022. ProTrack

### RGB-T Tracking
2024

* AFter: Attention-based Fusion Router for RGBT Tracking. Andong Lu, Wanyu Wang, Chenglong Li, Jin Tang, Bin Luo. Arxiv 2024. AFter.
* A content-aware correlation filter with multi-feature fusion for RGB-T tracking. FENG Zihang, YAN Liping*, BAI Jinglan, XIA Yuanqing, and XIAO Bo. Journal of Systems Engineering and Electronics 2024. [[Paper](https://ieeexplore.ieee.org/abstract/document/10530492)]
* AMNet: Learning to Align Multi-modality for RGB-T Tracking. Zhang Tianlu, He Xiaoyi, Jiao Qiang, Zhang Qiang, Han Jungong. TCSVT 2024. AMNet.
* Bi-directional Adapter for Multi-modal Tracking. Bing Cao, Junliang Guo, Pengfei Zhu, Qinghua Hu. AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27852)] [[Code](https://github.com/SparkTempest/BAT)].
* Cross-Modal Object Tracking: Modality-Aware Representations and A Unified Benchmark. Chenglong Li, Tianhao Zhu, Lei Liu, Xiaonan Si, Zilin Fan, Sulan Zhai. Arxiv 2024. MArMOT.
* From Two Stream to One Stream: Efficient RGB-T Tracking via Mutual Prompt Learning and Knowledge Distillation. Luo, Yang, Xiqing Guo, and Hao Li. Arxiv 2024.
* Generative-based Fusion Mechanism for Multi-Modal Tracking. Zhangyong Tang, Tianyang Xu, Xuefeng Zhu, Xiao-Jun Wu*, Josef Kittler. AAAI 2024.  [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28325)] [[Code](https://github.com/Zhangyong-Tang/GMMT-AAAI2024)].
* Learning Multi-Frequency Integration Network for RGBT Tracking. Jiatian Mei, Juxiang Zhou, Jun Wang, Jia Hao, Dongming Zhou, and Jinde Cao. IEEE Sensor Journal 2024. LMINet
* Learning Multi-Layer Attention Aggregation Siamese Network for Robust RGBT Tracking. Mingzheng Feng and Jianbo Su. TMM 2024. SiamMLAA
* Modality-missing RGBT Tracking: Invertible Prompt Learning and High-quality Benchmarks. Andong Lu, Jiacong Zhao, Chenglong Li, Jin Tang, Bin Luo. Arxiv 2024. IPL
* Maximize Peak-to-Sidelobe Ratio for Real-Time RGB-T Tracking. Xu Zhu, Jun Liu, Xingzhong Xiong, and Zhongqiang Luo. TIM 2024. MPT
* QueryTrack: Joint-Modality Query Fusion Network for RGBT Tracking. Fan, Huijie and Yu, Zhencheng and Wang, Qiang and Fan, Baojie and Tang, Yandong. TIP 2024. [[Paper](https://ieeexplore.ieee.org/abstract/document/10516307)]
* Revisiting RGBT Tracking Benchmarks from the Perspective of Modality Validity: A New Benchmark, Problem, and Method. Zhangyong Tang, Tianyang Xu, Zhenhua Feng, Xuefeng Zhu, He Wang, Pengcheng Shao, Chunyang Cheng, Xiao-Jun Wu∗, Muhammad Awais, Sara Atito, and Josef Kittler. Arxiv 2024. MV-RGBT
* RGBT Tracking via Challenge-Based Appearance Disentanglement and Interaction.  Liu, Lei and Li, Chenglong and Xiao, Yun and Ruan, Rui and Fan, Minghao. TIP 2024. CAT++.
* RGBT Tracking via Progressive Fusion Transformer with Dynamically Guided Learning. Yabin Zhu, Chenglong Li, Xiao Wang, Jin Tang, Zhixiang Huang. TCSVT 2024. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10506555)].
* Robust RGB-T Tracking via Adaptive Modality Weight Correlation Filters and Cross-modality Learning. Mingliang Zhou, Xinwen Zhao, Futing Luo, Jun Luo, Huayan Pu, Tao Xiang. ACM TOMM 2024. AWCM
* Temporal Adaptive RGBT Tracking with Modality Prompt. Hongyu Wang, Xiaotao Liu*, Yifan Li, Meng Sun, Dian Yuan, Jing Liu. AAAI 2024. [[Paper](https://arxiv.org/abs/2401.01244)].
* Towards Modalities Correlation for RGB-T Tracking. Hu Xiantao, Zhong Bineng, Liang Qihua, Zhang Shengping, Li Ning, Li Xianxian. TCSVT 2024. MCTrack.
* Transformer-based RGB-T Tracking with Channel and Spatial Feature Fusion. Yunfeng Li, Bo Wang, Ye Li, Zhiwen Yu, Liang Wang. Arxiv 2024. CSTNet.


2023

* Anchor free based Siamese network tracker with transformer for RGB‑T tracking. Liangsong Fan, Pyeoungkee Kim. Scientific Reports 2023. SiamAFTS
* An RGB-T Object Tracking Method for Solving Camera Motion Based on Correlation Filter. Zhongxuan Zhao, Weixing Li, Feng Pan. CCDC 2023. PRO
* Bayesian Dumbbell Diffusion Model for RGBT Object Tracking With Enriched Priors. Fan, Shenghua and He, Chu and Wei, Chenxia and Zheng, Yujin and Chen, Xi. SPL 2023. BD2Track
* Bridging Search Region Interaction with Template for RGB-T Tracking. Hui Tianrui, Xun Zizheng, Peng Fengguang, Huang Junshi, Wei Xiaoming, Wei Xiaolin, Dai Jiao, Han Jizhong, Liu Si. CVPR 2023. TBSI
* Dynamic Fusion Network for RGBT Tracking. Jingchao Peng , Haitao Zhao , and Zhengwei Hu. TITS 2023. DFMet.
* Deep Triply Attention Network for RGBT Tracking. Rui Yang, Xiao Wang, Yabin Zhu, Jin Tang. Cognitive Computation 2023.
* Differential Enhancement and Commonality Fusion for RGBT Tracking. Yang, Jianrong and Dong, Enzeng and Tong, Jigang and Yang, Sen and Zhang, Zufeng and Li, Wenyu. ICMA 2023. DECFNet
* Drone Based RGBT Tracking with Dual-Feature Aggregation Network. Zhinan Gao, Dongdong Li, Gongjian Wen, Yangliu Kuai, Rui Chen. Drones 2023.
* Dual-Modality Space-Time Memory Network for RGBT Tracking. Fan Zhang, Hanwei Peng, Lingli Yu, Yuqian Zhao, Baifan Chen. TIM 2023. DMSTM
* Dynamic Tracking Aggregation with Transformers for RGB-T Tracking. X Liu, Z Lei. Journal of Information Processing Systems 2023.
* Efficient RGB-T Tracking via Cross-Modality Distillation. Zhang Tianlu, Guo Hongyuan, Jiao Qiang, Zhang Qiang, Han Jungong. CVPR 2023. CMD.
* Exploring fusion strategies for accurate RGBT visual object tracking. Zhangyong Tang, Tianyang Xu, Hui Li, Xiao-Jun Wu, XueFeng Zhu, Josef Kittler. Information Fusion 2023. DFAT
* Exploring the potential of Siamese network for RGBT object tracking. Liangliang Feng, Kechen Song, Junyi Wang, Yunhui Yan. JVCIR 2023. SIamFEA
* HATFNet: Hierarchical adaptive trident fusion network for RGBT tracking. Yanjie Zhao, Huicheng Lai & Guxue Gao. Applied Intelligence 2023. HATFNet
* Learning Modality Complementary Features with Mixed Attention Mechanism for RGB-T Tracking. Yang Luo, Xiqing Guo, Mingtao Dong, Jin Yu. Sensors 2023. MACFT
* Learning cross-modal interaction for RGB-T tracking. Chunyan XU, Zhen CUI*, Chaoqun WANG, Chuanwei ZHOU & Jian YANG. SCIENCE CHINA Information Sciences 2023.
* Learning modality feature fusion via transformer for RGBT-tracking. Yujue Cai, Xiubao Sui, Guohua Gu, Qian Chen. IPT 2023. MMMPT
* Multiple frequency–spatial network for RGBT tracking in the presence of motion blur. Shenghua Fan, Xi Chen, Chu He, Lei Yu, Zhongjie Mao, Yujin Zheng. Neural Computing and Applications 2023.
* MTNet: Learning Modality-aware Representation with Transformer for RGBT Tracking. Ruichao Hou, Boyue Xu, Tongwei Ren, Gangshan Wu. ICME 2023. MTNet.
* Multi-Modal Fusion Object Tracking Based on Fully Convolutional Siamese Network. Ke Qi, Liji Chen, Yicong Zhou, Yutao Qi. CACML 2023. SiamMFF.
* Online Learning Samples and Adaptive Recovery for Robust RGB-T Tracking. Jun Liu, Zhongqiang Luo, Xingzhong Xiong. TCSVT 2023. LSAR.
* Object Fusion Tracking for RGB-T Images via Channel Swapping and Modal Mutual Attention. Luan, Tian and Zhang, Hui and Li, Jiafeng and Zhang, Jing and Zhuo, Li. IEEE Sensors Journal 2023.
* Quality-Aware RGBT Tracking via Supervised Reliability Learning and Weighted Residual Guidance. Lei Liu, Chenglong Li, Yun Xiao, Jin Tang. ACM MM 2023. QAT.
* ROBUST RGB-T TRACKING VIA CONSISTENCY REGULATED SCENE PERCEPTION. Bin Kang, Liwei Liu, Shihao Zhao, Songlin Du. ICIP 2023.
* RGB-T object tracking via sparse response-consistency discriminative correlation filters. Yueping Huang, Xiaofeng Li, Ruitao Lu, Naixin Qi. IPT 2023. SRCDCF
* RGB-T Tracking via Multi-Modal Mutual Prompt Learning. Yang Luo, Xiqing Guo, Hui Feng, Lei Ao. Arxiv 2023. MPLT.
* Region Selective Fusion Network for Robust RGB-T Tracking. Yu, Zhencheng and Fan, Huijie and Wang, Qiang and Li, Ziwan and Tang, Yandong. SPL 2023. RSFNet
* Robust RGB-T Tracking via Graph Attention-Based Bilinear Pooling. Bin Kang, Dong Liang, Junxi Mei, Xiaoyang Tan, Quan Zhou, Dengyin Zhang. TNNLS 2023.
* RGBT tracking based on prior least absolute shrinkage and selection operator and quality aware fusion of deep and handcrafted features. Seyed Morteza Ghazali, Yasser Baleghi. KBS 2023. PLASSO-ADSPF
* RGBT tracking based on modality feature enhancement. Sulan Zhai, Yi Wu1, Lei Liu, Jin Tang. Multimedia Tools and Applications 2023.
* RMFNet: Redetection Multimodal Fusion Network for RGBT Tracking. Yanjie Zhao, Huicheng Lai, and Guxue Gao. Applied Sciences 2023. RMFNet
* RGBT Tracking via Multi-stage Matching Guidance and Context integration. Kaixiang Yan, Changcheng Wang, Dongming Zhou, Ziwei Zhou. Neural Processing Letters 2023. M2GCI
* Siamese infrared and visible light fusion network for RGB-T tracking. Jingchao Peng, Haitao Zhao, Zhengwei Hu, Yi Zhuang, Bofan Wang. Journal of Machine Learning and Cybernetics 2023. SiamIVFN
* SiamTDR: Time-Efficient RGBT Tracking via Disentangled Representations. Guorui Wang , Qian Jiang , Xin Jin , Member, IEEE, Yu Lin, Yuanyu Wang , and Wei Zhou. TICPS 2023. SiamTDR
* Siamese transformer RGBT tracking. Futian Wang, Wenqi Wang, Lei Liu, Chenglong Li & Jing Tang. Applied Intelligence 2023.
* Semantic-guided fusion for multiple object tracking and RGB-Ttracking. Xiaohu Liu, Yichuang Luo, Yan Zhang, Zhiyong Lei. IET Image Processing 2023. SGF-MDNet+RGBT
* SiamCAF: Complementary Attention Fusion-Based Siamese Network for RGBT Tracking. Yingjian Xue, Jianwei Zhang, Zhoujin Lin, Chenglong Li, Bihan Huo, and Yan Zhang. Remote Sensing 2023. SiamCAF
* TEFNet: Target-Aware Enhanced Fusion Network for RGB-T Tracking. Panfeng Chen, Shengrong Gong, Wenhao Ying, Xin Du & Shan Zhong. PRCV 2023. TEFNet.
* Thermal infrared and visible sequences tracking via dual adversarial pixel fusion. Hang Zheng, Nangezi Yuan, Hongwei Ding, Peng Hu & Zhijun Yang. Multimedia Tools and Applications 2023. 
* Unsupervised RGB-T object tracking with attentional multi-modal feature fusion. Shenglan Li, Rui Yao, Yong Zhou, Hancheng Zhu, Bing Liu, Jiaqi Zhao & Zhiwen Shao.  Multimedia Tools and Applications  2023. UDT-FF
* Unified Single-Stage Transformer Network for Efficient RGB-T Tracking. Jianqiang Xia, DianXi Shi, Ke Song, Linna Song, XiaoLei Wang, Songchang Jin, Li Zhou, Yu Cheng, Lei Jin, Zheng Zhu, Jianan Li, Gang Wang, Junliang Xing, Jian Zhao. Arxiv 2023. USTrack
* Visible–Infrared Dual-Sensor Fusion for Single-Object Tracking. Weichun Liu , Weibing Liu, and Yuxin Sun.  IEEE SENSORS JOURNAL 2023. CSRDCF_RGBT


2022

* Asymmetric Global–Local Mutual Integration Network for RGBT Tracking. Mei Jiatian, Liu Yanyu, Wang Changcheng, Zhou Dongming, Nie Rencan, Cao Jinde. TIM 2022. AGMINet.
* Attribute-Based Progressive Fusion Network for RGBT Tracking. Yun Xiao, Mengmeng Yang, Chenglong Li, Lei Liu, Jin Tang. AAAI 2022. APFNet
* Correlation Filters Based on Strong Spatio-Temporal for Robust RGB-T Tracking. Futing Luo, Mingliang Zhou, and Bing Fang. Journal of Circuits, Systems and Computers 2022.
* CMC2R: Cross-modal collaborative contextual representation for RGBT tracking. Xiaohu Liu, Yichuang Luo, Keding Yan, Jianfei Chen, Zhiyong Lei. IET Image Processing 2022. CMC2R
* Duality-Gated Mutual Condition Network for RGBT Tracking. Lu Andong, Qian Cun, Li Chenglong, Tang Jin, Wang Liang. TNNLS 2022. DMCNet.
* Dual Siamese network for RGBT tracking via fusing predicted position maps. Chang Guo, Dedong Yang, Chang Li, Peng Song. The Visual Computer 2022. DuSIamRT
* HIGH SPEED AND ROBUST RGB-THERMAL TRACKING VIA DUAL ATTENTIVE STREAM SIAMESE NETWORK. Guo Chaoyang, Xiao Liang. IGARSS 2022. DASN
* Learning reliable modal weight with transformer for robust RGBT tracking. Mingzheng Feng, Jianbo Su. KBS 2022.
* MIRNET: A ROBUST RGBT TRACKING JOINTLY WITH MULTI-MODAL INTERACTION AND REFINEMENT. Ruichao Hou, Tongwei Ren , Gangshan Wu. ICME 2022. MIRNet
* Multibranch Adaptive Fusion Network for RGBT Tracking. Li Yadong, Lai Huicheng, Wang Liejun, Jia Zhenhong. IEEE Sensors Journal 2022. MBAFNet.
* MFGNet: Dynamic Modality-Aware Filter Generation for RGB-T Tracking. Xiao Wang, Xiujun Shu, Shiliang Zhang, Bo Jiang, Yaowei Wang, Yonghong Tian, Feng Wu. TMM 2022. MFGNet.
* RGBT tracking via reliable feature configuration. Zhengzheng Tu, Wenli Pan, Yunsheng Duan, Jin Tang & Chenglong Li.  Science China Information Sciences 2022.
* RGB-T long-term tracking algorithm via local sampling and global proposals. Liu Jun, Luo Zhongqiang, Xiong Xingzhong. Signal, Image and Video Processing 2022. CF-LG
* RGB-T tracking by modality difference reduction and feature re-selection. Qiang Zhang, Xueru Liu, Tianlu Zhang. IVC 2022. MFNet
* RGBT Tracking by Trident Fusion Network. Zhu Yabin and Li, Chenglong and Tang, Jin and Luo, Bin and Wang, Liang. TCSVT 2022. TFNet.
* Residual learning-based two-stream network for RGB-T object tracking. Yili Chen, Minjie Wan, Yunkai Xu, Xiaojie Zhang, Qian Chen, Guohua Gu. JEI 2022. RLTN
* SCA-MMA: Spatial and Channel-Aware Multi-Modal Adaptation for Robust RGB-T Object Tracking. Run Shi, Chaoqun Wang, Gang Zhao, Chunyan Xu. ELECTRONICS 2022. SCA-MMA
* SiamMMF: multi-modal multi-level fusion object tracking based on Siamese networks. Zhen Yang, Peng Huang, Dunyun He, Zhongwang Cai & Zhijian Yin. Machine Vision and Applications 2022. SiamMMF
* Temporal Aggregation for Adaptive RGBT Tracking. Tang, Zhangyong and Xu, Tianyang and Wu, Xiao-Jun. Arxiv 2022. TAAT
* Visible-Thermal UAV Tracking: A Large-Scale Benchmark and New Baseline. Pengyu Zhang, Jie Zhao, Dong Wang, Huchuan Lu, Xiang Ruan. CVPR 2022. HMFT.


2021

* Adaptive Fusion CNN Features for RGBT Object Tracking. Wang, Yong and Wei, Xian and Tang, Xuan and Shen, Hao and Zhang, Huanlong. TITS 2021.
* Channel Exchanging for RGB-T Tracking. Long Zhao, Meng Zhu, Honge Ren,  Lingjixuan Xue. Sensors 2021. CEDiMP
* Enhanced Real-Time RGB-T Tracking by Complementary Learners. Qingyu Xu, Yangliu Kuai, Junggang Yang, and Xinpu Deng. Journal of Circuits, Systems and Computers 2021. EStaple
* HDINet: Hierarchical Dual-Sensor Interaction Network for RGBT Tracking. Mei, Jiatian and Zhou, Dongming and Cao, Jinde and Nie, Rencan and Guo, Yanbu. IEEE Sensors Journal 2021. HDINet
* Jointly Modeling Motion and Appearance Cues for Robust RGB-T Tracking. Zhang, Pengyu and Zhao, Jie and Bo, Chunjuan and Wang, Dong and Lu, Huchuan and Yang, Xiaoyun. TIP 2021. JMMAC.
* LasHeR: A Large-scale High-diversity Benchmark for RGBT Tracking. Chenglong Li, Wanlin Xue, Yaqing Jia, Zhichen Qu, Bin Luo, Jin Tang, and Dengdi Sun. TIP 2021. LasHeR
* Learning Adaptive Attribute-Driven Representation for Real-Time RGB-T Tracking. Pengyu Zhang, Dong Wang, Huchuan Lu, Xiaoyun Yang. IJCV 2021. ADRNet.
* Learning a Twofold Siamese Network for RGB-T Object Tracking. Yangliu Kuai, Dongdong Li, and Que Qian. Journal of Circuits, Systems and Computers 2021. 
* M5L: Multi-Modal Multi-Margin Metric Learning for RGBT Tracking. Zhengzheng Tu, Chun Lin, Chenglong Li, Jin Tang, Bin Luo. TIP 2021. M5L
* Multimodal Cross-Layer Bilinear Pooling for RGBT Tracking. Qin Xu, Yiming Mei, Jinpei Liu, and Chenglong Li. TMM 2021. CBPNet
* RGBT Tracking via Multi-Adapter Network with Hierarchical Divergence Loss. Andong Lu, Chenglong Li, Yuqing Yan, Jin Tang, Bin Luo. TIP 2021. MANet++
* RGBT Tracking via Noise-Robust Cross-Modal Ranking. Li, Chenglong and Xiang, Zhiqiang and Tang, Jin and Luo, Bin and Wang, Futian. TNNLS 2021. CMR
* RGBT tracking via cross-modality message passing. Rui Yang, Xiao Wang, Chenglong Li, Jinmin Hu, Jin Tang. Neurocomputing 2021. GCMP
* SiamCDA: Complementarity-and distractor-aware RGB-T tracking based on Siamese network. Zhang, Tianlu and Liu, Xueru and Zhang, Qiang and Han, Jungong. TCSVT 2021. SiamCDA.
* WF_DiMP: weight-aware dual-modal feature aggregation mechanism for RGB-T tracking. Zhaodi Wang, Yan Ding, Pingping Wu, Jinbo Zhang. SEVENTH SYMPOSIUM ON NOVEL PHOTOELECTRONIC DETECTION TECHNOLOGY AND APPLICATIONS 2021. WF_DiMP


2020

* Cross-Modal Pattern-Propagation for RGB-T Tracking. Chaoqun Wang, Chunyan Xu, Zhen Cui, Ling Zhou, Tong Zhang, Xiaoya Zhang, Jian Yang. CVPR 2020. CMPP
* Challenge-Aware RGBT Tracking. Chenglong Li, Lei Liu, Andong Lu, Qing Ji, Jin Tang. ECCV 2020. CAT
* DSiamMFT: An RGB-T fusion tracking method via dynamic Siamese networks using multi-layer feature fusion. Xingchen Zhang, Ping Ye, Shengyun Peng, Jun Liu, Gang Xiao. Signal Processing: Image Communication 2020. DSiamMFT
* FANet: Quality-Aware Feature Aggregation Network for Robust RGB-T Tracking. Yabin Zhu, Chenglong Li, Bin Luo, Jin Tang. TIV 2020. FANet
* Learning discriminative update adaptive spatial-temporal regularized correlation filter for RGB-T tracking. Mingzheng Feng, Kechen Song, Yanyan Wang, Jie Liu, Yunhui Yan. Journal of Visual Communication and Image Representation 2020.
* Object Tracking in RGB-T Videos Using Modal-Aware Attention Network and Competitive Learning. Hui Zhang, Lei Zhang, Li Zhuo, Jing Zhang. Sensors 2020. MacNet
* RGB-T Tracking via Multi-expert Correlation Filters using Spatial-temporal Robustness. Zhang, Fei and Ma, Shiping and Li, Zhijun and Zhang, Yule. ICMCCE 2020. MECF
* Robust RGB-T tracking via Bimodal Constrained Correlation Filtering. Li, Xin and Cai, Jun and Ding, Wan and Fang, Zhi. PIC 2020. 

2019

* Dense Feature Aggregation and Pruning for RGBT Tracking. Yabin Zhu, Chenglong Li, Bin Luo, Jin Tang, Xiao Wang. ACM MM 2019. DAPNet.
* Deep Adaptive Fusion Network for High Performance RGBT Tracking. Yuan Gao, Chenglong Li, Yabin Zhu, Jin Tang, Tao He, Futian Wang. ICCVW 2019. DAFNet
* Fast RGB-T Tracking via Cross- Modal Correlation Filters. Sulan Zhai, Pengpeng Shao*, Xinyan Liang, Xin Wang. Neurocomputing 2019
* Learning Local-Global Multi-Graph Descriptors for RGB-T Object Tracking. Chenglong Li, Chengli Zhu, Jian Zhang, Bin Luo, Xiaohao Wu, and Jin Tang. TCSVT 2019. LGMG
* Learning Target-oriented Dual Attention for Robust RGB-T Tracking. Rui Yang, Yabin Zhu, Xiao Wang, Chenglong Li, Jin Tang. Arxiv 2019.
* Multi-Modal Fusion for End-to-End RGB-T Tracking. Lichao Zhang, Martin Danelljan, Abel Gonzalez-Garcia, Joost van de Weijer, Fahad Shahbaz Khan. ICCVW 2019. mfDiMP
* Multi-Adapter RGBT Tracking. Chenglong Li, Andong Lu, Aihua Zheng, Zhengzheng Tu, Jin Tang. ICCVW 2019. MANet
* RGB-T object tracking: Benchmark and baseline. Chenglong Li, Xinyan Liang, Yijuan Lu, Nan Zhao, Jin Tang. PR 2019. RGBT234
* SiamFT: An RGB-Infrared Fusion Tracking Method via Fully Convolutional Siamese Networks. XINGCHEN ZHANG, PING YE, SHENGYUN PENG, JUN LIU, KE GONG1, GANG XIAO. IEEE Access 2019. SiamFT
* Thermal infrared and visible sequences fusion tracking based on a hybrid tracking framework with adaptive weighting scheme. Chengwei Luoa, Bin Suna, Ke Yanga, Taoran Lua, Wei-Chang Yeh. IPT 2019.

2018

* Cross-Modal Ranking with Soft Consistency and Noisy Labels for Robust RGB-T Tracking. Chenglong Li, Chengli Zhu, Yan Huang, Jin Tang, Liang Wang. ECCV 2018. 
* Fusing two-stream convolutional neural networks for RGB-T object tracking. Chenglong Li, Xiaohao Wu, Nan Zhao, Xiaochun Cao, Jin Tang∗. Neurocomputing 2018. fusionnet
* Learning Soft-Consistent Correlation Filters for RGB-T Object Tracking. Yulong Wang, Chenglong Li & Jin Tang. SCCF
* Learning Multi-domain Convolutional Network for RGB-T Visual Tracking. Xingming Zhang, Xuehan Zhang, Xuedan Du, Xiangming Zhou, Jun Yin. 
* Robust Collaborative Discriminative Learning for RGB-Infrared Tracking. Xiangyuan Lan, Mang Ye, Shengping Zhang, Pong C. Yuen. AAAI 2018.
* Two-stage modality-graphs regularized manifold ranking for RGB-T tracking. Chenglong Li, Chengli Zhu, Shaofei Zheng, Bin Luo, Jing Tang. Signal Processing: Image Communication 2018. 

2017

* Grayscale-Thermal Object Tracking via Multitask Laplacian Sparse Representation. Chenglong Li, Xiang Sun, Xiao Wang, Lei Zhang, and Jin Tang. TSMCS 2017.
* Weighted Sparse Representation Regularized Graph Learning for RGB-T Object Tracking. Chenglong Li, Nan Zhao, Yijuan Lu, Chengli Zhu, Jin Tang. ACM MM 2017. RGBT210



2016

* Learning Collaborative Sparse Representation for Grayscale-Thermal Tracking. Chenglong Li, Hui Cheng, Shiyi Hu, Xiaobai Liu, Jin Tang, and Liang Lin. TIP 2016. GTOT
* Real-Time Grayscale-Thermal Tracking via Laplacian Sparse Representation. Chenglong Li, Shiyi Hu, Sihan Gao, and Jin Tang. MultiMedia Modeling 2016.

2012

* An iterative integrated framework for thermal–visible image registration, sensor fusion, and people tracking for video surveillance applications. Atousa Torabi ⇑, Guillaume Massé, Guillaume-Alexandre Bilodeau. CVIU 2012. LITIV
* Fusion tracking in color and infrared images using joint sparse representation. LIU HuaPing, SUN FuChun. Science China Information Sciences 2012. JSR


2011

* Multiple Source Data Fusion via Sparse Representation for Robust Visual Tracking. Wu, Yi and Blasch, Erik and Chen, Genshe and Bai, Li and Ling, Haibin. ICIF 2011. L1-PF


2008

* Thermo-visual feature fusion for object tracking using multiple spatiogram trackers. Conaire C Ó, O’Connor N E, Smeaton A. Machine Vision and Applications 2008.


2007

* Background-subtraction using contour-based fusion of thermal and visible imagery. James W. Davis *, Vinay Sharma. CVIU 2007. OTCBVS
* The Effect of Pixel-Level Fusion on Object Tracking in Multi-Sensor Surveillance Video. N. Cvejic, S. G. Nikolov, H. D. Knowles, A. Łoza, A. Achim, D. R. Bull and C. N. Canagarajah. CVPR 2007.


2006

* Comparison of fusion methods for thermo-visual surveillance tracking. Conaire, C.O. and O'Connor, N.E. and Cooke, E. and Smeaton, A.F. ICIF 2006.
* The influence of multi-sensor video fusion on object tracking using a particle filter. Mihaylova L., Loza A., Nikolov S. G., Lewis J. J., Canga E. -F., Li, J., Dixon T., Canagarajah C. N., Bull D. R. INFORMATIK 2006



### RGB-D Tracking

2024
* Adaptive Colour-Depth Aware Attention for RGB-D Object Tracking. Xue-Feng Zhu, Tianyang Xu, Xiao-Jun Wu, Zhenhua Feng, Josef Kittler. SPL 2024. CDAAT
* Feature enhancement and coarse-to-fine detection for RGB-D tracking. Xue-Feng Zhu, Tianyang Xu, Xiao-Jun Wu, Josef Kittler. PRL 2024. FECD
* Self-supervised learning for RGB-D object tracking. Xue-Feng Zhu, Tianyang Xu, Sara Atito, Muhammad Awais, Xiao-Jun Wu, Zhenhua Feng, Josef Kittler. PR 2024. SSLTrack
* Visual Adapt for RGBD Tracking. Zhang, Guangtong and Liang, Qihua and Mo, Zhiyi and Li, Ning and Zhong, Bineng. ICASSP 2024. VADT.
* 

2023 
* ARKitTrack: A New Diverse Dataset for Tracking Using Mobile RGB-D Data. Haojie Zhao, Junsong Chen, Lijun Wang, Huchuan Lu. CVPR 2023. ARKitTrack.
* Resource-Effcient RGBD Aerial Tracking. Yang, Jinyu and Gao, Shang and Li, Zhe and Zheng, Feng and Leonardis, Ale\v{s}. CVPR 2023. EMT
* RGBD1K: A Large-Scale Dataset and Benchmark for RGB-D Object Tracking. Xue-Feng Zhu, Tianyang Xu, Zhangyong Tang, ZuchengWu, Haodong Liu, Xiao Yang, Xiao-Jun Wu1*, Josef Kittler. AAAI 2023. RGBD1K
* RGB-D Tracking via Hierarchical Modality Aggregation and Distribution Network. Boyue Xu, Yi Xu, Ruichao Hou, Jia Bei, Tongwei Ren, Gangshan Wu. ACM MMA 2023. HAMD

2022
* Learning Dual-Fused Modality-Aware Representations for RGBD Tracking. Shang Gao, Jinyu Yang, Zhe Li, Feng Zheng, Aleš Leonardis, Jingkuan Song. ECCVW 2022. DMTracker
* 

2021
* DepthTrack: Unveiling the Power of RGBD Tracking. Song Yan, Jinyu Yang, Jani K¨apyl¨a, Feng Zheng, Aleˇs Leonardis, Joni-Kristian K¨am¨ar¨ainen. ICCV 2021. DepthTrack.
* Single-scale siamese network based RGB-D object tracking with adaptive bounding boxes. Feng Xiao, Qiuxia Wu, Han Huang. Neurocomputing 2021. 3s-RGBD
* TSDM: Tracking by SiamRPN++ with a Depth-refiner and a Mask-generator. Pengyao Zhao, Quanli Liu, Wei Wang and Qiang Guo. ICPR 2021. TSDM
* 

2020
* An Occlusion-Aware RGB-D Visual Object Tracking Method Based on Siamese Network. Wenli Zhang, Kun Yang, Yitao Xin, Rui Meng. ICSP 2020. SiamOC
* DAL : A deep depth-aware long-term tracker. Yanlin Qian, Alan Lukezic, Matej Kristan, Joni-Kristian Kämäräinen, Jiri Matas. ICPR 2020. DAL
* SRDT: A Novel Robust RGB-D Tracker Based on Siamese Region Proposal Network and Depth Information. Zhen Sun, Junfei Wu, Lu Wang, and Qingdang Li. International Journal of Pattern Recognition and Artificial Intelligence 2020. SRDT
* Robust fusion for RGB-D tracking using CNN features. Yong Wang, Xian Wei, Hao Shen, Lu Ding, Jiuqing Wan. Applied Soft Computing Journal 2020. RF-CFF.
* Robust RGBD Tracking via Weighted Convlution Operators. Weichun Liu, Xiaoan Tang, Chengling Zhao. Sensors 2020. WCO
* Robust RGB-D tracking via compact CNN features. Yong Wang, Xian Wei, Lingkun Luo, Wen Wen, Yang Wang. Engineering Applications of Artificial Intelligence 2020. 

2019
* CDTB: A Color and Depth Visual Object Tracking Dataset and Benchmark. Alan Lukeˇziˇc, Ugur Kart, Jani K¨apyl¨a, Ahmed Durmush, Joni-Kristian K¨am¨ar¨ainen, Jiˇr´ı Matas and Matej Kristan. ICCV 2019. CDTB.
* Context-Aware Three-Dimensional Mean-Shift With Occlusion Handling for Robust Object Tracking in RGB-D Videos. Ye Liu, Xiao-Yuan Jing, Jianhui Nie, Hao Gao, Jun Liu, Guo-Ping Jiang. TMM 2019. CA3DMS
* Depth Information Aided Constrained correlation Filter for Visual Tracking. Guanqun Li, Lei Huang, Peichang Zhang, Qiang Li, YongKai Huo. GSKI  2019. Depth-CCF
* Hierarchical multi-modal fusion FCN with attention model for RGB-D tracking. Ming-xin Jiang, Chao Deng, Jing-song Shan, Yuan-yuan Wang, Yin-jie Jia, Xing Sun. Information Fusion 2019. H-FCN
* Object Tracking by Reconstruction with View-Specific Discriminative Correlation Filters. Ugur Kart, Alan Lukezic, Matej Kristan, Joni-Kristian Kamarainen, Jiri Matas. CVPR 20219. OTR
* RGB-D Object Tracking with Occlusion Detection. Yujun Xie, Yao Lu, Shuang Gu. CIS 2019. RGBD-OD
* RGB-D tracker under Hierarchical structure. Li, Yifan and Wang, Xuan and Jiang, Zoe L. and Qi, Shuhan and Liu, Xinhui and Chen, Qian. CIFEr 2019. 
* Target-Aware Correlation Filter Tracking in RGBD Videos. Kuai, Yangliu and Wen, Gongjian and Li, Dongdong and Xiao, Jingjing. IEEE Sensors Journal 2019.
* Visual Object Tracking in RGB-D Data via Genetic Feature Learning. Ming-xin Jiang, Xian-xian Luo, Tao Hai, Hai-yan Wang, Song Yang and Ahmed N. Abdalla. Complexity 2019.

2018
* A Real-time RGB-D tracker based on KCF. Han Zhang, Meng Cai, Jianxun Li. CCDC 2018. RT-KCF
* Depth Masked Discriminative Correlation Filter. Uğur Kart, Joni-Kristian Kämäräinen, Jiří Matas, Lixin Fan, Francesco Cricri. ICPR 2018. DM-DCF
* How to Make an RGBD Tracker ?. Kart, Uğur and Kämäräinen, Joni-Kristian and Matas, Jiří. ECCVW 2018.
* Multimodal Deep Feature Fusion (MMDFF) for RGB-D Tracking. Ming-xin Jiang, Chao Deng, Ming-min Zhang, Jing-song Shan, and Haiyan Zhang. Complexity 2018. MMDFF
* Occlusion-Aware Correlation Particle Filter Target Tracking Based on RGBD Data. Yayu Zhai, Ping Song, Zonglei Mou, Xiaoxiao Chen, Xiongjun Liu. Access 2018. OACPF
* Robust Fusion of Color and Depth Data for RGB-D Target Tracking Using Adaptive Range-Invariant Depth Models and Spatio-Temporal Consistency Constraints. Jingjing Xiao, Rustam Stolkin, Yuqing Gao, and Aleš Leonardis. TCYB 2018. STC.
* Real-Time RGB-D Visual Tracking With Scale Estimation and Occlusion Handling. Jiaxu Leng, Ying Liu. IEEE Access 2018.
* 

2017
* Robust Object Tracking with RGBD-based Sparse Learning. Zi-ang Ma, Zhi-yu Xiang. ITEE 2017. ROTSL
* RGB-D Tracking Based on Kernelized Correlation Filter with Deep Features. Gu, Shuang and Lu, Yao and Zhang, Lin and Zhang, Jian. ICONIP 2017.
* Visual Object Tracking Based on Cross-Modality Gaussian-Bernoulli Deep Boltzmann Machines with RGB-D Sensors. Mingxin Jiang, Zhigeng Pan and Zhenzhou Tang. Sensors 2017.

2016
* DS-KCF: A Real-time Tracker for RGB-D Data. Sion Hannuna, Massimo Camplani, Jake Hall, Majid Mirmehdi, Dima Damen, Tilo Burghardt, Adeline Paiement, Lili Tao. RTIP 2016. DS-KCF_shape
* Online RGB-D Tracking via Detection-Learning-Segmentation. Ning An, Xiao-Guang Zhao, Zeng-Guang Hou. ICPR 2016. DLS
* Occlusion Aware Particle Filter Tracker to Handle Complex and Persistent Occlusions. Kourosh Meshgia, Shin-ichi Maedaa, Shigeyuki Obaa, Henrik Skibbea, Yu-zhe Lia, Shin Ishii. CVIU 2016. OAPF
* 3D Part-Based Sparse Tracker with Automatic Synchronization and Registration. Adel Bibi, Tianzhu Zhang, Bernard Ghanem. CVPR 2016. 3D-T

2015
* Real-time RGB-D Tracking with Depth Scaling Kernelised Correlation Filters and Occlusion Handling. Massimo Camplani, Sion Hannuna, Majid Mirmehdi, Dima Damen, Adeline Paiement, Lili Tao, Tilo Burghardt. BMVC 2015 DS-KCF
* Robust Object Tracking Using Color and Depth Images with a Depth Based Occlusion Handling and Recovery. Ping Ding, Yan Song. FSKD 2015. DOHR
* Using Consistency of Depth Gradient to Improve Visual Tracking in RGB-D sequences. Huizhang Shi, Changxin Gao, Nong Sang. CAC 2015. CDG
* 

2014
* Multi-Cue Based Tracking. Qi Wang, Jianwu Fang, Yuan Yuan. Multi-Cue Based Tracking. Neurocomputing  2014. MCBT
* Automatic Video Segmentation and Object Tracking with Real-Time RGB-D Data. I-Kuei Chen, Szu-Lu Hsu, Chung-Yu Chi, and Liang-Gee Chen. ICCE 2014
* Occlusion Handling Method for Object Tracking Using RGB-D data. Ariel Benou, Itay Benou, Rami Hagage. IEEEI 2014.

2013
* Tracking Revisited using RGBD Camera: Unified Benchmark and Baselines. Shuran Song Jianxiong Xiao. ICCV 2013. PTB.

2012
* Adaptive Multi-cue 3D Tracking of Arbitrary Objects. Germán Martín García, Dominik Alexander Klein, Jörg Stückler, Simone Frintrop, Armin B. Cremers. JDOS 2012. AMCT
* 



### RGB-E Tracking

2024
* CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras. Yabin Zhu, Xiao Wang, Chenglong Li, Bo Jiang, Lin Zhu, Zhixiang Huang, Yonghong Tian, Jin Tang. Arxiv 2024. CRSOT
* Long-term Frame-Event Visual Tracking: Benchmark Dataset and Baseline. Xiao Wang, Ju Huang, Shiao Wang, Chuanming Tang, Bo Jiang, Yonghong Tian, Jin Tang, and Bin Luo. Arxiv 2024. FELT
* Mamba-FETrack: Frame-Event Tracking via State Space Model. Ju Huang, Shiao Wang, Shuai Wang, Zhe Wu, Xiao Wang, Bo Jiang. Arxiv 2024. Mamba-FETrack
* Reliable Object Tracking by Multimodal Hybrid Feature Extraction and Transformer-Based Fusion. Hongze Sun, Rui Liu, Wuque Cai, Jun Wang, Yue Wang, Huajin Tang, Yan Cui, Dezhong Yao, Daqing Guo. Arxiv 2024. MMHT.
* TENet: Targetness Entanglement Incorporating with Multi-Scale Pooling and Mutually-Guided Fusion for RGB-E Object Tracking. Pengcheng Shao, Tianyang Xu, Zhangyong Tang, Linze Li, Xiao-Jun Wu, Josef Kittler. Arxiv 2024. TENet


2023
* Cross-modal Orthogonal High-rank Augmentation for RGB-Event Transformer-trackers. Zhiyu Zhu, Junhui Hou, Dapeng Oliver Wu. ICCV 2023.
* Frame-Event Alignment and Fusion Network for High Frame Rate Tracking. Jiqing Zhang, Yuanchen Wang, Wenxi Liu, Meng Li, Jinpeng Bai, Baocai Yin, Xin Yang. CVPR 2023. AFNet
* VisEvent: Reliable Object Tracking via Collaboration of Frame and Event Flows. Xiao Wang, Jianing Li, Lin Zhu, Zhipeng Zhang, Zhe Chen, Xin Li, Yaowei Wang, Yonghong Tian, and Feng Wu. TCYB 2023. VisEvent

2022
* Revisiting Color-Event based Tracking: A Unified Network, Dataset, and Metric. Chuanming Tang, Xiao Wang, Ju Huang, Bo Jiang, Lin Zhu, Jianlin Zhang, Yaowei Wang, Yonghong Tian. Arxiv 2022. COESOT

2021
* Multi-domain Collaborative Feature Representation for Robust Visual Object Tracking. Jiqing Zhang, Kai Zhao, Bo Dong, Yingkai Fu, Yuxin Wang, Xin Yang, Baocai Yin. The Visual Computer 2021. CFE
* Object Tracking by Jointly Exploiting Frame and Event Domain. Jiqing Zhang, Xin Yang, Yingkai Fu, Xiaopeng Wei, Baocai Yin, Bo Dong. ICCV 2021. FE108
* 

### RGB-L Tracking
2024
* Context-Aware Integration of Language and Visual References for Natural Language Tracking. Yanyan Shao, Shuting He, Qi Ye, Yuchao Feng, Wenhan Luo, Jiming Chen. CVPR 2024. QueryNLT.
* DTLLM-VLT: Diverse Text Generation for Visual Language Tracking Based on LLM. Xuchen Li, Xiaokun Feng, Shiyu Hu, Meiqi Wu, Dailing Zhang, Jing Zhang, Kaiqi Huang. CVPRW 2024. DTLLM-VLT.
* Multimodal Features Alignment for Vision–Language Object Tracking. Ping Ye, Gang Xiao, Jun Liu. Remote Sensing 2024.
* One-Stream Stepwise Decreasing for Vision-Language Tracking. Guangtong Zhang, Bineng Zhong, Qihua Liang, Zhiyi Mo, Ning Li, Shuxiang Song. TCSVT 2024. OSDT
* Textual Tokens Classification for Multi-Modal Alignment in Vision-Language Tracking. Zhongjie Mao; Yucheng Wang; Xi Chen; Jia Yan. ICASSP 2024. TTCTrack.
* Toward Unified Token Learning for Vision-Language Tracking. Zheng, Yaozong and Zhong, Bineng and Liang, Qihua and Li, Guorong and Ji, Rongrong and Li, Xianxian. TCSVT 2024. MMTrack.
* Unifying Visual and Vision-Language Tracking via Contrastive Learning. Yinchao Ma, Yuyang Tang, Wenfei Yang, Tianzhu Zhang, Jinpeng Zhang, Mengxue Kang. AAAI 2024. UVLTrack
* VastTrack: Vast Category Visual Object Tracking. Liang Peng, Junyuan Gao, Xinran Liu, Weihong Li, Shaohua Dong, Zhipeng Zhang, Heng Fan, and Libo Zhang. Arxiv 2024. VastTrack.
* WebUOT-1M: Advancing Deep Underwater Object Tracking with A Million-Scale Benchmark. Chunhui Zhang, Li Liu, Guanjie Huang, Hao Wen, Xi Zhou, Yanfeng Wang. Arxiv 2024. [[Paper](https://arxiv.org/pdf/2405.19818)] [[Code](https://github.com/983632847/Awesome-Multimodal-Object-Tracking?tab=readme-ov-file)]

2023
* A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Causal Relationship. Shiyu Hu, Dailing Zhang, Meiqi Wu, Xiaokun Feng, Xuchen Li, Xin Zhao, Kaiqi Huang. NIPS 2023. MGIT.
* All in One: Exploring Unified Vision-Language Tracking with Multi-Modal Alignment. Chunhui Zhang, Xin Sun, Li Liu, Yiqian Yang, Qiong Liu, Xi Zhou, Yanfeng Wang. ICCV 2023. ALl in One
* Beyond Visual Cues: Synchronously Exploring Target-Centric Semantics for Vision-Language Tracking. Jiawei Ge, Xiangmei Chen, Jiuxin Cao, Xuelin Zhu, Bo Liu. Arxiv 2023. SATracker
* CiteTracker: Correlating Image and Text for Visual Tracking. Xin Li, Yuqing Huang, Zhenyu He, Yaowei Wang, Huchuan Lu, Ming-Hsuan Yang. ICCV 2023. CiteTracker.
* Divert More Attention to Vision-Language Object Tracking. Mingzhe Guo, Zhipeng Zhang, Liping Jing, Haibin Ling, Heng Fan. Arxiv 2023. VLT_TT
* Joint Visual Grounding and Tracking with Natural Language Specifcation. Li Zhou, Zikun Zhou, Kaige Mao, Zhenyu He. CVPR 2023. JointNLT.
* Multi-Modal Object Tracking with Vision-Language Adaptive Fusion and Alignment. Zuo, Jixiang and Wu, Tao and Shi, Meiping and Liu, Xueyan and Zhao, Xijun. RICAI 2023. VLATrack.
* One-Stream Vision-Language Memory Network for Object Tracking. Zhang, Huanlong and Wang, Jingchao and Zhang, Jianwei and Zhang, Tianzhu and Zhong, Bineng. TMM 2023. OVLM.
* Tracking by Natural Language Specification with Long Short-term Context Decoupling. Ma, Ding and Wu, Xiangqian. ICCV 2023. DecoupleTNL
* Transformer vision-language tracking via proxy token guided cross-modal fusion. Haojie Zhao, Xiao Wang, Dong Wang, Huchuan Lu, Xiang Ruan. PRL 2023.

2022
* Cross-modal Target Retrieval for Tracking by Natural Language. Li, Yihao and Yu, Jun and Cai, Zhongpeng and Pan, Yuwen. CVPRW 2022. AdaRS
* Divert More Attention to Vision-Language Tracking. Mingzhe Guo, Zhipeng Zhang, Heng Fan, Liping Jing. NIPS 2022. VLT_TT

2021
* Capsule-based Object Tracking with Natural Language Specification. Ding Ma, Xiangqian Wu. ACM MM 2021. CapsuleNLT
* LaSOT: A High-quality Large-scale Single Object Tracking Benchmark. Heng Fan, Hexin Bai, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Harshit, Mingzhen Huang, Juehuan Liu, Yong Xu, Chunyuan Liao, Lin Yuan, Haibin Ling. IJCV 2021. LaSOT_EXT.
* Siamese Natural Language Tracker: Tracking by Natural Language Descriptions with Siamese Trackers. Qi Feng, Vitaly Ablavsky, Qinxun Bai, Stan Sclaroff. CVPR 2021. SNLT.
* Towards More Flexible and Accurate Object Tracking with Natural Language: Algorithms and Benchmark. Xiao Wang, Xiujun Shu, Zhipeng Zhang, Bo Jiang, Yaowei Wang, Yonghong Tian, Feng Wu. CVPR 2021. TNL2K.

2020
* Real-time visual object tracking with natural language description. Qi Feng, Vitaly Ablavsky, Qinxun Bai, Guorong Li, and Stan Sclarof. WACV 2020. RTTNLD

2019
* LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking. Heng Fan, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Hexin Bai, Yong Xu, Chunyuan Liao, Haibin Ling. CVPR 2019. LaSOT.
* Robust visual object tracking with natural language region proposal network. Feng, Qi and Ablavsky, Vitaly and Bai, Qinxun and Sclaroff, Stan. Arxiv 2019. RVTNLN.

2017
* Tracking by Natural Language Specification. Zhenyang Li, Ran Tao, Efstratios Gavves, Cees G. M. Snoek, Arnold W.M. Smeulders. CVPR 2017. OTB99-L. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Tracking_by_Natural_CVPR_2017_paper.pdf)] [[Code](https://github.com/QUVA-Lab/lang-tracker)]

### RGB-NIR Tracking

* Cross-Modal Object Tracking via Modality-Aware Fusion Network and A Large-Scale Dataset. Lei Liu, Mengya Zhang, Cheng Li, Chenglong Li, and Jin Tang. TNNLS 2024. CMOTB. [[Paper](https://github.com/mmic-lcl/Datasets-and-benchmark-code)] [[Code](https://github.com/xfarawayx/CMOTB_Toolkit)]
* Cross-Modal Object Tracking: Modality-Aware Representations and A Unified Benchmark. Chenglong Li, Tianhao Zhu, Lei Liu, Xiaonan Si, Zilin Fan, Sulan Zhai. AAAI 2022. CMOTB. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20016)] [[Code](https://github.com/xfarawayx/CMOTB_Toolkit)]

### RGB-Mutli Tracking

* UniMod1K: Towards a More Universal Large-Scale Dataset and Benchmark for Multi-modal Learning. Xue-Feng Zhu, Tianyang Xu, Zongtao Liu, Zhangyong Tang, Xiao-Jun Wu & Josef Kittler. IJCV 2024. [[Paper](https://link.springer.com/article/10.1007/s11263-024-01999-8)] [[Code](https://github.com/xuefeng-zhu5/UniMod1K)] 
* WebUAV-3M: A Benchmark for Unveiling the Power of Million-Scale Deep UAV Tracking. Chunhui Zhang, Guanjie Huang, Li Liu, Shan Huang, Yinan Yang, Xiang Wan, Shiming Ge, and Dacheng Tao. TPAMI 2023. [[Paper](https://ieeexplore.ieee.org/document/10004511)]


## Compeletations
 1. [AntiUAV 1st](https://anti-uav.github.io/)
	The first AntiUAV challenge is a multi-modal challenge. It was held in 2020.  The website for the 1st AntiUAV is covered by the newest one. The winner is team *xiaobaibai*. One of its member is [Tianyang Xu](https://xu-tianyang.github.io/)
 2. [VOT-RGBT2019](https://votchallenge.net/vot2019/)
 	The first competition in the RGBT tracking community. It was held in 2019. The winner is *SiamDW*.
 3. [VOT-RGBT2020]
    A competition in the RGBT tracking community. It was held in 2020. The winner is *DFAT*. One of its member is [Zhangyong Tang](https://github.com/Zhangyong-Tang/)


## Awesome Repositories
* [Awesome-Multimodal-Object-Tracking](https://github.com/983632847/Awesome-Multimodal-Object-Tracking)
* [RGB-Event-Benchmarks](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark)
* [RGBT-Thermal-Results-Datasets-Methods](https://github.com/Zhangyong-Tang/RGBT-Tracking-Results-Datasets-and-Methods)

## Acknowledgements
This work is supported by [PRCI-Lab](https://github.com/PRCI-Lab), which is an outstanding and also fast-developing group. Please feel free to find out more information through its home page.


## Questions

If you have any questions, please feel free to start the issue, or contact me at zhangyong_tang_jnu@163.com (wechat: Tzy18861871359  is also welcomed).



## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Zhangyong-Tang/MultiModal-Visual-Object-tracking&type=Date)](https://star-history.com/#Zhangyong-Tang/MultiModal-Visual-Object-tracking&Date)


