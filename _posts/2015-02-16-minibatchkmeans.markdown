---
author: Kushal
layout: post
type: post
date: 2015-02-19 17:35
title: "MiniBatchKMeans"
category: tip
tags: []
---

Clustering datasets with high dimensions (>100K) can be very slow with KMeans. An alternate to KMeans for high dimensional dataset is MiniBatchKMeans.

MiniBatchKMeans is available for python in scikit-learn library.
While trying to cluster more than 1000 clusters you might notice that some of yhe clusters turn out to be empty. To fix the issue, increase the batch size and decreasing the reassingment ratio.



