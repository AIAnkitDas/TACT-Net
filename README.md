# TACT-Net: Triple-Tier Attention-integrated Compact Transformer Network for COVID-19 Prediction in CT Scans

## Accepted for Publication at the 6th International Conference on Frontiers in Computing and Systems (COMSYS)


The global impact of COVID-19 points out the need of a
rapid, accurate and robust diagnostic method to minimize its consequences.
In, this study, we propose a hybrid architecture, TACT-Net
a Triple-Tier Attention-Integrated Compact Transformer, which uses
depth-wise separable convolutions for efficient feature extraction combining
with global contextual awareness of transformer model. We have
integrated Triple Tier Attention (TTA) with the compact transformer
block, to capture the important regions-of-infections from the chest CT
scans, leading to accurate predictions. Experiments were carried out on
the publicly available “SARS-CoV-2 CT Scan” database. To ensure robustness
and generalization of our model, we have performed 3-fold cross
validation. The results achieved exhibit a macro f1-score of 0.9835 across
the 3 folds. The model not only outperformed existing method in terms
of precision, recall and f1-score, but it is also computationally efficient,
because of its low parameter count. For qualitative analysis, we used
Grad-CAM heatmaps as a part of Explainable AI techniques for visualizing
the infected regions.
