# CS722822 Machine Learning
This repository serves as course website for CS722/822 Machine Learning.

The course sysllabus is [here](https://github.com/fengjiaowang7/CS722822/blob/main/CS722_822_syllabus_new.pdf)

Required reading on how to read research paper:
1. How to Read a CS Research Paper? Philip W. L. Wong. [PDF](http://www2.cs.uregina.ca/~pwlfong/CS499/reading-paper.pdf)
2. How to Read a Technical Paper. Jason Eisner. [Online](https://www.cs.jhu.edu/~jason/advice/how-to-read-a-paper.html)
3. How to Read a Paper. S. Keshav. [PDF](http://blizzard.cs.uwaterloo.ca/keshav/home/Papers/data/07/paper-reading.pdf)   
Note: **please follow idea mentioned in reference 1 to write your own paper review summary**.

List of references for part II:
1. Representation Learning: A Review and New Perspectives. [PDF](https://arxiv.org/pdf/1206.5538.pdf)
2. Self-Supervised Representation Learning. [online](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html)
3. Leave those nets alone: advances in self-supervised learning. CVPR 2021 tutorial. including topics: contrasive learning, teacher student approaches. [video](https://gidariss.github.io/self-supervised-learning-cvpr2021/)

image processing references:
1. Basic Image Handling and Processing [online](https://www.oreilly.com/library/view/programming-computer-vision/9781449341916/ch01.html)

Tentative course schedule:
| Week                   | Date |Topics                                                       | Homework/Quiz | Course Project                            |
| ---------------------- |  ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------- | -------------------------------- |
| Week 1 (8/30-9/3)      | 8/31 | Course overview |                                  | |
| Week 1 (8/30-9/3)      | 9/2 | Review of basic mathematics (matrix computation, norms, probability, mean, variance, optimization, etc.) |                                  | |
| Week 2 (9/6-9/10)      | 9/7 | Supervised Learning - regression (linear/polynomial/non-linear regression), least square |                                 | |
| Week 2 (9/6-9/10)      | 9/9 | underfitting, overfitting, regularization |  Homework 1 is published in Blackboard on 9/9, due date is 9/16 (by end of the day)                                | |
| Week 3 (9/13-9/17)     | 9/14 |logistic regression, model evaluation (confusion matrix, Accuracy, precision, recall, F-measure, cost-sensitive measure)                                      |                                  | |
| Week 3 (9/13-9/17)     | 9/16 | model evaluation (ROC curve, AUC), Deep Learning Introduction                                      |  Homework 1 due on 9/16  <br> Homework 2 is published on 9/17, due date is 9/26 (by end of the day)                               | selecting paper for presentation by 9/19|
| Week 4 (9/20-9/24)     | 9/21 | Deep Learning Introduction        |                                | |
| Week 4 (9/20-9/24)     | 9/23 | In-class quiz        | In-class quiz on 9/23 <br> Homework 2 due on 9/26                                 | |
| Week 5 (9/27-10/1)     | 9/28 | Unsupervised Learning - clustering: K-means, hierarchical clustering, DBSCAN, spectral clustering, Gaussian mixture model, evaluation |                                | |
| Week 5 (9/27-10/1)     | 9/30 | continue clustering |  Homework 3 (programming assignment, logistic regression) publish on 9/30, due on 10/17 (by end of the day)                                 |Course project proposal due on 10/3 |
| Week 6 (10/4 - 10/8)   | 10/5 | semi-supervised learning survey<br> required reading: Introduction to Semi-Supervised Learning. Olivier Chapelle, Bernhard Schölkopf, and Alexander Zien. In Semi-Supervised Learning, MIT Press, 2006. [PDF](http://mitp-content-server.mit.edu:18180/books/content/sectbyfn?collid=books_pres_0&id=6173&fn=9780262033589_sch_0001.pdf)                                        |                                | |
| Week 6 (10/4 - 10/8)   | 10/7 | unsupervised learning, semi-supervised learning survey - part2                                         |                                   | |
| ~~Week 7 (10/11-10/15)~~   | ~~10/12~~ | No class on 10/12 (Fall Holiday)   |  |  |
| Week 7 (10/11-10/15)   | 10/14 | In-class quiz           | In-class quiz on 10/14 <br>Homework 3 due 10/17  |  |
| Week 8 (10/18-10/22)   | 10/19 | Paper presentation<br>[semi-supervised learning] 5. Temporal Ensembling for Semi-Supervised Learning. Samuli Laine and Timo Aila. International Conference on Learning Representations (ICLR) 2017.         |  Homework 4 (programming assignment, neural network) publish on 10/19, due on 11/7 (by the end of the day)                                | |
| Week 8 (10/18-10/22)   | 10/21 | Paper presentation<br>2.  Big Self-Supervised Models are Strong Semi-Supervised Learners. Ting Chen, Simon Kornblith, Kevin Swersky, Mohammad Norouzi, and Geoffrey Hinton. ArXiv 2006.10029 2020. <br>20. Large-Scale Weakly-Supervised Pre-Training for Video Action Recognition.           |                                  | |
| Week 9 (10/25 - 10/29) | 10/26 |   Paper presentation<br>10. Fine-Tune BERT for text classification <br>3. Self-Supervised Semi-Supervised Learning<br>26.  Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks. Chelsea Finn, Pieter Abbeel, and Sergey Levine. In International Conference on Machine Learning (ICML) 2017 |                                  | |
| Week 9 (10/25 - 10/29) | 10/28 | Paper presentation<br> 17. Pretrained Encyclopedia: Weakly Supervised Knowledge-Pretrained Language Model. Wenhan Xiong, Jingfei Du, William Yang Wang, and Veselin Stoyanov. International Conference on Learning Representations (ICLR) 2020.<br>12. Momentum Contrast for Unsupervised Visual Representation Learning.<br>15.  Snorkel:  Rapid  Training  Data  Creation  with  Weak  Supervision.  Alexander  Ratner,  Stephen  H.  Bach,  Henry Ehrenberg,  Jason  Fries,  Sen  Wu,  and  Christopher  Ré.  Proceedings  of  the  VLDB  Endowment,  11(3):269-282, 2017.                                              |                                  | |
| ~~Week 10 (11/1-11/5)~~    | ~~11/2~~ | No class on 11/2 (Election Day)                                             |    |  |
| Week 10 (11/1-11/5)    | 11/4 |   Paper presentation<br>7. Self-training  with  Noisy  Student  improves  ImageNet  classification.   <br> 11. Unsupervised Feature Learning via Non-Parametric Instance Discrimination.                                         | Homework 4 due on 11/7 (by the end of the day)  |  |
| Week 11 (11/8-11/12)   | 11/9 | Paper presentation<br>  22. Learning from Simulated and Unsupervised Images through Adversarial Training.<br>9. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.                                           |                                  | |
| Week 11 (11/8-11/12)   | 11/11 | Paper presentation<br> 23. Unsupervised Data Augmentation for Consistency Training. Qizhe Xie, Zihang Dai, Eduard Hovy, MinhThang Luong, and Quoc V. Le. ArXiv 1904.12848 2019.<br>29. Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs                                            |                                  | |
| Week 12 (11/15-11/19)  | 11/16 | Paper presentation<br>  30. Rethinking Knowledge Graph Propagation for Zero-Shot Learning<br>27. Rethinking Few-Shot Image Classiication: A Good Embedding Is All You Need? Yonglong Tian, Yue Wang, Dilip Krishnan, Joshua B. Tenenbaum, and Phillip Isola. ArXiv:2003.11539 2020.                                           |                                  | Course project milestone report due on 11/16 |
| Week 12 (11/15-11/19)  | 11/18 | Paper presentation<br>  "28. DeViSE: A Deep Visual-Semantic Embedding Model. Andrea Frome, Greg S. Corrado, Jon Shlens, Samy Bengio, Jeff Dean, Marc'Aurelio Ranzato, and Tomas Mikolov. In Neural Information Processing Systems (NeurIPS) 2015." <br>"4. Self-Supervised Learning of Pretext-Invariant Representations. Ishan Misra and Laurens van der Maaten. IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2020."                                          |                                  | |
| Week 13 (11/22-11/26)  | 11/23 | Paper presentation<br>1. Billion-scale semi-supervised learning for image classification. I. Zeki Yalniz, Hervé Jégou, Kan Chen, Manohar Paluri, and Dhruv Mahajan. ArXiv 1905.00546 2019. <br> 24. MixMatch: A Holistic Approach to Semi-Supervised Learning                                             |  |  |
| ~~Week 13 (11/22-11/26)~~  | ~~11/25~~ |  No class on 11/25 (Thanksgiving)                    |  |  |
| Week 14 (11/29-12/3)   | 11/30 | Paper presentation<br>   21. Semi-Supervised Learning with Deep Generative Models. Diederik P. Kingma, Danilo J. Rezende, Shakir Mohamed, and Max Welling. Neural Information Processing Systems (NeurIPS) 2014.<br>8. Pseudo-Labeling and Confirmation Bias in Deep Semi-Supervised Learning.                                           |                                  | |
| Week 14 (11/29-12/3)   | 12/2 | Paper presentation<br>    6. Mean teachers are better role models<br>19. Exploring the Limits of Weakly Supervised Pretraining                                         |                                  | |
| Week 15 (12/6-12/10)   | 12/7 | course project presentation                                  |               |  |
| Week 15 (12/6-12/10)   | 12/9 | course project presentation                                  |               | Course project (report, code, supplementary materials) due on 12/10 |


 
