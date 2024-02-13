---
title: "Deep Learning Weight Pruning with RMT-SVD: Increasing Accuracy and Reducing Overfitting"
collection: publications
permalink: /publication/paper-4
excerpt: 'This paper applies random matrix theory techniques to prune the weight
            matrices of fully connected neural networks.
            
            Arxiv Preprint'
date: 2023-03-15
paperurl: 'https://arxiv.org/abs/2303.08986' 
---
In this work, we present some applications of random matrix theory for the training of deep neural networks. Recently, random matrix theory (RMT) has been applied to the overfitting problem in deep learning. Specifically, it has been shown that the spectrum of the weight layers of a deep neural network (DNN) can be studied and understood using techniques from RMT. In this work, these RMT techniques will be used to determine which and how many singular values should be removed from the weight layers of a DNN during training, via singular value decomposition (SVD), so as to reduce overfitting and increase accuracy. We show the results on a simple DNN model trained on MNIST. In general, these techniques may be applied to any fully connected layer of a pretrained DNN to reduce the number of parameters in the layer while preserving and sometimes increasing the accuracy of the DNN.