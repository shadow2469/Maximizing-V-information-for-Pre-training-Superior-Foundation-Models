# Maximizing V-information for Pre-training Superior Foundation Models

This repo is the official implementation of ["Maximizing V-information for Pre-training Superior Foundation Models"](https://arxiv.org/abs/2408.07107).

## Abstact

Pre-training foundation models on large-scale datasets demonstrates exceptional performance. However, recent research questions this traditional notion, exploring whether an increase in pre-training data always leads to enhanced model performance. To address this issue, data-effective learning approaches have been introduced. However, current methods in this area lack a clear standard for sample selection. Our experiments reveal that by maximizing V-information, sample selection can be framed as an optimization problem, enabling effective improvement in model performance even with fewer samples. Under this guidance, we develop an optimal data-effective learning method (OptiDEL) to maximize V-information. The OptiDEL method generates hard samples to achieve or even exceed the performance of models trained on the full dataset while using substantially less data. We compare the OptiDEL method with state-of-the-art approaches finding that OptiDEL consistently outperforms existing approaches across different datasets, with foundation models trained on only 5% of the pre-training data surpassing the performance of those trained on the full dataset.
