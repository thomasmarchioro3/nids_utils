# Unsupervised ML NIDS

## 2022-2025

#### Alotaibi F, Maffeis S. Mateen: Adaptive Ensemble Learning for Network Anomaly Detection. RAID. 2024. ([link](https://dl.acm.org/doi/pdf/10.1145/3678890.3678901))


#### Dong Y, Li Q, Wu K, Li R, Zhao D, Tyson G, Peng J, Jiang Y, Xia S, Xu M. {HorusEye}: A realtime {IoT} malicious traffic detection framework using programmable switches. USENIX Security. 2023. ([link](https://www.usenix.org/system/files/usenixsecurity23-dong-yutao.pdf))


Models:
- [Mateen](https://github.com/ICL-ml4csec/Mateen/) (ensemble of autoencoders)
- [HorusEye](https://github.com/vicTorKd/HorusEye) (isolation forest + autoencoder)

## 2020-2022

#### Song Y, Hyun S, Cheong YG. Analysis of autoencoders for network intrusion detection. Sensors. 2021. ([link](https://pdfs.semanticscholar.org/5867/0660258b91bb8e3bbc84a66db20c45a9d0d4.pdf))

Models:
- Autoencoder

## 2000-2019

#### Mirsky Y, Doitshman T, Elovici Y, Shabtai A. Kitsune: An Ensemble of Autoencoders for Online Network Intrusion Detection. machine learning. 2018 ([link](https://arxiv.org/pdf/1802.09089))

Models:
- [KitNET](https://github.com/ymirsky/Kitsune-py) (ensemble of autoencoders)

#### Nisioti A, Mylonas A, Yoo PD, Katos V. From intrusion detection to attacker attribution: A comprehensive survey of unsupervised methods. IEEE Communications Surveys & Tutorials. 2018 ([link](https://www.research.herts.ac.uk/ws/files/22864679/08410366.pdf))

Models:
- Clustering algorithms
    - [K-means](https://scikit-learn.org/1.5/modules/generated/sklearn.cluster.KMeans.html)
    - [DBSCAN](https://scikit-learn.org/1.5/modules/generated/sklearn.cluster.DBSCAN.html)
    - Other
- Outlier detectors
    - ROS (no open source implementation, does not seem to be used in practice)