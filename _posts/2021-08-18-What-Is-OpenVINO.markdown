---
layout: post
title:  "What is OpenVINO"
date:   2021-08-18 3:08:27 -0700
categories: jekyll update
---
![Alt Text](/assets/img/openvino1.jpg)

Intel Movidius chip is about speeding up inference and not training. OpenCV or OpenVINO does not provide you tools to train a neural network. You need to train your network with TensorFlow or PyTorch alike. For inference on edge device(such as Raspberry Pi), you will need addtion tool to squeeze your trained TensorFlow model into edge devices. OpenVINO is such tool to squeeze your trained model into Intel edge devices. 

OpenVINO (Open Visual Inference and Neural Network Optimization) is a toolkit which allows to run deep learning models across various Intel specific hardware devices like Intel CPUs (Xeon, Core and Atom), Intel Integrated GPUs (HD Graphics and Iris), VPUs (Movidius Neural Compute Stick 2), Intel FPGAs (Vision Accelerator and Programmable Acceleration Card) etc., with just a few lines of codes. 

![Alt Text](/assets/img/openvino2.jpg)

To install your trained model into Raspberry Pi with Movidius Neural Compute Stick you need to intall the OpenVINO on your Raspberry Pi first.

! [Installation on Raspberry Pi](https://docs.openvinotoolkit.org/latest/openvino_docs_install_guides_installing_openvino_raspbian.html)

The model obtained in the training step is usually not optimized for inference on Intel edge devices. Therefore, instead of directly using the trained model for inference, OpenVINO requires us to create an optimized model which they call Intermediate Representation (IR) using a Model Optimizer tool they provide. IR is completely hardware agnostic and only depends on the architecture of the neural network.

! [Object detection with Movidius on Raspberry Pi](https://www.youtube.com/watch?v=KOFexecHZp4&ab_channel=JanpuHou)

