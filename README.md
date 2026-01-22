# Awesome Memory VLA
This is a collection of research papers for Visual-Language-Action (VLA) models with memory, designed to solve long-horizon, partially observabe tasks. The repository shall be regularly updated to track the frontiers. 
As there is no generally accepted definition of memory in the context of VLA, we include all works related to the ability of VLA systems to process information over horizons longer than a single step.

Since most VLAs are based on Visual-Language Models (VLMs), we also included a section on VLMs with memory.

TODOs:
- [ ] Separate navigation and manipulation models with memory

-----
Contributions are welcome. Submit a [PR](https://github.com/avanturist322/awesome-memory-vla/pulls) with relevant papers or resources you consider significant.
```
format:
- [title](paper link)
  - author1, author2, and author3...
```

## Papers | VLA + memory
### 2025
- [Action-Sketcher: From Reasoning to Action via Visual Sketches for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2601.01618)
  - Huajie Tan, Peterson Co, Yijie Xu, Shanyu Rong, Yuheng Ji, Cheng Chi, Xiansheng Chen, Qiongyu Zhang, Zhongxia Zhao, Pengwei Wang, Zhongyuan Wang, Shanghang Zhang
- [HiF-VLA: Hindsight, Insight and Foresight through Motion Representation for Vision-Language-Action Models](https://arxiv.org/abs/2512.09928)
  - Minghui Lin, Pengxiang Ding, Shu Wang, Zifeng Zhuang, Yang Liu, Xinyang Tong, Wenxuan Song, Shangke Lyu, Siteng Huang, Donglin Wang
- [LoLA: Long Horizon Latent Action Learning for General Robot Manipulation](https://arxiv.org/abs/2512.20166)
  - Xiaofan Wang, Xingyu Gao, Jianlong Fu, Zuolei Li, Dean Fortier, Galen Mullins, Andrey Kolobov, Baining Guo
- [Affordance Field Intervention: Enabling VLAs to Escape Memory Traps in Robotic Manipulation](https://arxiv.org/abs/2512.07472)
  - Siyu Xu, Zijian Wang, Yunke Wang, Chenghao Xia, Tao Huang, Chang Xu
- [Rethinking Progression of Memory State in Robotic Manipulation: An Object-Centric Perspective](https://arxiv.org/abs/2511.11478)
  - Nhat Chung, Taisei Hanyu, Toan Nguyen, Huy Le, Frederick Bumgarner, Duy Minh Ho Nguyen, Khoa Vo, Kashu Yamazaki, Chase Rainwater, Tung Kieu, Anh Nguyen, Ngan Le
- [HAMLET: Switch your Vision-Language-Action Model into a History-Aware Policy](https://arxiv.org/abs/2510.00695)
  - Myungkyu Koo, Daewon Choi, Taeyoung Kim, Kyungmin Lee, Changyeon Kim, Younggyo Seo, Jinwoo Shin
- [LoHoVLA: A Unified Vision-Language-Action Model for Long-Horizon Embodied Tasks](https://arxiv.org/abs/2506.00411)
  - Yi Yang, Jiaxuan Sun, Siqi Kou, Yihan Wang, Zhijie Deng
- [RoboHiMan: A Hierarchical Evaluation Paradigm for Compositional Generalization in Long-Horizon Manipulation](https://arxiv.org/abs/2510.13149)
  - Yangtao Chen, Zixuan Chen, Nga Teng Chan, Junting Chen, Junhui Yin, Jieqi Shi, Yang Gao, Yong-Lu Li, Jing Huo
- [Spatial Traces: Enhancing VLA Models with Spatial-Temporal Understanding](https://arxiv.org/abs/2508.09032)
  - Maxim A. Patratskiy, Alexey K. Kovalev, Aleksandr I. Panov
- [KV-Efficient VLA: A Method to Speed up Vision Language Models with RNN-Gated Chunked KV Cache](https://arxiv.org/abs/2509.21354)
  - Wanshun Xu, Long Zhuang, Lianlei Shan
- [F1: A Vision-Language-Action Model Bridging Understanding and Generation to Actions](https://arxiv.org/abs/2509.06951)
  - Qi Lv, Weijie Kong, Hao Li, Jia Zeng, Zherui Qiu, Delin Qu, Haoming Song, Qizhi Chen, Xiang Deng, Jiangmiao Pang
- [Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation](https://arxiv.org/abs/2508.19958)
  - Yiguo Fan, Pengxiang Ding, Shuanghao Bai, Xinyang Tong, Yuyang Zhu, Hongchao Lu, Fengqi Dai, Wei Zhao, Yang Liu, Siteng Huang, Zhaoxin Fan, Badong Chen, Donglin Wang
- [RoboMemory: A Brain-inspired Multi-memory Agentic Framework for Interactive Environmental Learning in Physical Embodied Systems](https://arxiv.org/abs/2508.01415)
  - Mingcong Lei, Honghao Cai, Zezhou Cui, Liangchen Tan, Junkun Hong, Gehan Hu, Shuangyu Zhu, Yimou Wu, Shaohan Jiang, Ge Wang, Yuyuan Yang, Junyuan Tan, Zhenglin Wan, Zhen Li, Shuguang Cui, Yiming Zhao, Yatong Han
- [DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping](https://arxiv.org/abs/2502.20900)
  - Yifan Zhong, Xuchuan Huang, Ruochong Li, Ceyao Zhang, Zhang Chen, Tianrui Guan, Fanlian Zeng, Ka Num Lui, Yuyao Ye, Yitao Liang, Yaodong Yang, Yuanpei Chen
- [RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration](https://arxiv.org/abs/2505.03673)
  - Huajie Tan, Xiaoshuai Hao, Cheng Chi, Minglan Lin, Yaoxu Lyu, Mingyu Cao, Dong Liang, Zhuo Chen, Mengsi Lyu, Cheng Peng, Chenrui He, Yulong Ao, Yonghua Lin, Pengwei Wang, Zhongyuan Wang, Shanghang Zhang
- [EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos](https://arxiv.org/abs/2507.12440)
  - Ruihan Yang, Qinxi Yu, Yecheng Wu, Rui Yan, Borui Li, An-Chieh Cheng, Xueyan Zou, Yunhao Fang, Xuxin Cheng, Ri-Zhao Qiu, Hongxu Yin, Sifei Liu, Song Han, Yao Lu, Xiaolong Wang
- [CycleManip: Enabling Cyclic Task Manipulation via Effective Historical Perception and Understanding](https://arxiv.org/abs/2512.01022)
  - Yi-Lin Wei, Haoran Liao, Yuhao Lin, Pengyue Wang, Zhizhao Liang, Guiliang Liu, Wei-Shi Zheng
- [History-Aware Visuomotor Policy Learning via Point Tracking](https://arxiv.org/abs/2509.17141)
  - Jingjing Chen, Hongjie Fang, Chenxi Wang, Shiquan Wang, Cewu Lu
- [MemER: Scaling Up Memory for Robot Control via Experience Retrieval](https://arxiv.org/abs/2510.20328)
  - Ajay Sridhar, Jennifer Pan, Satvik Sharma, Chelsea Finn
- [MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation](https://arxiv.org/abs/2508.19236)
  - Hao Shi, Bin Xie, Yingfei Liu, Lin Sun, Fengrong Liu, Tiancai Wang, Erjin Zhou, Haoqiang Fan, Xiangyu Zhang, Gao Huang
- [Memory, Benchmark & Robots: A Benchmark for Solving Complex Tasks with Reinforcement Learning](https://arxiv.org/abs/2502.10550)
  - Egor Cherepanov, Nikita Kachaev, Alexey K. Kovalev, Aleksandr I. Panov
- [MAP-VLA: Memory-Augmented Prompting for Vision-Language-Action Model in Robotic Manipulation](https://arxiv.org/abs/2511.09516)
  - Runhao Li, Wenkai Guo, Zhenyu Wu, Changyuan Wang, Haoyuan Deng, Zhenyu Weng, Yap-Peng Tan, Ziwei Wang
- [Rethinking Progression of Memory State in Robotic Manipulation: An Object-Centric Perspective](https://arxiv.org/abs/2511.11478)
  - Nhat Chung, Taisei Hanyu, Toan Nguyen, Huy Le, Frederick Bumgarner, Duy Minh Ho Nguyen, Khoa Vo, Kashu Yamazaki, Chase Rainwater, Tung Kieu, Anh Nguyen, Ngan Le
- [MVP: Memory-enhanced Vision-Language-Action Policy with Feedback Learning](https://openreview.net/forum?id=Yz2DnYBJXd)
  - Anonymous authors. Paper under double-blind review
- [Towards Fast, Memory-based and Data-Efficient Vision-Language Policy](https://arxiv.org/abs/2503.10322)
  - Haoxuan Li, Sixu Yan, Yuhan Li, Xinggang Wang
- [EvoVLA: Self-Evolving Vision-Language-Action Model](https://arxiv.org/abs/2511.16166)
  - Zeting Liu, Zida Yang, Zeyu Zhang, Hao Tang
- [EchoVLA: Robotic Vision-Language-Action Model with Synergistic Declarative Memory for Mobile Manipulation](https://arxiv.org/abs/2511.18112)
  - Min Lin, Xiwen Liang, Bingqian Lin, Liu Jingzhi, Zijian Jiao, Kehan Li, Yuhan Ma, Yuecheng Liu, Shen Zhao, Yuzheng Zhuang, Xiaodan Liang
- [Mixture of Horizons in Action Chunking](https://arxiv.org/abs/2511.19433)
  - Dong Jing, Gang Wang, Jiaqi Liu, Weiliang Tang, Zelong Sun, Yunchao Yao, Zhenyu Wei, Yunhui Liu, Zhiwu Lu, Mingyu Ding
- [AVA-VLA: Improving Vision-Language-Action models with Active Visual Attention](https://arxiv.org/abs/2511.18960)
  - Lei Xiao, Jifeng Li, Juntao Gao, Feiyang Ye, Yan Jin, Jingjing Qian, Jing Zhang, Yong Wu, Xiaoyuan Yu
- [Vision-Language Memory for Spatial Reasoning](https://arxiv.org/abs/2511.20644)
  - Zuntao Liu, Yi Du, Taimeng Fu, Shaoshu Su, Cherie Ho, Chen Wang
- [CronusVLA: Towards Efficient and Robust Manipulation via Multi-Frame Vision-Language-Action Modeling](https://arxiv.org/abs/2506.19816)
  - Hao Li, Shuai Yang, Yilun Chen, Xinyi Chen, Xiaoda Yang, Yang Tian, Hanqing Wang, Tai Wang, Dahua Lin, Feng Zhao, Jiangmiao Pang
- [ContextVLA: Vision-Language-Action Model with Amortized Multi-Frame Context](https://arxiv.org/abs/2510.04246)
  - Huiwon Jang, Sihyun Yu, Heeseung Kwon, Hojin Jeon, Younggyo Seo, Jinwoo Shin
- [GR-RL: Going Dexterous and Precise for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2512.01801)
  - Yunfei Li, Xiao Ma, Jiafeng Xu, Yu Cui, Zhongren Cui, Zhigang Han, Liqun Huang, Tao Kong, Yuxiao Liu, Hao Niu, Wanli Peng, Jingchao Qiao, Zeyu Ren, Haixin Shi, Zhi Su, Jiawen Tian, Yuyang Xiao, Shenyu Zhang, Liwei Zheng, Hang Li, Yonghui Wu
- [CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks](https://arxiv.org/abs/2112.03227)
  - Oier Mees, Lukas Hermann, Erick Rosete-Beas, Wolfram Burgard

## Papers | VLM + memory
### 2025
- [VideoMem: Enhancing Ultra-Long Video Understanding via Adaptive Memory Management](https://arxiv.org/abs/2512.04540)
  - Hongbo Jin, Qingyuan Wang, Wenhao Zhang, Yang Liu, Sijie Cheng
- [Vision-Language Memory for Spatial Reasoning](https://arxiv.org/abs/2511.20644)
  - Zuntao Liu, Yi Du, Taimeng Fu, Shaoshu Su, Cherie Ho, Chen Wang
