### **GeneKAN: A Gene Regulatory Network Inference Method Based on Multiscale Kolmogorov-Arnold-Network-Enhanced Graph Convolutional Kernels**

##### Overview

we propose GeneKAN, a new method that integrates a kernel-based graph convolutional network, termed Graph Convolution with Kernel Methods (GCKM), to infer GRNs from single-cell transcriptomic data. By leveraging kernel methods, our model generated enriched feature representations based on pairwise gene similarities. By stacking multiple GCKM layers with varying kernel widths, which modulate the receptive field of each node, the model captures complex gene interactions and nonlinear dependencies in a high-dimensional feature space, effectively encoding global structural dependencies.

##### Requirements

You'll need to install the following packages in order to run the codes.

numpy==1.19.3

pandas==1.2.4

scikit\_learn==1.0.2

scipy==1.7.3

##### Getting started

See main.py

