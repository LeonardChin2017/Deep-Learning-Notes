# Deep-Learning-Starter-Pack
## Index

1. [Setup GCP with Jupyter Notebook (MALAYSIA)](https://github.com/LeonardChin2017/Deep-Learning-Notes/blob/master/SETUP%20GOOGLE%20CLOUD%20PLATFORM%20WITH%20JUPYTER%20(MALAYSIA).pdf)
2. [How to setup Tensorflow 1.8 on Window 10](https://github.com/LeonardChin2017/Deep-Learning-Starter-Pack/blob/master/HOW%20TO%20SETUP%20TENSORFLOW%201.8%20ON%20WINDOW%2010.pdf)
3. Some Common Datasets for Deep Learning
   * MNIST (Digits classification) 
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
     
     * Download: http://yann.lecun.com/exdb/mnist/
     
    * MSCOCO (Object recognition)
      * Brief description: Complex everyday scenes of common objects in their natural context.
      * Take note that COCO has five annotations, for object detection, keypoint detection, stuff segmentation, panoptic segmentation, and         image captioning. The annotations are stored using JSON format. 
      * Instances: 2,500,000
      * Download: http://cocodataset.org/#download
      
    * PASCAL VOC (Object detection and classification) 
      * Brief description: Large number of images for classification tasks.
      * Instances: 500,000
      * Download: http://host.robots.ox.ac.uk/pascal/VOC/
      
    * CIFAR 10 (Classification)
      * Brief description: Many small, low-resolution, images of 10 classes of objects.
      * Instances: 60,000
      * Download: https://www.cs.toronto.edu/~kriz/cifar.html
      
    * CIFAR 100 (Classification) 
      * Brief description: Like CIFAR-10, above, but 100 classes of objects are given.
      * Instances: 60,000
      
    * OpenImage (Object Classification and Recognition) 
      * Brief description: A dataset of ~9M images annotated with image-level labels, object bounding boxes, object segmentation masks, and visual relationships.
      * Instances: 9,178,275
      * Download: https://storage.googleapis.com/openimages/web/factsfigures.html
      
    * ImageNet (Object and Scene Recognition) 
      * Brief description: Labeled object image database, used in the ImageNet Large Scale Visual Recognition Challenge.
      * Instances: 14,197,122
      * Download: http://image-net.org/download
