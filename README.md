# ECE-GY-7123-Deep-Learning-Project-3

**Team GradesAreAllYouNeed**  
Ansh Sarkar (as20363@nyu.edu)  
Princy Doshi (pd2672@nyu.edu)  
Simran Kucheria (sk11645@nyu.edu)  
New York University

## Overview

This project aims to understand the impact of various jail-breaking (adversarial attack) techniques on making the performance of a deep model worse.
Starting with a pretrained ResNet-34, we evaluated multiple attack methods-including iterative and targeted attacks-to identify the most effective approach. All techniques were then applied to DenseNet-121 to compare model robustness. 

**Final Results:**  
- Technique: MIFGSM
- Top1 Accuracy: **0%**  
- Densenet Accuracy: **45%**  

## Methodology

- **Dataset:** A sample of ImageNet Dataset
- **Experiments:** FGSM, MI-FGSM, Patch Attacks..

## References

- Dong, Y.; Liao, F.; Pang, T.; Su, H.; Zhu, J.; Hu, X.; and
Li, J. 2018. Boosting Adversarial Attacks with Momentum.
arXiv preprint arXiv:1710.06081.
- Goodfellow, I. J.; Shlens, J.; and Szegedy, C. 2015.
Explaining and Harnessing Adversarial Examples.
arXiv:1412.6572.
- Kim, H. 2018a. FGSM-pytorch: A PyTorch Implemen-
tation of ”Explaining and Harnessing Adversarial Exam-
ples”. https://github.com/Harry24k/FGSM-pytorch. Ac-
cessed: 2025-05-13.
- Waghela, H.; Sen, J.; and Rakshit, S. 2024. Robust Image
Classification: Defensive Strategies against FGSM and PGD
Adversarial Attacks. arXiv:2408.13274.
