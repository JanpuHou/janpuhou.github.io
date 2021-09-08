---
layout: post
title:  "Video Caption and Stock Prediction"
date:   2021-08-25 3:08:27 -0700
categories: jekyll update
---
![Alt Text](/assets/img/cnnrnn1.jpg)

Convolutional neural networks (CNN) form the backbone of many modern computer vision systems. The origins of CNNs, starting from biological experiments of the 1950s. Hubel and Wiesel proposed in 1962 that complex cells achieve spatial invariance by “summing” the output of several simple cells that all prefer the same orientation (e.g. horizontal bars) but different receptive fields (e.g. bottom, middle, or top of an image). By collecting information from a bunch of simple cell minions, the complex cells can respond to horizontal bars that occur anywhere.
This concept – that simple detectors can be “summed” to create more complex detectors – is found throughout the human visual system, and is also the fundamental basis of convolution neural network models.

Recurrent Neural Networks (RNN) were developed during the 1980s. Schmidhuber discovered in 1992 the vanishing gradient problem and therefore improved with Hochreiter the RNN to the Long Short-Term Memory (LSTM) in 1997. After that no major improvement happened a long time until in 2014 the Gated Recurrent Neural Networks (GRU) were introduced, which are kind of similar to the LSTM. 

Over the last few years everyone combine RNN with CNN and called them sometimes Recurrent CNN. Example of such approach is described in the paper of  Andrej Karpathy and  Li Fei-Fei: They connect a CNN and RNN in series and use this for labeling a scene with a whole sentence, so called image caption. An other approach from Ming Liang and Xiaolin Hu mixes a CNN with a RNN and use this architecture for better object detection or activity activity recognition.

![Alt Text](/assets/img/cnnrnn2.jpg)

Typically, the CNN is doing the feature extraction, and the RNN is doing the sequence learning. The common applications is for activity recognition, where sequence is in the input. For image caption the sequence is in the output. For video captions, the sequence is in both input and output. 

![Alt Text](/assets/img/cnnrnn3.jpg)

The CNN+RNN combined model become a common tool for combining computer vision(CV) and natural language processing(NLP). For example, you like to predict the stock price, and in addition to all the time series data from the trading price volume etc. you also have tons of financial news and financial reports associated with different time instance which is described in words. With word embedding, you can easily combine the financial information with the historical data to make prediction of the price and volume of a stock of interest.



