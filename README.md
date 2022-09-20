# Subject_independent_MI_classification_paper

## Papers
| Title | Author | Date | Publication | Link | Accuracy | Dataset | Model |
| - | - | - | - | :-:| :-: | :-: | :-: |
| MIN2Net : End-to-End Multi-Task Learning for Subject-Independent Motor Imagery EEG Classification | Phairot Autthansan, et al. | June-2022 | IEEE Transactions on Biomedical Engineering | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9658165) [Code](https://github.com/IoBT-VISTEC/MIN2Net) | 60.03% 59.79% 72.03% | BCIC_IV_2a SMR-BCI OpenBMI | AE CNN triplet |
| Subject-independent Brain-Computer Interfaces Based on Deep Convolutional Neural Networks | O-Yeon Kwon, et al. | Oct-2020 | IEEE Transactions on Neural Networks and Learning Systems | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8897723) Code | 74.15% | OpenBMI | FB CNN |
| A subject-independent pattern-based Brain-Computer Interface | Andreas M. Ray, et al. | Oct-2015 | Frontiers in Behavioral Neuroscience | [Paper](https://www.frontiersin.org/articles/10.3389/fnbeh.2015.00269/full) Code | 66.2% (10x10 CV) | Private | FBCSP SVM |
| Comparison of Designs Towards a Subject-Independent Brain-Computer Interface based on Motor Imagery | Fabien Lotte, et al. | 2009 | International Conference of the IEEE EMBS | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5334126) Code | 70.99% | BCIC_IV_2a (left, right hand) | multi-resoulution-FBCSP SVM |

## Papers to read 
| Title | Author | Date | Publication | Link | Accuracy | Dataset | Model |
| - | - | - | - | :-:| :-: | :-: | :-: |


## Public Datasets
| Dataset | Subjects | Classes | Channels | Sampling rate | #Training per subject | #Test per subject |
| - | :-:| :-: | :-: | :-: | :-: | :-: | 
| BCIC_IV_2a| 9 | 4 (rihgt hand, left hand, both feet, tongue) | 22EEG 3EOG | 250Hz | 288 | 288 |
| BCIC_IV_2b| 9 | 2 (rihgt hand, left hand) | 3EEG 3EOG | 250Hz | 400±a | 320±a |
| HGD(High-Gamma Dataset) | 14 | 4 (right hand, left hand, rest, feet) | 128 ME-EEG | 500Hz | ~880 | ~160 |
| OpenBMI | 54 | 2 (right hand, left hand) | 62EEG 4EMG | 1,000Hz | 200 | 200 | 
