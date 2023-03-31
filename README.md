# Adversarial Attack and Defense Experiment

This repository contains the code and results for two experiments that investigate the effectiveness of adversarial attacks and defenses on ResNet-18 models pretrained on CIFAR-10 and CIFAR-100 datasets.

## Experiment Settings
This repository contains code for two different experiment settings. For both settings, we use the AutoAttack method to generate adversarial samples with an epsilon of 0.031 (or 8/255) and norm of `Linf' and `L2' [1].

### Setting 1: CIFAR-10
#### Dataset
The dataset used is CIFAR-10.

#### Model
We use ResNet-18 pre-trained on CIFAR-10. The specific model structure is defined by resnet.py in the official TRADES github link [2].

#### Result report

ResNet-18 classification accuracy on CIFAR-10.
AutoAttack attack rate on the pre-trained ResNet-18.
AutoAttack adversarial samples detection rate.

### Setting 2: CIFAR-100
#### Dataset
The dataset used is CIFAR-100.

#### Model
We use ResNet-18 pre-trained on CIFAR-100. The specific model structure is defined by resnet.py in the official TRADES github link [2].

## Result report
ResNet-18 classification accuracy on CIFAR-100.
AutoAttack attack rate on the pre-trained ResNet-18.
AutoAttack adversarial samples detection rate.

 
#### References
[1] F. Croce and M. Hein, "Reliable evaluation of adversarial robustness with an ensemble of diverse parameter-free attacks," 2020. (https://github.com/fra31/auto-attack)

[2] H. Zhang, Y. Yu, J. Jiao, E. Xing, L. El Ghaoui, and M. Jordan, "Theoretically principled trade-off between robustness and accuracy," 2019. (https://github.com/yaodongyu/TRADES)
