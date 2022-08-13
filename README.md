# STraTS: Self-Supervised Transformer for Multivariate Clinical Time-Series with Missing Values

This is the official keras implementation of STraTS (https://arxiv.org/abs/2107.14293)

If you find this repo useful, please cite


    @article{10.1145/3516367,
    author = {Tipirneni, Sindhu and Reddy, Chandan K.},
    title = {Self-Supervised Transformer for Sparse and Irregularly Sampled Multivariate Clinical Time-Series},
    year = {2022},
    issue_date = {December 2022},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    volume = {16},
    number = {6},
    issn = {1556-4681},
    url = {https://doi.org/10.1145/3516367},
    doi = {10.1145/3516367},
    abstract = {Multivariate time-series data are frequently observed in critical care settings and are typically characterized by sparsity (missing information) and irregular time intervals. Existing approaches for learning representations in this domain handle these challenges by either aggregation or imputation of values, which in-turn suppresses the fine-grained information and adds undesirable noise/overhead into the machine learning model. To tackle this problem, we propose a Self-supervised Transformer for Time-Series (STraTS) model, which overcomes these pitfalls by treating time-series as a set of observation triplets instead of using the standard dense matrix representation. It employs a novel Continuous Value Embedding technique to encode continuous time and variable values without the need for discretization. It is composed of a Transformer component with multi-head attention layers, which enable it to learn contextual triplet embeddings while avoiding the problems of recurrence and vanishing gradients that occur in recurrent architectures. In addition, to tackle the problem of limited availability of labeled data (which is typically observed in many healthcare applications), STraTS utilizes self-supervision by leveraging unlabeled data to learn better representations by using time-series forecasting as an auxiliary proxy task. Experiments on real-world multivariate clinical time-series benchmark datasets demonstrate that STraTS has better prediction performance than state-of-the-art methods for mortality prediction, especially when labeled data is limited. Finally, we also present an interpretable version of STraTS, which can identify important measurements in the time-series data. Our data preprocessing and model implementation codes are available at .},
   journal = {ACM Trans. Knowl. Discov. Data},
   month = {jul},
   articleno = {105},
   numpages = {17},
   keywords = {Time-series, healthcare, neural networks, deep learning, Transformer, self-supervised learning}
}
