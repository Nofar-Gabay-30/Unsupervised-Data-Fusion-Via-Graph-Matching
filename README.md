# Unsupervised Data Fusion Via Graph Matching

link to the paper

## Abstruct
Point correspondence poses a fundamental challenge in the fields of computer vision, pattern recognition, and machine learning. The correspondence problem is often addressed through graph matching methodologies, where each point corresponds to a node, and the weight between nodes is a function of their pairwise distance.
Given the NP-completeness of graph matching problems, numerous techniques to obtain approximate solutions have been proposed. However, these techniques often suffer from high computational complexity, which limits their applicability to small datasets. In this paper, we introduce a scalable and efficient framework for matching data across two distinct sources, particularly applicable in scenarios where no landmarks are shared between the respective sets. We present several contributions. We developed a sparse, scalable, and efficient compatibility matrix aimed at resolving the inherent challenges in graph matching. The compatability matrix is based on diffision embedding, computed for both datasets. Our diffusionbased compatability matrix has the dual advantage of being more robust than previous matrices, while being much sparser, a property that enables its use for matching large datasets. Through comprehensive experimentation involving both synthetic points and real-world images, we demonstrate the efficacy of our proposed method by comparing it against benchmark techniques.

## Deffusion Matching Algorithm

![algo dm](https://github.com/user-attachments/assets/7b5a145e-1cc5-4101-b82f-9650bf86da1d)

<img src=![algo dm](https://github.com/user-attachments/assets/7b5a145e-1cc5-4101-b82f-9650bf86da1d) width="500" height="300">


Here you can find the DM algorithm and implementations of two of our experiments.

