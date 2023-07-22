This repository contains the Jupyter notebooks and utility script for the paper titled "Kernel Matrix Approximation on Class-Imbalanced Data with an Application to Scientific Simulation."

Abstract


Generating low-rank approximations of kernel matrices that arise in nonlinear machine learning techniques holds the potential to significantly alleviate the memory and computational burdens. A compelling approach centers on finding a concise set of exemplars or landmarks to reduce the number of similarity measure evaluations from quadratic to linear concerning the data size. However, a key challenge is to regulate tradeoffs between the quality of landmarks and resource consumption. Despite the volume of research in this area, current understanding is limited regarding the performance of landmark selection techniques in the presence of class-imbalanced data sets that are becoming increasingly prevalent in many applications. Hence, this paper provides a comprehensive empirical investigation using several real-world imbalanced data sets, including scientific data, by evaluating the quality of approximate low-rank decompositions and examining their influence on the accuracy of downstream tasks. Furthermore, we present a new landmark selection technique called Distance-based Importance Sampling and Clustering (DISC), in which the relative importance scores are computed for improving accuracy-efficiency tradeoffs compared to existing works that range from probabilistic sampling to clustering methods. The proposed landmark selection method follows a coarse-to-fine strategy to capture the intrinsic structure of complex data sets, allowing us to substantially reduce the computational complexity and memory footprint with minimal loss in accuracy.

Notebooks
DISC_Fig1_C.ipynb: Jupyter notebook containing the code for generating Figure 1 and its subplots in the paper.

Ozon_C.ipynb: Jupyter notebook demonstrating the application of the proposed landmark selection technique on the "Ozone Level" data set.

WineQuality_C.ipynb: Jupyter notebook demonstrating the application of the proposed landmark selection technique on the "Wine Quality" data set.

Utility Script
utils.py: Python script containing utility functions used in the notebooks for landmark selection and low-rank approximation of kernel matrices.

Citation
If you find this work useful for your research, please consider citing:

Hajibabaee, P., Pourkamali-Anaraki, F., & Hariri-Ardebili, M. A. (2021). Kernel matrix approximation on class-imbalanced data with an application to scientific simulation. IEEE Access, 9, 83579-83591.

Paper Link:
https://ieeexplore.ieee.org/abstract/document/9449889
