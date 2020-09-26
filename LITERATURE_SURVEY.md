Literature Survey

**A Study on Transfer Learning for Binary Classification**

Abstract

Binary classification is one of the most common and frequently tackled problems in the deep learning domain. It is generally applied when the user wants to classify an entity into one of the two possible categories. For an instance, given a dataset of labelled images of cats and dogs, we can apply binary classification to predict whether the image is of a cat or a dog. Though this seems like a trivial task, it does involve fair amount of underlying computation. This computation is based on incorporating the principles used for efficient classification by &#39;Intelligent Algorithms.&#39; One of those intelligent algorithms are Neural Networks. Through the effective use of neural networks, binary classification problems can be solved to a fairly high degree. In this literature survey, we are going to observe how Transfer Learning improves the performance of a neural network based deep learning model.

Introduction

Transfer Learning is the reuse of a pre-trained model on a new but similar problem. Basically, in transfer learning, a machine exploits the knowledge gained from a previous task to improve generalization about another i.e we transfer the weights that a network has learned in the previous task to the new task.

It&#39;s currently very popular in deep learning because it can train deep neural networks with comparatively little data. This is very useful in the data science field since most real-world problems typically do not have millions of labelled data points to train such complex models.

Use Cases

The general use case for using transfer learning is when we need to use the knowledge a model has learned from a task with a lot of available labelled training data in a new task that doesn&#39;t have much data. So that instead of starting the learning process from scratch, we start with patterns learned from solving a related task.

Transfer learning is mostly used in computer vision and natural language processing tasks like sentiment analysis due to the huge amount of computational power required. Transfer learning has several benefits, but the main advantages are saving training time, better performance of neural networks (in most cases), and not needing a lot of data

Popular Pre-Trained Models for Transfer Learning

Some of the very popular pre-trained models for Transfer Learning are as follows:

- VGG-16
- ResNet50
- Inceptionv3
- EfficientNet

VGG-16

VGG-16 is a convolutional neural network that is 16 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database [1]. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. As a result, the network has learned rich feature representations for a wide range of images.

ResNet is a short name for Residual Network. ResNet makes it possible to train up to hundreds or even thousands of layers and still achieves compelling performance.

Taking advantage of its powerful representational ability, the performance of many computer vision applications other than image classification have been boosted, such as object detection and face recognition.
