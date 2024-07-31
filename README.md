# EFSPF
One of the crucial processes in machine learning algorithms to improve the performance as well as, in some cases, to reduce the computational cost is feature selection. In other words, when there are many features, some are irrelevant; thus, irrelevant features will badly affect the learning process, so selecting the most fitting features can lead to increasing the accuracy of models in high-dimensional datasets. Recent researches benefit from an integration of various feature selection methods to find relevant features more accurately. Despite the fact that applying several feature selection methods can be efficient, the accuracy of current methods and combining the ranks of different feature selection methods are still challenging problems. In this paper, a novel ensemble of feature selection based on weighted PageRank and fuzzy logic, named EFSPF, is proposed to overcome these drawbacks. First, an MM matrix, called Euclidean Distance Matrix (EDM), is set up, where M is the number of features. Secondly, a fuzzy Type-I is applied individually to tackle uncertainties in ranks. In other words, to specify a reliability rate for each feature, fuzzy Type-I is utilized. Then, EFSPF forms a reliable weighted graph where each feature is considered as a node. Furthermore, the weight between two nodes expresses a combination of their Euclidean Distance in EDM and the calculated reliability rates through fuzzy Type-I. Finally, the rank of each graph node is calculated via the PageRank algorithm. To demonstrate the performance of EFSPF, we have compared it with five ensemble algorithms and eight primary feature selection algorithms. The proposed method is evaluated based on Accuracy, Precision, Recall, and F1 score metrics. The analysis results show that the proposed method outperforms its rivals.




## Citation
```
@article{JOODAKI2021107538,
title = {An ensemble feature selection algorithm based on PageRank centrality and fuzzy logic},
journal = {Knowledge-Based Systems},
volume = {233},
pages = {107538},
year = {2021},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2021.107538},
url = {https://www.sciencedirect.com/science/article/pii/S0950705121008005},
author = {Mehdi Joodaki and Mohammad Bagher Dowlatshahi and Nazanin Zahra Joodaki},
keywords = {Feature selection, Ensemble feature selection, PageRank, High-dimensional data, Fuzzy Type-I},
abstract = {One of the crucial processes in machine learning algorithms to improve the performance as well as, in some cases, to reduce the computational cost is feature selection. In other words, when there are many features, some are irrelevant; thus, irrelevant features will badly affect the learning process, so selecting the most fitting features can lead to increasing the accuracy of models in high-dimensional datasets. Recent researches benefit from an integration of various feature selection methods to find relevant features more accurately. Despite the fact that applying several feature selection methods can be efficient, the accuracy of current methods and combining the ranks of different feature selection methods are still challenging problems. In this paper, a novel ensemble of feature selection based on weighted PageRank and fuzzy logic, named EFSPF, is proposed to overcome these drawbacks. First, an M×M matrix, called Euclidean Distance Matrix (EDM), is set up, where M is the number of features. Secondly, a fuzzy Type-I is applied individually to tackle uncertainties in ranks. In other words, to specify a reliability rate for each feature, fuzzy Type-I is utilized. Then, EFSPF forms a reliable weighted graph where each feature is considered as a node. Furthermore, the weight between two nodes expresses a combination of their Euclidean Distance in EDM and the calculated reliability rates through fuzzy Type-I. Finally, the rank of each graph node is calculated via the PageRank algorithm. To demonstrate the performance of EFSPF, we have compared it with five ensemble algorithms and eight primary feature selection algorithms. The proposed method is evaluated based on Accuracy, Precision, Recall, and F1 score metrics. The analysis results show that the proposed method outperforms its rivals. The source code of the proposed method is accessible from https://github.com/mehdijoodaki/EFSPF.}
}
```




