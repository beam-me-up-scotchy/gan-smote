# GAN-SMOTE
## A Generative Adversarial Network approach to Synthetic Minority Oversampling for One-Hot Encoded Data
### Mitchell Scott & Jo Plested (2019)

### Abstract
Small unbalanced datasets remain a serious impediment to the implementation of cutting-edge machine
learning in an industry setting. This paper proposes GAN-SMOTE, a novel approach to synthetic minority class
oversampling using a generative adversarial network that can be applied to boost the performance of classifiers learning
from small and imbalanced one-hot encoded datasets. This paper also introduces techniques that are key for ensuring
the stability and variance of the generative adversarial network in this setting. The proposed method demonstrates
meaningful improvement on a well-studied petrographical dataset with significant class imbalance.

### Repo
"GAN-SMOTE.ipynb" implements the GAN-SMOTE architecture.
"Benchmark test for GAN-SMOTE.ipynb" displays benchmark test code and outcomes.
"utils.py" contains helper functions that help with data display (credit: https://github.com/diegoalejogm/gans/blob/master/1.%20Vanilla%20GAN%20PyTorch.ipynb)
