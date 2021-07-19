---
layout: post
title:  "Time Series Clustering for Cloud Service Provider"
date:   2021-07-19 3:08:27 -0700
categories: jekyll update

---

#### What is Cloud Service Provider?

![Alt Text](/assets/img/CSP_ms.jpg)

Artificial Intelligence applications in the telecommunications industry are increasingly helping Cloud Solution Provider (CSP) manage, optimize and maintain not only infrastructure, but also customer support operations. The Microsoft Cloud Solution Provider Program enables partners to directly manage their entire Microsoft cloud customer lifecycle. Partners in this program utilize dedicated in-product tools to directly provision, manage, and support their customer subscriptions.

#### What is Time Series Clustering?

![Alt Text](/assets/img/similar.jpg)What is Time Series Clustering?

Time series are a common data type and they are widely used in diverse application areas, such as finance, economics, communication, automatic control, and online services, etc. Clustering time series is to identify the homogeneous groups of time series data based on their similarity. Fast and scalable clustering of time series is essential to completing these tasks since grouping provides common performance profiles across servers or services. Moreover, clustering transforms time series data into categorical attributes, thus making it possible to analyze time series data together with other categorical attributes.

Large datacenters may have tens of thousands or even more servers running and hosting different services. In order to ensure service quality, various types of performance counters (e.g., CPU usage, disk I/O, network throughput, etc.) are continuously collected on each server. For analysis purpose, they are often aggregated at pre-defined time intervals (e.g., 5 minutes) on each server, resulting in time series representing certain performance characteristic of the service(s) under monitoring.

Most of the existing time series clustering algorithms fall into two categories, depending on whether the similarity measures are defined directly on input data, or on the features extracted, for example, Fourier Transform into frequency domain from input data. Clustering is a measure of the similarity, and group similar objects together. 

#### Application of Time Series Clustering for Cloud Service Provider

![Alt Text](/assets/img/clustering.jpg)

To meet with different storage requirements, lots of products are provided by cloud service providers. These products vary greatly in price and performance. Choosing different storage services to build tiered storage systems could reduce overall costs of using of cloud services. But choosing of storage services is not easy because it must meet storage performance requirements and minimize the costs. Log files that keep storage access traits are used to analyze storage access patterns. Once we process log files and generate access frequency time series, we can extract feathers from such time series and use K-Means clustering method to classify storage objects. Then we can recommend different migration policies for our customers to optimize storage usages according to these different classes of storage objects.  

