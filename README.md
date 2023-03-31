# Adversarial Attack and Defense Experiment

This repository contains the code and results for two experiments that investigate the effectiveness of adversarial attacks and defenses on ResNet-18 models pretrained on CIFAR-10 and CIFAR-100 datasets.

Experiment Setting 1
Dataset
CIFAR-10 dataset

Models
ResNet-18 pretrained on CIFAR-10. The specific model structure is defined by resnet.py in the official TRADES github link [4].

Attack Settings
AutoAttack with an epsilon of 0.031 (or 8/255) and norm of ’Linf’ and ’L2’ [3].

Results Report
ResNet-18 classification accuracy on CIFAR-10.
AA attack rate on the pre-trained ResNet-18.
AA adversarial samples detection rate.
Experiment Setting 2
Dataset
CIFAR-100 dataset

Models
ResNet-18 pretrained on CIFAR-100. The specific model structure is defined by resnet.py in the official TRADES github link [4].

Attack Settings
AutoAttack with an epsilon of 0.031 (or 8/255) and norm of ’Linf’ and ’L2’ [3].

Results Report
ResNet-18 classification accuracy on CIFAR-100.
AA attack rate on the pre-trained ResNet-18.
AA adversarial samples detection rate.
Discussion
The results of the experiments will be discussed in detail in the project report. The report will include a comparison of the effectiveness of adversarial attacks and defenses on the two ResNet-18 models trained on CIFAR-10 and CIFAR-100 datasets. The discussion will focus on the limitations and strengths of each attack and defense method, and how they can be improved to better protect deep learning models against adversarial attacks.
