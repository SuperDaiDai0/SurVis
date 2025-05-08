## Explanation of Literature Classification Logic
**Topics** are categorized according to the research core and modeling ideas that the literature focuses on: for example, SRC and compressed sensing belong to “basic theory”, structured a priori belongs to “structured sparsity”, and those that are combined with CNN belong to “deep sparsity”, and those that are combined with CNN belong to “deep sparsity”.

**The methodology classification** is based on the methodology used in the research, including theoretical analysis (optimization), empirical testing, and whether or not weakly supervised methods are used.

**The application area classification** focuses on practical task scenarios (e.g., face recognition, medical images, signal processing, etc.), which facilitates the subsequent analysis of task-specific effects.

## Literature classification table

### Categorize by Research Topic

| Category | Include Literature No. | Rationale |
|----------------------|------------------|---------------------------------------|
| Basic Sparse Representation Theory | P1, P2, P7 | Focus on core theories of L1 sparsity, SRC modeling and compressed perception |
| Discriminative Dictionary Learning and Optimization | P3, P4, P10 | Focus on Supervised Dictionary Construction, Semi-Supervised Learning, and Classification Performance Improvement | Structured Sparse Modeling
| Structured Sparse Modeling | P5, P6, P8 | Involves structural extensions such as graph regularity, group sparsity, and low-rank structure
| Deep Sparse Representation and Integration | P9, P10 | Trainable sparse modeling methods combined with deep networks |

### Categorized by method type

| Method Type | Include Literature Number | Rationale |
|----------------------|-----------------------|----------------------------------------|
| Mathematical Modeling / Theoretical Derivation | P1, P2, P6, P7, P9 | Explicitly include algorithm derivation, optimization theory and convergence analysis |
| Empirical Comparison Experiments | P3, P4, P5, P8, P10 | Provides classification performance evaluation against a baseline method or data set |
| semi-supervised / self-supervised methods | P4, P10 | explicitly use unlabeled data to enhance classification |

### Categorize by application area

|  Application areas | Include literature numbers | Rationale |
|------------------------|-------------------|----------------------------------------------|
| Face Recognition and Image Classification | P1, P3, P4, P10 | Explicitly applied to image recognition tasks (YaleB, CIFAR, etc.) |
| Medical / Biosignals | P5, P6 | P5 for EEG classification, P6 for gene modeling discussion |
| General Machine Learning / Image Representation | P2, P7, P8, P9 | Generalized for generic tasks such as image completion, signal recovery and subspace clustering |

### Exhibit: Thesis Numbering Cross Reference Chart
| No. | Title of Literature | Author(s) (first author) | Year of Publication | Source |
| --- | ------------------------------------------------------------------------------ | ---------- | ---- | ------------------- |
| P1 | Robust Face Recognition via Sparse Representation | Wright, J. | 2009 | IEEE TPAMI |
| P2 | Online Learning for Matrix Factorization and Sparse Coding | Mairal, J. | 2010 | JMLR |
| P3 | Discriminative K-SVD for Dictionary Learning in Face Recognition | Zhang, Q. | 2010 | CVPR | P2 | Online Learning for Matrix Factorization and Sparse Coding | Zhang, Q.
| P4 | Unlabeled Data Driven Cost-Sensitive Inverse Projection Sparse Representation | Yang, X. | 2021 | Eng. Appl. of AI |
| P5 | Graph Regularized Sparse Coding for Image Representation | Zheng, M. | 2011 | IEEE TIP |
| P6 | Structured Sparsity through Convex Optimization | Bach, F. | 2012 | NEURIPS |
| P7 | Robust Uncertainty Principles: Exact Signal Reconstruction | Candes, E. | 2006 | IEEE TIT | P8 | Robust Uncertainty Principles.
| P8 | Robust Recovery of Subspace Structures by Low-Rank Representation | Liu, G. | 2010 | IEEE TPAMI | P8 | Robust Recovery of Subspace Structures by Low-Rank Representation
| P9 | Learning Fast Approximations of Sparse Coding (LISTA) | Gregor, K. | 2010 | ICML | P10 | Discriminate | Discriminate | Discriminate | Discriminate | Discriminate | Discriminate | Discriminate
| P10 | Discriminative Semi-Supervised Learning via Deep and Dictionary Representation | Zhang, X. | 2023 | Pattern Recognition |

