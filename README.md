# Awesome Streaming Anomaly Detection

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/your-username/your-repo/graphs/commit-activity)

A curated list of taxonomy and resources for **Online Anomaly Detection (OAD)** and **Online Drift Anomaly Detection (ODAD)**. 

This repository organizes papers by year and details their specific taxonomies, including label availability, concept drift handling, and computational complexity.

## 📖 Taxonomy Legend
* **OAD:** Online Anomaly Detection
* **ODAD:** Online Drift Anomaly Detection
* **Label:** Supervised, Unsupervised, Semi-Supervised
* **Drift:** Explicit vs Implicit detection methods

## 📌 Table of Contents
- [2025 Papers](#2025-papers)
- [2024 Papers](#2024-papers)
- [2023 Papers](#2023-papers)
- [2022 Papers](#2022-papers)
- [2021 Papers](#2021-papers)

---

## 2025 Papers

| Model | Paper Title | Venue | Type | Label | Drift Handling | Complexity (Time/Mem) |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: |
| **SAD** | [A Novel Sparse Active Online Learning Framework...](link_to_pdf) | IJCAI | OAD | Supervised | No detection | No / No |
| **EDOBS** | [An efficient distance based outlier detection...](link_to_pdf) | Cluster Comp. | OAD | Unsupervised | No detection | Yes / Yes |
| **ADA-ADF** | [An unsupervised framework for drift-aware...](link_to_pdf) | App. Soft Comp. | ODAD | Unsupervised | Distribution-based | No / No |
| **CyberCScope** | [CyberCScope: Mining Skewed Tensor Streams...](link_to_pdf) | WWW | OAD | Unsupervised | Error-based | No / No |
| **DFAS** | [Density-aware and Cluster-based Federated...](link_to_pdf) | WSDM | OAD | Semi-Sup | No detection | Yes / No |
| **ESOD** | [ESOD: An Edge Streaming Data Outlier Detection...](link_to_pdf) | IoT-J | OAD | Unsupervised | Error-based | Yes / Yes |
| **INQMAD** | [INQMAD: incremental streaming anomaly detection...](link_to_pdf) | Neural Comp. | OAD | Unsupervised | Distribution-based | Yes / Yes |
| **AdaESST** | [Online Adaptive Anomaly Detection in Networked...](link_to_pdf) | IoT-J | OAD | Unsupervised | Distribution-based | No / No |
| **OODOFS** | [Online Outlier Detection in Open Feature Spaces](link_to_pdf) | TKDE | ODAD | Semi-Sup | Error-based | No / No |
| **Sirloin** | [Streaming Time Series Subsequence Anomaly Detection](link_to_pdf) | VLDB | OAD | Unsupervised | No detection | No / No |

## 2024 Papers

| Model | Paper Title | Venue | Type | Label | Drift Handling | Update Method |
| :--- | :--- | :---: | :---: | :---: | :--- | :---: |
| **IEDSEM** | An Intelligent Edge Dual-Structure Ensemble Method... | IoT-J | ODAD | Supervised | Error-based | Adaptive |
| **CDAO-LSTM** | An Online Anomaly Detection Algorithm with Adaptive... | CISCE | ODAD | Unsupervised | Error-based | Adaptive |
| **ASOD** | ASOD: an adaptive stream outlier detection method... | J. Cloud Comp | OAD | Unsupervised | Distribution-based | Adaptive |
| **AADS** | Autonomous anomaly detection for streaming data | KBS | OAD | Unsupervised | No detection | Incremental |
| **METER** | METER: A Dynamic Concept Adaptation Framework... | VLDB | ODAD | Unsupervised | Distribution-based | Adaptive |
| **VAE4AS** | Unsupervised Incremental Learning with Dual Concept... | IJCNN | ODAD | Unsupervised | Distribution-based | Adaptive |

## 2023 Papers

| Model | Paper Title | Venue | Type | Label | Drift Handling |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **ADTCD** | ADTCD: An Adaptive Anomaly Detection Approach... | IoT-J | ODAD | Unsupervised | Error-based |
| **GC-ADS** | Anomaly detection for streaming data based on grid... | Info. Sciences | OAD | Unsupervised | No detection |
| **ASTREAM** | ASTREAM: Data-Stream-Driven Scalable Anomaly... | TNSE | OAD | Unsupervised | Distribution-based |
| **strAEm++D** | Autoencoder-based Anomaly Detection in Streaming... | IJCNN | ODAD | Unsupervised | Distribution-based |
| **BWOAIF** | Bilateral-Weighted Online Adaptive Isolation Forest... | Stat. Analysis | OAD | Unsupervised | Error-based |
| **DBCatcher** | DBCatcher: A Cloud Database Online Anomaly... | ICDE | OAD | Semi-Sup | Error-based |
| **Zhang et al.** | Online Forecasting Based Anomaly Detection For... | Big Data | OAD | Unsupervised | No detection |

## 2022 Papers

| Model | Paper Title | Venue | Label | Drift Tech | Update |
| :--- | :--- | :---: | :---: | :--- | :--- |
| **ARCUS** | Adaptive Model Pooling for Online Deep Anomaly... | KDD | Unsupervised | Error-based | Adaptive |
| **ADSketch** | Adaptive performance anomaly detection for online... | ICSE | Unsupervised | Distribution-based | Adaptive |
| **Belacel** | An LSTM Encoder-Decoder Approach for Unsupervised... | Big Data | Unsupervised | Error-based | Adaptive |
| **Odiathevar** | An Online Offline Framework for Anomaly Scoring... | TKDE | Semi-Sup | Distribution-based | Adaptive |
| **AD-LTI** | Developing an Unsupervised Real-Time Anomaly... | TKDE | Unsupervised | No detection | Incremental |
| **iLDCBOF** | Efficient density and cluster based incremental... | Info. Sci | Unsupervised | No detection | Incremental |
| **EADNSD** | Evolving anomaly detection for network streaming... | Info. Sci | Unsupervised | No detection | Incremental |
| **Wahab** | Intrusion Detection in the IoT Under Data... | IoT-J | Supervised | Distribution-based | Adaptive |
| **IPMOD** | IPMOD: An efficient outlier detection model... | Expert Sys. | Unsupervised | No detection | Incremental |
| **MemStream** | MemStream: Memory-Based Streaming Anomaly... | WWW | Unsupervised | No detection | Incremental |
| **RCAD** | RCAD: Real-time Collaborative Anomaly Detection... | KDD | Unsupervised | No detection | Adaptive |
| **SCAPA** | Real time anomaly detection and categorisation | Stat & Comp | Unsupervised | No detection | Incremental |
| **Abououf** | Self-Supervised Online and Lightweight Anomaly... | IoT-J | Semi-Sup | No detection | Incremental |
| **Uni-AD** | Share or Not Share? Towards the Practicability... | ISSRE | Unsupervised | No detection | No update |
| **Hassan** | Towards a deep learning-based outlier detection... | Big Data | Supervised | No detection | No update |
| **OeSNN** | Unsupervised anomaly detection in multivariate... | ML-Springer | Unsupervised | No detection | Incremental |
| **DenStream** | Unsupervised online anomaly detection in SDN... | Expert Sys. | Unsupervised | No detection | Incremental |

## 2021 Papers

| Model | Paper Title | Venue | Label | Complexity |
| :--- | :--- | :---: | :---: | :--- |
| **CODS** | A GPU Algorithm for Detecting Contextual Outliers... | Big Data | Unsupervised | Retrain |
| **ELOF** | ELOF: fast and memory-efficient anomaly detection... | Soft Comp. | Unsupervised | Incremental |
| **MStream** | MStream: Fast Anomaly Detection in Multi-Aspect... | WWW | Unsupervised | No update |
| **MDUAL** | Multiple Dynamic Outlier-Detection from a Data... | SIGMOD | Unsupervised | Incremental |
| **OHODIN** | OHODIN – Online Anomaly Detection for Data Streams | ACSOS-C | Unsupervised | No update |
| **Kurt** | Real-Time Nonparametric Anomaly Detection... | TPAMI | Unsupervised | No update |
| **SAND** | SAND: streaming subsequence anomaly detection | VLDB | Unsupervised | Incremental |
| **SHC** | Statistical hierarchical clustering algorithm... | ML-Springer | Unsupervised | Adaptive |

---
## Contributing
Contributions are welcome! Please submit a pull request to add new papers.
