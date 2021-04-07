Awesome Active Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A list of resources related to Active learning in machine learning.



# Tutorials

* [[Book] Active Learning](https://www.morganclaypool.com/doi/abs/10.2200/S00429ED1V01Y201207AIM018). Burr Settles. (CMU, 2012)
* [[Seminar] Active Learning from Theory to Practice](https://www.youtube.com/watch?v=_Ql5vfOPxZU). Steve Hanneke, Robert Nowak. (ICML, 2019)
* [[Seminar] Bandits, Active Learning, Bayesian RL and Global Optimization](https://www.youtube.com/watch?v=5rev-zVx1Ps).Marc Toussaint. (MLSS, 2013)
* [[Lecture. 24]  36-708 Statistical Methods for Machine Learning](https://www.youtube.com/watch?v=UHWbZHZ7aVk). (CMU, 2015)

# Papers

## Pool-Based Sampling

### Singleton

* [A Variance Maximization Criterion for Active Learning](https://arxiv.org/pdf/1706.07642.pdf). Yazhou Yang, Marco Loog. (Pattern Recognition, 2018)

* [The power of ensembles for active learning in image classification](http://openaccess.thecvf.com/content_cvpr_2018/papers/Beluch_The_Power_of_CVPR_2018_paper.pdf). William H. Beluch, Tim Genewein, Andreas Nurnberger, Jan M. Kohler. (CVPR, 2018)

* [Learning Algorithms for Active Learning](https://arxiv.org/pdf/1708.00088.pdf). Philip Bachman, Alessandro Sordoni, Adam Trischler. (ICML, 2017)

* [Beyond Disagreement-based Agnostic Active Learning](https://papers.nips.cc/paper/5435-beyond-disagreement-based-agnostic-active-learning.pdf). Chicheng Zhang, Kamalika Chaudhuri. (NIPS, 2014)

* [Bayesian Optimal Active Search and Surveying](https://arxiv.org/abs/1206.6406). Roman Garnett, Yaumna Krishnamurthy, Xuehan Xiong, Jeff Schneider, Richard Mann. (ICML, 2012)

* [Bayesian Active Learning for Classification and Prefernce Learning](https://arxiv.org/abs/1112.5745). Neil Houlsby, Ferenc Huszár, Zoubin Ghahramani, Máté Lengyel. (CoRR, 2011)

* [Active Learning using On-line Algorithms](https://www.cs.rutgers.edu/~pazzani/Publications/active-online.pdf). Chris Mesterharm, Michael J. Pazzani. (KDD, 2011) 

* [Active Learning from Crowds](http://www.cs.columbia.edu/~prokofieva/CandidacyPapers/Yan_AL.pdf). Yan Yan, R ́omer Rosales, Glenn Fung, Jennifer G. Dy. (ICML, 2011)

* [Hierarchical Sampling for Active Learning](https://dl.acm.org/doi/pdf/10.1145/1390156.1390183). Sanjoy Dasgupta, Daniel Hsu  (ICML, 2008)

  

### Batch/Batch-like

* [Deep Batch Active Learning By Diverse, Uncertain Gradient Lower Bound](https://openreview.net/forum?id=ryghZJBKPS). Jordan T. Ash, Chicheng Zhang, Akshay Krishnamurthy, John Langford, Alekh Agarwal. (ICLR, 2020)
* [Bayesian Generative Active Deep Learning](https://arxiv.org/pdf/1904.11643.pdf). Toan Tran, Thanh-Toan Do, Ian Reid, Gustavo Carneiro. (ICML, 2019)
* [Learning Loss for Active Learning](https://arxiv.org/abs/1905.03677). Donggeun Yoo, In So Kweon. (CVPR, 2019)
* [Variational Adversarial Active Learning](https://arxiv.org/pdf/1904.00370.pdf). Samarth Sinha, Sayna Ebrahimi, Trevor Darrell. (arXiv, 2019)
* [Integrating Bayesian and Discriminative Sparse Kernel Machines for Multi-class Active Learning](https://papers.nips.cc/paper/8500-integrating-bayesian-and-discriminative-sparse-kernel-machines-for-multi-class-active-learning.pdf). Weishi Shi, Qi Yu. (NeurIPS, 2019)
* [Rapid Performance Gain through Active Model Reuse](http://www.lamda.nju.edu.cn/liyf/paper/ijcai19-acmr.pdf). Feng Shi, Yu-Feng Li. (IJCAI, 2019)
* [Active Semi-Supervised Learning Using Sampling Theory for Graph Signals](http://sipi.usc.edu/~ortega/Papers/Gadde_KDD_14.pdf). Akshay Gadde, Aamir Anis, Antonio Ortega. (KDD, 2014)
* [Active Learning for Multi-Objective Optimization](http://proceedings.mlr.press/v28/zuluaga13.pdf). Marcela Zuluaga, Andreas Krause, Guillaume Sergent, Markus P{\''u}schel (ICML, 2013)
* [Querying Discriminative and Representative Samples forBatch Mode Active Learning](http://chbrown.github.io/kdd-2013-usb/kdd/p158.pdf). Zheng Wang, Jieping Ye. (KDD, 2013)
* [Near-optimal Batch Mode Active Learning and Adaptive Submodular Optimization](http://proceedings.mlr.press/v28/chen13b.pdf). Yuxin Chen, Andreas Krause. (ICML, 2013)
* [Active Learning for Probabilistic Hypotheses Usingthe Maximum Gibbs Error Criterion](https://papers.nips.cc/paper/4958-active-learning-for-probabilistic-hypotheses-using-the-maximum-gibbs-error-criterion.pdf), Nguyen Viet Cuong, Wee Sun Lee, Nan Ye, Kian Ming A. Chai, Hai Leong Chieu. (NIPS, 2013)
* [Batch Active Learning via Coordinated Matching](https://icml.cc/2012/papers/607.pdf). Javad Azimi, Alan Fern, Xiaoli Z. Fern, Glencora Borradaile, Brent Heeringa. (ICML, 2012)
* [Ask me better questions: active learning queries based on rule induction](https://www.eecs.wsu.edu/~cook/pubs/kdd11.pdf). Parisa Rashidi, Diane J. Cook. (KDD, 2011)
* [Active Instance Sampling via Matrix Partition](https://papers.nips.cc/paper/3919-active-instance-sampling-via-matrix-partition). Yuhong Guo. (NIPS 2010)
* [Discriminative Batch Mode Active Learning](https://papers.nips.cc/paper/3295-discriminative-batch-mode-active-learning.pdf). Charles X. Ling, Jun Du. (NIPS, 2007)



## Stream-Based Selective Sampling

* [Online Active Learning of Reject Option Classifiers](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-ShahK.3433.pdf). Kulin Shah, Naresh Manwani. (AAAI, 2020)
* [Active Learning from Peers](https://papers.nips.cc/paper/7276-active-learning-from-peers.pdf). Keerthiram Murugesan, Jaime Carbonell. (NIPS, 2017)
* [An Analysis of Active Learning Strategies for Sequence Labeling Tasks](https://www.biostat.wisc.edu/~craven/papers/settles.emnlp08.pdf). Burr Settles, Mark Craven. (EMNLP, 2008)
* [Improving Generalization with Active Learning](https://users.cs.northwestern.edu/~pardo/courses/mmml/papers/active_learning/improving_generalization_with_active_learning_ML94.pdf), DAVID COHN, LES ATLAS, RICHARD LADNER. (Machine Learning, 1994)



## Membership Query Synthesize

* [Active Learning via Membership Query Synthesisfor Semi-supervised Sentence Classification](https://www.aclweb.org/anthology/K19-1044/). Raphael Schumann, Ines Rehbein. (CoNLL, 2019)
* [Active Learning with Direct Query Construction](https://dl.acm.org/doi/10.1145/1401890.1401950), Yuhong Guo, Dale Schuurmans. (KDD, 2008)



## Meta-Learning

* [Meta-Learning for Batch Mode Active Learning](https://openreview.net/forum?id=r1PsGFJPz). Sachin Ravi, Hugo Larochelle. (ICLR-WS, 2018)
* [Meta-Learning Transferable Active Learning Policies by Deep Reinforcement Learning](https://arxiv.org/abs/1806.04798). Kunkun Pang, Mingzhi Dong, Yang Wu, Timothy Hospedales. (ICML-WS, 2018) 
* [Learning Active Learning from Data](https://papers.nips.cc/paper/7010-learning-active-learning-from-data.pdf). Ksenia Konyushkova, Sznitman Raphael. (NIPS, 2017)



## Theory

* [On Statistical Bias In Active Learning: How and When To Fix It](https://openreview.net/forum?id=JiYq3eqTKY). Sebastian Farquhar, Yarin Gal, Tom Rainforth (ICLR, 2021 spotlight)
* [Active Learning from Imperfect Labelers](https://papers.nips.cc/paper/6162-active-learning-from-imperfect-labelers.pdf). Songbai Yan, Kamalika Chaudhuri, Tara Javidi (NIPS, 2016)



## Critics

* [Towards Robust and Reproducible Active  Learning Using Neural Networks](https://arxiv.org/abs/2002.09564). Prateek Munjal, Nasir Hayaat, Nunawar Hayat, Jamshid Sourati, Shadab Khan. (arXiv, 2020)
* [Parting with Illusions about Deep Active Learning](https://arxiv.org/abs/1912.05361). Sudhanshu Mittal, Maxim Tatarchenko. Ozgu ̈n Cicek, Thomas Brox. (arXiv, 2019)



## Related

### Data Valuation

* [Dataset Condensation with Gradient Matching](https://openreview.net/forum?id=mSAKhLYLSsl). Bo Zhao, Konda Reddy Mopuri, Hakan Bilen. (ICLR, 2021 Oral)
* [Data Valuation Using Reinforcement Learning](https://arxiv.org/abs/1909.11671). Jinsung Yoon, Sercan O. Arik, Tomas Pfister. (ICML 2020)