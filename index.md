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

| | Application areas | Include literature numbers | Rationale |
|------------------------|-------------------|----------------------------------------------|
| Face Recognition and Image Classification | P1, P3, P4, P10 | Explicitly applied to image recognition tasks (YaleB, CIFAR, etc.) |
| Medical / Biosignals | P5, P6 | P5 for EEG classification, P6 for gene modeling discussion |
| General Machine Learning / Image Representation | P2, P7, P8, P9 | Generalized for generic tasks such as image completion, signal recovery and subspace clustering |
