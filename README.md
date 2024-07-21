# Mitigating Black-Box Membership Inference Attack using Metric Mapping

<h4>Membership Inference Attack</h4>

[Membership inference](https://arxiv.org/abs/1610.05820) attacks can be carried out against neural networks to infer the presence of data records in the training dataset, breaching user privacy. Black-box membership inference attacks can be executed simply by analyzing metrics like entropy, standard deviation, and maximum posterior probability of output prediction vectors, as these metrics have different distributions for members and non-members of the training dataset.

<h4>Metric Mapping</h4>

The Metric Mapping algorithm aims to eliminate the differences in metric distributions of members and non-members by manipulating the output prediction vectors such that the prediction remains the same. Thus, ensuring that utility is not compromised to preserve privacy.

<h4>Experimental Analysis</h4>

The Jupyter notebooks consist of experiments measuring the effectiveness of metric mapping in mitigating black-box membership inference attacks for different datasets in the presence of class imbalance and overfitting. Furthermore, the algorithm is compared with [DP-SGD](https://arxiv.org/abs/2009.00395), [DP-Logits](https://arxiv.org/abs/2009.00395), and [Dropout](https://arxiv.org/abs/2103.07853) techniques with respect to preserving privacy and maintaining utility.
