# Title
ILDNet: A Novel Deep Learning Framework for Interstitial Lung Disease Identification Using Respiratory Sounds
# Abstrcat
Interstitial lung disease (ILD) is a collection of pulmonary adventitious conditions that induce scarring of the lung parenchyma, fibrosis, and inflammation. ILD encompasses over 200 chronic respiratory diseases that gradually damage the lung tissues and make it difficult to acquire adequate oxygen in the lungs. Therefore, it is essential to identify and diagnose diseases early to prevent their progression. ILDs are often characterized by abnormal respiratory sounds (RSs) such as crackles and squawks as a result of anatomical faults in the respiratory pathway produced by the disease. In this paper, for the first time, we propose a novel sinc convolution-based residual convolutional deep learning architecture, namely the ILDNet, for categorizing the ILD-affected RSs. The proposed framework comprises two major stages: (a) pre-processing of the input RS and (b) classification of the RSs using the proposed ILDNet. The proposed framework is extensively evaluated using the RSs from the publicly available BRACETS and KAUH datasets, and the experimental results show that our proposed ILDNet framework achieves an accuracy, sensitivity, and specificity of 81.25%, 78.85%, and 83.33%. These results also pave the way for future research on the potential use of RSs to identify reliable biomarkers for early-stage ILD identification.
# Block diagram
![block_diag_ILD_updated (1)](https://github.com/rsarka34/ILDNet/assets/89518952/d52a1240-6bf8-44af-a96f-3ecb194378d1)
# Results
<img width="639" alt="Screenshot 2024-07-04 at 8 02 55 PM" src="https://github.com/rsarka34/ILDNet/assets/89518952/8215d3f8-b09c-45b7-b1e4-fe0459c3f756">

Visualization of the feature maps extracted from the sinc-convolution layer, first residual block, and second residual block of our proposed ILDNet for healthy RS (a-c) and ILD-affected RS (d-f).


