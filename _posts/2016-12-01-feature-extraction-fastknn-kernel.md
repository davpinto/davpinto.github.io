---
layout: post
title: Feature Extraction with KNN
subtitle: Improving H2O GLM with KNN features from FastKNN
comments: true
tags: [rstats, machine-learning, fastknn, kaggle, tutorial]
---

I just wrote a [Kaggle kernel](https://www.kaggle.com/davidpinto/d/uciml/forest-cover-type-dataset/fastknn-show-to-glm-what-knn-see-0-96) showing how to use the `knnExtract()` method from my `R` package [fastknn](https://davpinto.github.io/fastknn/) to make a nonlinear mapping from the orginal features and improve [H2O GLM](http://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/glm.html) performance. The resulting method is very fast and performs better than **Random Forests** for the [Forest Cover Type](https://www.kaggle.com/uciml/forest-cover-type-dataset) dataset.

Take a look at it to learn how to use `fastknn` to improve your performance on **Kaggle** competitions, and let me know what you think!
