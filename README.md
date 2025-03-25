## Hybrid Bayesian Neural Networks: Quantifying Uncertainty in Cancer detection

Data:
~20,000 features: https://drive.google.com/file/d/1TH2ahaH7mzR93Mfz635oY46MMN24T-u1/view?usp=sharing
10,000 features: https://drive.google.com/file/d/1-0wf0G3_b5s3laKKAsoSgB_pQhy0BT14/view?usp=sharing
1000 features: https://drive.google.com/file/d/1_aFrfV6ldxosYn5e-xk54UpnPKQv4vtS/view?usp=sharing

Abstract:
Deep learning models for cancer detection with gene expression data do not
quantify the uncertainty. This leads to unreliability in clinical settings where
knowing the risks involved in detections is required for improved decision-
making. To this end, we introduced a hybrid Bayesian neural network composed
of multilayer perceptron and Bayesian layers to quantify uncertainty. Our hybrid
approach proved effective in improving performance while quantifying aleatoric
and epistemic uncertainty. Achieving an accuracy of 0.9624, and the total un-
certainty having a mean of 1.133 and 0.271 bits for incorrectly and correctly
labeled, correspondingly. Further, our approach is evaluated with an ablation
study. Six distributions were benchmarked as our prior and posterior to assess
their influence on convergence.
![hybrid bayesian model](https://github.com/user-attachments/assets/a94ed0c1-2848-4311-baec-e6dd566675f0)
