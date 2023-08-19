# mmm2024
## Abstract
To avoid deep learning models utilizing short-cuts in a train-
ing dataset, many debiasing models have been developed to encourage
models learning from accurate correlations. Some research constructs ro
bust models via adversarial training. Although this series of methods
shows promising debiasing performance, we do not know precisely what
spurious features have been discarded during adversarial training. To
address its lack of explainability especially in scenarios with low error
tolerance, we design AdvExp, which not only visualizes the underly
ing spurious feature behind adversarial training but also maintains good
debiasing performance with the assistance of a robust optimization algo
rithm. We showed promising performance of AdvExp on BiasCheXpert,
a subsampled dataset from CheXpert, and uncover potential regions in
radiographs recognized by deep neural networks as gender or race-related
features.
## Supplementary
### BiasCheXpert-gender
![BiasCheXpert-gender](https://github.com/mmm2024-106/mmm2024/blob/8ae4262ee85c62823adead6c8118ad760bbd7cef/table_BiasCheXpert_gender.PNG)
### BiasCheXpert-race
![BiasCheXpert-race](https://github.com/mmm2024-106/mmm2024/blob/8ae4262ee85c62823adead6c8118ad760bbd7cef/table_BiasCheXpert_race.PNG)
