# Awesome Online Anomaly Detection Models in Complex Data Stream 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/your-username/your-repo/graphs/commit-activity)

A curated list of taxonomy and resources for **Online Anomaly Detection (OAD)** and **Online Deep Anomaly Detection (ODAD)**.

## 📌 Table of Contents
- [ODAD Papers](#ODAD-Papers)
- [OAD Papers](#OAD-papers)
- [2025 Papers](#2025-papers)
- [2024 Papers](#2024-papers)
- [2023 Papers](#2023-papers)
- [2022 Papers](#2022-papers)
- [2021 Papers](#2021-papers)
- [📂 View Detailed Dataset & Feature Information](./Dataset.md)

---
<img width="903" height="1134" alt="image" src="https://github.com/user-attachments/assets/ceed3369-5b8c-43ea-a6ce-ebb532125009" />

---
# ODAD Papers

## 2025 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **ADA-ADF** | An unsupervised framework for drift-aware anomaly detection in streaming time series | Applied Soft Computing - Elsevier | ODAD | Generative Model (VAE) | Distribution-based | Unsupervised | Window | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://www.sciencedirect.com/science/article/pii/S1568494625012165?via%3Dihub) |
| **OODOFS** | Online Outlier Detection in Open Feature Spaces | TKDE (IEEE Transactions on Knowledge and Data Engineering) | ODAD | Approximation | Error-based | Semi-Supervised | Timestamp | Instance | Distance | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/document/11117179) \| [💻Code](https://github.com/X1aoLian/OODOFS) |

## 2024 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **IEDSEM** | An Intelligent Edge Dual-Structure Ensemble Method for Data Stream Detection and Releasing | IoT-J (IEEE Internet of Things Journal) | ODAD | Feature Selection | Error-based | Supervised | Window | Global Point | Likelihood | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/10153419) |
| **CDAO-LSTM** | An Online Anomaly Detection Algorithm with Adaptive Concept Drift | CISCE | ODAD | AE | Error-based | Unsupervised | Timestamp | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/10653010) |
| **ASOD** | ASOD: an adaptive stream outlier detection method using online strategy | Journal of Cloud Computing | ODAD | Generative Model (Gaussian) | Distribution-based | Unsupervised | Timestamp | Contextual | Distance | Adaptive | [📄 Paper](https://link.springer.com/article/10.1186/s13677-024-00682-0) |
| **METER** | METER: A Dynamic Concept Adaptation Framework for Online Anomaly Detection | VLDB (Very Large Database) | ODAD | AE | Distribution-based | Unsupervised | Timestamp | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://dl.acm.org/doi/abs/10.14778/3636218.3636233) \| [💻Code](https://github.com/zjiaqi725/METER)  |
| **VAE4AS** | Unsupervised Incremental Learning with Dual Concept Drift Detection for Identifying Anomalous Sequences | IJCNN | ODAD | AE | Distribution-based | Unsupervised | Window | Group (Collective) | Reconstruction Error | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/10649991) |

## 2023 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **ADTCD** | ADTCD: An Adaptive Anomaly Detection Approach Toward Concept Drift in IoT | IoT-J (IEEE Internet of Things Journal) | ODAD | AE | Error-based | Unsupervised | Batch | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/10097858) |
| **strAEm++D** | Autoencoder-based Anomaly Detection in Streaming Data with Incremental Learning and Concept Drift Adaptation | IJCNN | ODAD | AE | Distribution-based | Unsupervised | Timestamp | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/10191328) |

## 2022 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **RCAD** | RCAD: Real-time Collaborative Anomaly Detection System for Mobile Broadband Networks | KDD | ODAD | Encoder | No detection | Unsupervised | Timestamp | Local point | Likelihood | Adaptive | [📄 Paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539097) \| [💻Code](https://github.com/azza8903/HTM-MODEL_EXCHANGE) |
| **OeSNN** | Unsupervised anomaly detection in multivariate time series with online evolving spiking neural networks | Machine Learning - Springer | ODAD | Generative Model (Gaussian) | No detection | Unsupervised | Timestamp | Contextual | Likelihood | Incremental | [📄 Paper](https://link.springer.com/article/10.1007/s10994-022-06129-4) |
| **Hassan et al.** | Towards a deep learning-based outlier detection approach in the context of streaming data | Journal of Big Data - Springer | ODAD | Projection -> Hidden Layers (DNN) | No detection | Supervised | Window | Instance | Likelihood | No update | [📄 Paper](https://link.springer.com/article/10.1186/s40537-022-00670-8) |
| **Uni-AD** | Share or Not Share? Towards the Practicability of Deep Models for Unsupervised Anomaly Detection in Modern Online Systems | ISSRE | ODAD | Generative Model (Transformer) | No detection | Unsupervised | Window | Contextual | Reconstruction Error | No update | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9978953) |
| **Abououf et al.** | Self-Supervised Online and Lightweight Anomaly and Event Detection for IoT Devices | IoT-J (IEEE Internet of Things Journal) | ODAD | Generative Model (AE) | No detection | Semi-Supervised | Window | Local point, Global Group | Reconstruction Error | Incremental | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9848787) |
| **Belacel et al.** | An LSTM Encoder-Decoder Approach for Unsupervised Online Anomaly Detection in Machine Learning Packages for Streaming Data | Big Data (IEEE) | ODAD | AE | Error-based | Unsupervised | Window | Contextual | Reconstruction Error | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/10020872) \| [💻Code](https://github.com/redsofa/streaming_anomaly_detection)|
| **Wahab** | Intrusion Detection in the IoT Under Data and Concept Drifts: Online Deep Learning Approach | IoT-J (IEEE Internet of Things Journal) | ODAD | PCA | Distribution-based | Supervised | Window | Contextual | Density | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9755949) |
| **AD-LTI** | Developing an Unsupervised Real-Time Anomaly Detection Scheme for Time Series With Multi-Seasonality | TKDE (IEEE) | ODAD | Approximation | No detection | Unsupervised | Timestamp | Instance | Distance | Incremental | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9247440) |
| **Odiathevar et al.** | An Online Offline Framework for Anomaly Scoring and Detecting New Traffic in Network Streams | TKDE (IEEE) | ODAD | AE | Distribution-based | Semi-Supervised | Timestamp | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://ieeexplore.ieee.org/abstract/document/9319564) |
| **ARCUS** | Adaptive Model Pooling for Online Deep Anomaly Detection from a Complex Evolving Data Stream | KDD | ODAD | AE | Error-based | Unsupervised | Batch | Instance | Reconstruction Error | Adaptive | [📄 Paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539348) \| [💻Code](https://github.com/kaist-dmlab/ARCUS) |

## 2021 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Kurt et al.** | Real-Time Nonparametric Anomaly Detection in High-Dimensional Settings | TPAMI (IEEE) | ODAD | Approximation | No detection | Unsupervised | Timestamp | Group | Likelihood | Incremental | [📄 Paper](#) |

<br/>

# OAD Papers

## 2025 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **SAD** | A Novel Sparse Active Online Learning Framework for Fast and Accurate Streaming Anomaly Detection Over Data Streams | IJCAI | OAD | Approximation | No detection | Supervised | Window | Instance | Reconstruction Error | Incremental | [📄 Paper](#) |
| **CyberCScope** | CyberCScope: Mining Skewed Tensor Streams and Online Anomaly Detection in Cybersecurity Systems | WWW (The Web Conference) | OAD | Approximation | Error-based | Unsupervised | Timestamp | Group | Likelihood | Adaptive | [📄 Paper](#) |
| **DFAS** | Density-aware and Cluster-based Federated Anomaly Detection on Data Streams | WSDM | OAD | Approximation | No detection | Semi-Supervised | Timestamp | Instance | Density (NN-based) | Incremental | [📄 Paper](#) |
| **ESOD** | ESOD: An Edge Streaming Data Outlier Detection Framework for IoT Platforms | IoT-J (IEEE Internet of Things Journal) | OAD | Approximation | Error-based | Unsupervised | Window | Instance | Likelihood | Incremental | [📄 Paper](#) |
| **INQMAD** | INQMAD: incremental streaming anomaly detection with density matrices, quantum measurement, and density estimation | Neural Computing and Applications - Springer | OAD | Approximation | Distribution-based | Unsupervised | Timestamp | Instance | Likelihood | Adaptive | [📄 Paper](#) |
| **AdaESST** | Online Adaptive Anomaly Detection in Networked Electrical Machines by Adaptive Enveloped Singular Spectrum Transformation | IoT-J (IEEE Internet of Things Journal) | OAD | Approximation | Distribution-based | Unsupervised | Window | Instance | Distance | Adaptive | [📄 Paper](#) |
| **Sirloin** | Streaming Time Series Subsequence Anomaly Detection: A Glance and Focus Approach | VLDB (Very Large Database) | OAD | Approximation | No detection | Unsupervised | Window | Group | Distance (NN-based) | Adaptive | [📄 Paper](https://dl.acm.org/doi/10.14778/3725688.3725714) \| [💻 Code](https://github.com/Wangwenjing1996/Sirloin)  |
| **EDOBS** | An efficient distance based outlier detection method for batch-processed data streams | Cluster Computing - Springer | OAD | Approximation | No detection | Unsupervised | Batch | Contextual Collective | Distance | Incremental | [📄 Paper](#) |

## 2024 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **AADS** | Autonomous anomaly detection for streaming data | KBS (Knowledge Based Systems) | OAD | Approximation | No detection | Unsupervised | Timestamp | Group | Density (NN-based) | Incremental | [📄 Paper](#) |

## 2023 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **BWOAIF** | Bilateral-Weighted Online Adaptive Isolation Forest for anomaly detection in streaming data | Statistical Analysis and Data Mining | OAD | Approximation | Error-based | Unsupervised | Batch | Instance | Tree-path length | Adaptive | [📄 Paper](#) |
| **DBCatcher** | DBCatcher: A Cloud Database Online Anomaly Detection System based on Indicator Correlation | ICDE | OAD | Feature Selection | Error-based | Semi-Supervised | Instance | Contextual | Similarity/Correlation | Adaptive | [📄 Paper](#) |
| **Zhang et al.** | Online Forecasting Based Anomaly Detection For Monitoring Large Scale Streaming Data | Big Data (IEEE) | OAD | Approximation | No detection | Unsupervised | Instance | Contextual | Likelihood | Incremental | [📄 Paper](#) |
| **ASTREAM** | ASTREAM: Data-Stream-Driven Scalable Anomaly Detection With Accuracy Guarantee in IIoT Environment | TNSE (IEEE) | OAD | PCA | Distribution-based | Unsupervised | Window | Instance | Frequency | Adaptive | [📄 Paper](#) |
| **GC-ADS** | Anomaly detection for streaming data based on grid-clustering and Gaussian distribution | Information Sciences | OAD | Grid | No detection | Unsupervised | Window | Instance | Distance | Incremental | [📄 Paper](#) |

## 2022 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **ADSketch** | Adaptive performance anomaly detection for online service systems via pattern sketching | ICSE | OAD | Approximation | Distribution-based | Unsupervised | Window | Group | Distance (NN-based) | Adaptive | [📄 Paper](#) |
| **iLDCBOF** | Efficient density and cluster based incremental outlier detection in data streams | Information Sciences | OAD | Approximation | No detection | Unsupervised | Instance | Instance, Group | Density (NN-based) | Incremental | [📄 Paper](#) |
| **EADNSD** | Evolving anomaly detection for network streaming data | Information Sciences | OAD | Approximation | No detection | Unsupervised | Batch | Instance, Group | Density (NN-based) | Incremental | [📄 Paper](#) |
| **IPMOD** | IPMOD: An efficient outlier detection model for high-dimensional medical data streams | Expert Systems with Applications | OAD | Feature Selection | No detection | Unsupervised | Window | Instance | Distance | Incremental | [📄 Paper](#) |
| **MemStream** | MemStream: Memory-Based Streaming Anomaly Detection | WWW (The Web Conference) | ODAD | Projection: DAE | Error-based | Unsupervised | Timestamp | Instance | Distance | Adaptive | [📄 Paper](#) |
| **SCAPA** | Real time anomaly detection and categorisation | Statistics and Computing - Springer | OAD | Approximation | No detection | Unsupervised | Timestamp | Instance, Group | Likelihood | Incremental | [📄 Paper](#) |
| **DenStream** | Unsupervised online anomaly detection in Software Defined Network environments | Expert Systems with Applications | OAD |  | No detection | Unsupervised | Instance | Group | Density (NN-based) | Incremental | [📄 Paper](#) |

## 2021 Papers

| Model | Paper Title | Venue | General Type | Base Model | Concept Drift Detection | Availability of Label | Streaming Method | Target Anomaly | Anomaly Score | Model Update | Resources |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **CODS** | A GPU Algorithm for Detecting Contextual Outliers in Multiple Concurrent Data Streams | Big Data (IEEE) | OAD | PCA | No detection | Unsupervised | Window | Contextual | Density (NN-based) | Retrain | [📄 Paper](#) |
| **ELOF** | ELOF: fast and memory-efficient anomaly detection algorithm in data streams | Soft Computing - Springer | OAD | Approximation | No detection | Unsupervised | Window | Instance | Density (NN-based) | Incremental | [📄 Paper](#) |
| **MStream** | MStream: Fast Anomaly Detection in Multi-Aspect Streams | WWW (The Web Conference) | OAD | Approximation | No detection | Unsupervised | Timestamp | Group (Collective) | Frequency | No update | [📄 Paper](#) |
| **MDUAL** | Multiple Dynamic Outlier-Detection from a Data Stream by Exploiting Duality of Data and Queries | SIGMOD | OAD | Approximation | No detection | Unsupervised | Window | Contextual | Distance | Incremental | [📄 Paper](#) |
| **OHODIN** | OHODIN Online Anomaly Detection for Data Streams | ACSOS-C | OAD |  | No detection | Unsupervised | Timestamp | Instance | Distance | No update | [📄 Paper](#) |
| **SAND** | SAND: streaming subsequence anomaly detection | VLDB (Very Large Database) | OAD | Approximation | No detection | Unsupervised | Batch | Group | Distance (NN-based) | Incremental | [📄 Paper](#) |
| **SHC** | Statistical hierarchical clustering algorithm for outlier detection in evolving data streams | Machine Learning - Springer | OAD | Approximation | Distribution-based | Unsupervised | Timestamp | Instance | Distance | Adaptive | [📄 Paper](#) |
