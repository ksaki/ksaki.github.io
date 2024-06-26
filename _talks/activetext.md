---
title: "Improving Probabilistic Models in Text Classification via Active Learning" 
collection: talks
type: "Talk"
permalink: /talks/activetext
---
Co-authored with Mitchell Bosley, Yuki Shiraito, and Ted Enamorado

[Download paper](https://arxiv.org/abs/2202.02629)

Abstract: 

Modern strategies to classify text documents are generally separated into supervised and unsupervised algorithms. Both of these methods have downsides: in the former, hand-coding documents is labor-intensive and costly; in the latter, performance is severely threatened when the data lacks the necessary structure such that a strong signal can be recovered.  One way to reduce the cost of hand-coding documents in the supervised approach is active learning. However, current implementations of active learning have only been used to augment supervised approaches. Our innovation is to augment the active learning with unsupervised clustering in addition to the supervised approach. In this way, we provide a model that exploits the benefits of both the unsupervised and supervised approaches to improve the performance of text classifiers.  In particular, we use a probabilistic mixture model of text to combine the information from both labeled and unlabeled documents at each stage of the proposed active learning algorithm. We improve upon existing approaches in three ways. First, we design new sampling schemes for active learning to retrieve the most informative observations to be labeled. Second, we formalize the conditions under which upweighting the most informative labeled cases can help improve precision measures for text classification. Third, we show that in some cases, allowing multiple latent clusters to be linked with one classification category improves the model fit, and develop a diagnostic tool that finds the optimal number of clusters to use in the unsupervised part of the algorithm.
