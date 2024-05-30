#  A Comprehensive Survey for Multi-Modal Visual Object tracking

<p align="center">
<img src="https://github.com/Zhangyong-Tang/MultiModal-Visual-Object-tracking/blob/main/logo.png" width="500">
</p>

#### We appreciate any efforts committed to the development of Multi-Modal Visual Object Tracking. Please feel free to connect us (zhangyong_tang_jnu@163.com) for discussion or missed works.


## :collision: Update Log 
* [2024.05.29] All datasets are listed.
* [2024.05.28] All survey papers and RGBT papers are listed.
* [2023.12.16] The repository is started.

## Datasets and Benchmarks

### RGB-Mutli Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| UniMod1K| IJCV'2024 |[UniMod1K](https://github.com/xuefeng-zhu5/UniMod1K) |RGB+D+L|
| WebUAV-3M| TPAMI'2023 | [WebUAV-3M](https://github.com/983632847/WebUAV-3M) | RGB+L+Audio|

### RGBT Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| MV-RGBT| Arxiv'2024 |[MV-RGBT]() |122 video pairs. The data in this benchmark mainly focus on the modality validity.|
| VTUAV| CVPR'2022 |[VTUAV](https://zhang-pengyu.github.io/DUT-VTUAV/) | imaged in the top-down view by uav, long-term;176 videos in the test-st, which has around 3500 frames in average|
| LasHeR| TIP'2021 | [LasHeR](https://github.com/BUGPLEASEOUT/LasHeR) | train/test split, imaged in the head-up view, above 70W image pairs in total; 245 videos in the test set|
| VOT-RGBT20| VOT Community： 2020 | [VOT-RGBT2020](https://pan.baidu.com/s/1fNgAVk4siqP2p-b1M2ZGmg ) *CODE:TZYD*| 60 Video pairs, its data is the same with VOT-RGBT2019, but with different evaluation mechanism|
| VOT-RGBT19| VOT Community：2019 |[VOT-RGBT2019](https://pan.baidu.com/s/1kYnTTWF9LIkrCH4NNsSlFQ) *CODE:TZYD* | 60 Video pairs, about 2W frame pairs, a sub-set of RGBT 234|
| RGBT234| PR'2018 | [RGBT234](https://sites.google.com/view/ahutracking001/)| 234 Video pairs, the extension of RGBT210 |
| RGBT210| ACM MM'2017 | [RGBT210](https://drive.google.com/file/d/0B3i2rdXLNbdUTkhsLVRwcTBTMlU/view?resourcekey=0-vytg_w3hqlQfLhoiS2J8Dg) | 210 Video pairs|
| GTOT | TIP'2016 | [GTOT](https://pan.baidu.com/s/1QNidEo-HepRaS6OIZr7-Cw) | 50 Video pairs, about 1.5W frames|
| LITIV | CVIU'2012 | [LITIV](https://www.polymtl.ca/litiv/en/codes-and-datasets) | 9 video pairs|
| OTCBVS | CVIU'2007 | [OTCBVS](http://vcipl-okstate.org/pbvs/bench/) | 6 video pairs|
| LSS-Dataset(from RGB) | TCSVT'2021 | [LSS-Dataset](https://pan.baidu.com/s/1x2hiqb2lSo54_4CI_L9YeQhttps://pan.baidu.com/s/1x2hiqb2lSo54_4CI_L9YeQ) ,code(Ye5Q)| Generated from VID|
| LSS-Dataset(from TIR) | TCSVT'2021 | [LSS-Dataset](https://pan.baidu.com/s/1xD3Ox-9VbZnyRQSWOxQRNw),code(IHws) | Generated from TIR|


### RGBD Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| ARKittrack| CVPR'2023 | [ARKittrack](https://github.com/lawrence-cj/ARKitTrack) | -|
| RGBD1K | AAAI'2023 | [RGBD1K](https://github.com/xuefeng-zhu5/RGBD1K) | -|
| DepthTrack | ICCV'2021 | [DepthTrack](https://github.com/xiaozai/DeT) | -|
| CDTB | ICCV'2019 | [CDTB](https://www.votchallenge.net/vot2019/dataset.html) | -|
| STC | ICCV'2019 | [STC](https://pan.baidu.com/s/1Y3z2JH-oR68-stWFVnHUVw) code:TZYD| -|
| PTB | ICCV'2013 | [PTB](https://tracking.cs.princeton.edu/index.html) | -|


### RGBE Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| CRSOT| Arxiv'2024 |[CRSOT](https://github.com/Event-AHU/Cross_Resolution_SOT) |-|
| FELT| Arxiv'2024 |[FELT](https://github.com/Event-AHU/FELT_SOT_Benchmark) | -|
| COESOT| Arxiv'2022 | [COESOT](https://github.com/Event-AHU/COESOT)| -|
| VisEvent| TCYB'2023 |[VisEvent](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark?tab=readme-ov-file)| -|
| FE108/FE240hz| ICCV'2021 | [FE108/FE240hz](https://github.com/Jee-King/ICCV2021_Event_Frame_Tracking)| -|



### RGBL Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| VastTrack| Arxiv'2024 |[VastTrack](https://github.com/HengLan/VastTrack) |-|
| MGIT| NIPS'2023 |[MGIT](http://videocube.aitestunion.com/) | -|
| TNL2K| CVPR'2021 | [TNL2K](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)| -|
| LaSOT_EXT| IJCV'2021 |[LaSOT_EXT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)| -|
| LaSOT| CVPR'2019 | [LaSOT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|- |
| OTB99-L| CVPR'2017 | [OTB99-L](https://github.com/QUVA-Lab/lang-tracker) | -|


### RGBNIR Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| CMOTB| TNNLS'2024 |[CMOTB](https://github.com/xfarawayx/CMOTB_Toolkit?tab=readme-ov-file) |-|




## Surveys 
* RGBT ---- RGBT tracking: A comprehensive review. Mingzheng Feng, Jianbo Su*. Information Fusion 2024. [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253524002707)]
* RGBT ---- Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective. Zhihao Zhang, Jun Wang, Zhuli Zang, Lei Jin, Shengjie Li, Hao Wu*,Jian Zhao, Zhang Bo. ACM TOMM 2024. [[Paper](https://dl.acm.org/doi/10.1145/3651308)]
* RGBT---- Object fusion tracking based on visible and infrared images: A comprehensive review. Xingchen Zhang, Ping Ye, Henry Leung, Ke Gong, Gang Xiao*. Information Fusion 2020. [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253520302657)]
* RGBT---- A Survey for Deep RGBT Tracking. Zhangyong Tang, Tianyang Xu, and Xiao-Jun Wu*. Arxiv 2022. [[Paper](https://arxiv.org/abs/2201.09296)]
* RGBD---- A Survey of RGB-Depth Object Tracking. Zhou Ou, Ge Ying, Dawei Zhang*, Zhonglong Zheng. Journal of Computer-Aided Design & Computer Graphics 2024. [[Paper](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.null.2023-00537)]
* RGBD---- Rgbd object tracking: An in-depth review. Jinyu Yang, Zhe Li, Song Yan, Feng Zheng*, Aleš Leonardis, Joni-Kristian Kämäräinen, Ling Shao. Arxiv 2022. [[Paper](https://arxiv.org/abs/2203.14134)]
* RGBD/T ---- Multi-modal visual tracking: Review and experimental comparison. Zhang, Pengyu, Dong Wang*, and Huchuan Lu. Computational Visual Media 2024. [[Paper](https://link.springer.com/article/10.1007/s41095-023-0345-5)]




## Regular Papers 

### Unified (Model or Architecture for) Multi-Modal Tracking

* Unified Sequence-to-Sequence Learning for Single- and Multi-Modal Visual Object Tracking. Xin Chen, Ben Kang, Jiawen Zhu, Dong Wang*, Houwen Peng, and Huchuan Lu. Arxiv 2024. [[Paper](https://arxiv.org/pdf/2304.14394)] [[Code](https://github.com/chenxin-dlut/SeqTrackv2)] 
* SDSTrack: Self-Distillation Symmetric Adapter Learning for Multi-Modal Visual Object Tracking. Xiaojun Hou, Jiazheng Xing, Yijie Qian, Yaowei Guo, Shuo Xin, Junhao Chen,
Kai Tang, Mengmeng Wang, Zhengkai Jiang, Liang Liu*, Yong Liu*. CVPR 2024. [[Paper](https://arxiv.org/pdf/2403.16002)] [[Code](https://github.com/hoqolo/SDSTrack)]
* Single-Model and Any-Modality for Video Object Tracking. Zongwei Wu, Jilai Zheng, Xiangxuan Ren, Florin-Alexandru Vasluianu, Chao Ma*, Danda Pani Paudel, Luc Van Gool, Radu Timofte. CVPR 2024. [[Paper](https://arxiv.org/abs/2311.15851)] [[Code](https://github.com/Zongwei97/UnTrack)]
* OneTracker: Unifying Visual Object Tracking with Foundation Models and Efficient Tuning. Lingyi Hong, Shilin Yan, Renrui Zhang, Wanyun Li, Xinyu Zhou, Pinxue Guo, Kaixun Jiang, Yiting Chen, Jinglun Li, Zhaoyu Chen, Wenqiang Zhang*. CVPR 2024. [[Paper](https://arxiv.org/pdf/2403.09634)]
* Knowledge Synergy Learning for Multi-Modal Tracking. He, Yuhang and Ma, Zhiheng and Wei, Xing and Gong, Yihong. TCSVT 2024. KSTrack.
* MINet: Modality interaction network for unified multi-modal tracking. Shuang Gong, Zhu Teng1*, Rui Li, Jack Fan, Baopeng Zhang, Jianping Fan. IVC 2024. [[Paper](https://www.sciencedirect.com/science/article/pii/S0262885624001756)]
* Visual Prompt Multi-Modal Tracking. Jiawen Zhu, Simiao Lai, Xin Chen, Dong Wang*, Huchuan Lu. CVPR 2023.  [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_Visual_Prompt_Multi-Modal_Tracking_CVPR_2023_paper.pdf)] [[Code](https://github.com/jiawen-zhu/ViPT)]

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
* Prompting for multi-modal tracking. Yang, Jinyu and Li, Zhe and Zheng, Feng and Leonardis, Ales and Song, Jingkuan. ACM MM 2022. ProTrack
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
* Learning Adaptive Attribute-Driven Representation for Real-Time RGB-T Tracking. Pengyu Zhang, Dong Wang, Huchuan Lu, Xiaoyun Yang. IJCV 2021. ADRNet.
* Learning a Twofold Siamese Network for RGB-T Object Tracking. Yangliu Kuai, Dongdong Li, and Que Qian. Journal of Circuits, Systems and Computers 2021. 
* M5L: Multi-Modal Multi-Margin Metric Learning for RGBT Tracking. Zhengzheng Tu, Chun Lin, Chenglong Li, Jin Tang, Bin Luo. TIP 2021. M5L
* Multimodal Cross-Layer Bilinear Pooling for RGBT Tracking. Qin Xu, Yiming Mei, Jinpei Liu, and Chenglong Li. TMM 2021. CBPNet
* RGBT Tracking via Multi-Adapter Network with Hierarchical Divergence Loss. Andong Lu, Chenglong Li, Yuqing Yan, Jin Tang, Bin Luo. TIP 2021. MANet++
* RGBT Tracking via Noise-Robust Cross-Modal Ranking. Li, Chenglong and Xiang, Zhiqiang and Tang, Jin and Luo, Bin and Wang, Futian. TNNLS 2021. CMR
* RGBT tracking via cross-modality message passing. Rui Yang, Xiao Wang, Chenglong Li, Jinmin Hu, Jin Tang. Neurocomputing 2021. GCMP
* SiamCDA: Complementarity-and distractor-aware RGB-T tracking based on Siamese network. Zhang, Tianlu and Liu, Xueru and Zhang, Qiang and Han, Jungong. TCSVT 2021. SiamCDA.
* WF_DiMP: weight-aware dual-modal feature aggregation mechanism for RGB-T tracking. Zhaodi Wang, Yan Ding, Pingping Wu, Jinbo Zhang. SEVENTH SYMPOSIUM ON NOVEL PHOTOELECTRONIC DETECTION TECHNOLOGY AND APPLICATIONS 2021. WF_DiMP
* 




2020

* Cross-Modal Pattern-Propagation for RGB-T Tracking. Chaoqun Wang, Chunyan Xu, Zhen Cui, Ling Zhou, Tong Zhang, Xiaoya Zhang, Jian Yang. CVPR 2020. CMPP
* Challenge-Aware RGBT Tracking. Chenglong Li, Lei Liu, Andong Lu, Qing Ji, Jin Tang. ECCV 2020. CAT
* DSiamMFT: An RGB-T fusion tracking method via dynamic Siamese networks using multi-layer feature fusion. Xingchen Zhang, Ping Ye, Shengyun Peng, Jun Liu, Gang Xiao. Signal Processing: Image Communication 2020. DSiamMFT
* FANet: Quality-Aware Feature Aggregation Network for Robust RGB-T Tracking. Yabin Zhu, Chenglong Li, Bin Luo, Jin Tang. TIV 2020. FANet
* Learning discriminative update adaptive spatial-temporal regularized correlation filter for RGB-T tracking. Mingzheng Feng, Kechen Song, Yanyan Wang, Jie Liu, Yunhui Yan. Journal of Visual Communication and Image Representation 2020.
* Object Tracking in RGB-T Videos Using Modal-Aware Attention Network and Competitive Learning. Hui Zhang, Lei Zhang, Li Zhuo, Jing Zhang. Sensors 2020. MacNet
* RGB-T Tracking via Multi-expert Correlation Filters using Spatial-temporal Robustness. Zhang, Fei and Ma, Shiping and Li, Zhijun and Zhang, Yule. ICMCCE 2020. MECF

2019

* Dense Feature Aggregation and Pruning for RGBT Tracking. Yabin Zhu, Chenglong Li, Bin Luo, Jin Tang, Xiao Wang. ACM MM 2019. DAPNet.
* Deep Adaptive Fusion Network for High Performance RGBT Tracking. Yuan Gao, Chenglong Li, Yabin Zhu, Jin Tang, Tao He, Futian Wang. ICCVW 2019. DAFNet
* Fast RGB-T Tracking via Cross- Modal Correlation Filters. Sulan Zhai, Pengpeng Shao*, Xinyan Liang, Xin Wang. Neurocomputing 2019
* Learning Local-Global Multi-Graph Descriptors for RGB-T Object Tracking. Chenglong Li, Chengli Zhu, Jian Zhang, Bin Luo, Xiaohao Wu, and Jin Tang. TCSVT 2019. LGMG
* Learning Target-oriented Dual Attention for Robust RGB-T Tracking. Rui Yang, Yabin Zhu, Xiao Wang, Chenglong Li, Jin Tang. Arxiv 2019.
* Multi-Modal Fusion for End-to-End RGB-T Tracking. Lichao Zhang, Martin Danelljan, Abel Gonzalez-Garcia, Joost van de Weijer, Fahad Shahbaz Khan. ICCVW 2019. mfDiMP
* Multi-Adapter RGBT Tracking. Chenglong Li, Andong Lu, Aihua Zheng, Zhengzheng Tu, Jin Tang. ICCVW 2019. MANet
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

2016

* Real-Time Grayscale-Thermal Tracking via Laplacian Sparse Representation. Chenglong Li, Shiyi Hu, Sihan Gao, and Jin Tang. MultiMedia Modeling 2016.

2012

* Fusion tracking in color and infrared images using joint sparse representation. LIU HuaPing, SUN FuChun. Science China Information Sciences 2012. JSR


2011

* Multiple Source Data Fusion via Sparse Representation for Robust Visual Tracking. Wu, Yi and Blasch, Erik and Chen, Genshe and Bai, Li and Ling, Haibin. ICIF 2011. L1-PF


2008

* Thermo-visual feature fusion for object tracking using multiple spatiogram trackers. Conaire C Ó, O’Connor N E, Smeaton A. Machine Vision and Applications 2008.


2007

* The Effect of Pixel-Level Fusion on Object Tracking in Multi-Sensor Surveillance Video. N. Cvejic, S. G. Nikolov, H. D. Knowles, A. Łoza, A. Achim, D. R. Bull and C. N. Canagarajah. CVPR 2007.


2006

* Comparison of fusion methods for thermo-visual surveillance tracking. Conaire, C.O. and O'Connor, N.E. and Cooke, E. and Smeaton, A.F. ICIF 2006.
* The influence of multi-sensor video fusion on object tracking using a particle filter. Mihaylova L., Loza A., Nikolov S. G., Lewis J. J., Canga E. -F., Li, J., Dixon T., Canagarajah C. N., Bull D. R. INFORMATIK 2006



### RGB-D Tracking
2024
* Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective. Zhihao Zhang, Jun Wang, Zhuli Zang, Lei Jin, Shengjie Li, Hao Wu*,Jian Zhao, Zhang Bo. ACM TOMM 2024. [[Paper](https://dl.acm.org/doi/10.1145/3651308)]
* 

### RGB-E Tracking
2024
* Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective. Zhihao Zhang, Jun Wang, Zhuli Zang, Lei Jin, Shengjie Li, Hao Wu*,Jian Zhao, Zhang Bo. ACM TOMM 2024. [[Paper](https://dl.acm.org/doi/10.1145/3651308)]
* 

### RGB-L Tracking
2024
* Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective. Zhihao Zhang, Jun Wang, Zhuli Zang, Lei Jin, Shengjie Li, Hao Wu*,Jian Zhao, Zhang Bo. ACM TOMM 2024. [[Paper](https://dl.acm.org/doi/10.1145/3651308)]
* 

### RGB-NIR Tracking
2024
* Review and Analysis of RGBT Single Object Tracking Methods: A Fusion Perspective. Zhihao Zhang, Jun Wang, Zhuli Zang, Lei Jin, Shengjie Li, Hao Wu*,Jian Zhao, Zhang Bo. ACM TOMM 2024. [[Paper](https://dl.acm.org/doi/10.1145/3651308)]
* 

### RGB-Mutli Tracking

* UniMod1K: Towards a More Universal Large-Scale Dataset and Benchmark for Multi-modal Learning. Xue-Feng Zhu, Tianyang Xu, Zongtao Liu, Zhangyong Tang, Xiao-Jun Wu & Josef Kittler. IJCV 2024. [[Paper](https://link.springer.com/article/10.1007/s11263-024-01999-8)]
* WebUAV-3M: A Benchmark for Unveiling the Power of Million-Scale Deep UAV Tracking. Chunhui Zhang, Guanjie Huang, Li Liu, Shan Huang, Yinan Yang, Xiang Wan, Shiming Ge, and Dacheng Tao. TPAMI 2023. [[Paper](https://ieeexplore.ieee.org/document/10004511)]

## Compeletations
 1. [AntiUAV 1st](https://anti-uav.github.io/)
	The first AntiUAV challenge is a multi-modal challenge. It was held in 2020.  The website for the 1st AntiUAV is covered by the newest one. The winner is team *xiaobaibai*. One of its member is [Tianyang Xu](https://xu-tianyang.github.io/)
 2. [VOT-RGBT2019](https://votchallenge.net/vot2019/)
 	The first competition in the RGBT tracking community. It was held in 2019. The winner is *SiamDW*.
 3. [VOT-RGBT2020]
    A competition in the RGBT tracking community. It was held in 2020. The winner is *DFAT*. One of its member is [Zhangyong Tang](https://github.com/Zhangyong-Tang/)


## Acknowledgements
This work is supported by [PRCI-Lab](https://github.com/PRCI-Lab), which is an outstanding and also fast-developing group. Please feel free to find out more information through its home page.


**Questions**

If you have any questions, please feel free to start the issue, or contact me at zhangyong_tang_jnu@163.com (wechat: Tzy18861871359  is also welcomed).



## Star History

<a href="https://star-history.com/#Zhangyong-Tang/MultiModal-Visual-Object-tracking&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Zhangyong-Tang/MultiModal-Visual-Object-tracking&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Zhangyong-Tang/MultiModal-Visual-Object-tracking&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Zhangyong-Tang/MultiModal-Visual-Object-tracking&type=Date" />
 </picture>
</a>

