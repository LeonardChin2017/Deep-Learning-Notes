# Deep-Learning-Starter-Pack
## Index

1. [Setup GCP with Jupyter Notebook (MALAYSIA)](https://github.com/LeonardChin2017/Deep-Learning-Notes/blob/master/SETUP%20GOOGLE%20CLOUD%20PLATFORM%20WITH%20JUPYTER%20(MALAYSIA).pdf)
2. [How to setup Tensorflow 1.8 on Window 10](https://github.com/LeonardChin2017/Deep-Learning-Starter-Pack/blob/master/HOW%20TO%20SETUP%20TENSORFLOW%201.8%20ON%20WINDOW%2010.pdf)
3. Some Common Datasets for Deep Learning
   * MNIST
     * Brief description: Database of handwritten digits (0-9) 
     * Table of some machine learning methods using on MNIST database
     
       | Classifier                                                          | Preprocessing               | Test Error Rate (%) |
       |---------------------------------------------------------------------|-----------------------------|---------------------|
       | Linear Classifier (1-layer NN)                                      | none                        | 12.0                |
       | Linear Classifier (1-layer NN)                                      | deskewing                   | 8.4                 |
       | K-nearest-neighbors, Euclidean (L2)                                 | none                        | 5.0                 |
       | K-nearest-neighbors, Euclidean (L2)                                 | deskewing                   | 2.4                 |
       | Convolutional net LeNet-1                                           | subsampling to 16x16 pixels | 1.7                 |
       | Convolutional net LeNet-4                                           | none                        | 1.1                 |
       | Convolutional net LeNet-5, [distortions]                            | none                        | 0.8                 |
       | Convolutional net, cross-entropy [elastic distortions]              | none                        | 0.4                 |
       | committee of 35 conv. net, 1-20-P-40-P-150-10 [elastic distortions] | width normalization         | 0.23                |
     
     * Link: http://yann.lecun.com/exdb/mnist/
     
    * MSCOCO
    * PASCAL VOC
    * CIFAR 10 
