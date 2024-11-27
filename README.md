## PPDA
This repository contains the code and data for our paper "PPDA: A Privacy Preserving Framework for Distributed Graph Learning," published at ICONIP 2024.

## Abstract
Graph-based learning finds wide application in social networks, robotics, communication, and medicine. However, datasets often contain sensitive information, hindering their use in graph learning applications due to privacy concerns. Existing privacy-preserving methods pre-process the data to extract user-side features, and only these features are used for subsequent learning. Unfortunately, these methods are vulnerable to adversarial attacks to infer private attributes. We present a novel privacy-respecting framework for distributed graph learning and graph-based machine learning. In order to perform graph learning and other downstream tasks on the server side, this framework aims to learn features as well as distances without requiring actual features while preserving the original structural properties of the raw data. The proposed framework is quite generic and highly adaptable. We demonstrate the utility of the Euclidean space, but it can be applied with any existing method of distance approximation and graph learning for the relevant spaces. Through extensive experimentation on both synthetic and real datasets, we demonstrate the efficacy of the framework in terms of comparing the results obtained without data sharing to those obtained with data sharing as a benchmark. This is, to our knowledge, the first privacy-preserving distributed graph learning framework.

## Highlights
Our framework achieves the following objectives: ​
(1) Secure distance learning: Achieve pairwise distance learning without disclosing features, ​
(2) Graph learning: Leverage this secure distance information to construct graphs, and ​
(3) Graph embedding: Generate graph embeddings for advanced machine learning tasks.​

## Installation Instructions
Instructions coming soon...

## Usage
Guidelines and examples will be provided soon...

## Datasets
Details and links to datasets will be added shortly.

## Results
Results, including figures, tables, and key findings, will be shared here.

## Citation
If you use this repository in your research, please cite our work published at ICONIP'24.
