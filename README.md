# Deep Learning for Satellite Image Analysis (Remote Sensing)

## Introduction

This includes short and minimalistic few examples covering fundamentals of Deep Learning for Satellite Image Analysis (Remote Sensing). Each chapter includes Python Jupyter Notebooks with example codes. And data used in example codes are also included in "data" folders.

It's recommended to use computer with an advanced GPU for these exercises. If GPU is not readily available, Google Colab (https://colab.research.google.com/) which provides free GPUs, can be used for these exercises.

These tutorials are consisted of example code segments explaining step by step process up to 2 applications of U-Net (building and land cover mapping) starting from basic  linear regression. Mathematics behind deep learning concepts is not explained here. And conceptual explanation with example code segments that can be adapt to any related problems are given and explained here.

## Libraries Used

Libraries used this tutorial are as follows,

* numpy
* matplotlib
* scikit-learn
* tensorflow (keras)

## Content

Content of this tutorial is as follows,

* Section 1: Getting Started with Machine Learning
  1) Linear Regression
  2) Logistic Regression
  3) Linear Regression - Multiple Input Variables
  4) PCA - Principle Component Analysis

* Section 2: Vanilla Neural Networks
  1) Regression with Neural Networks
  2) Classification (2 Classes) with Neural Networks
  3) Classification (Multi Classes) with Neural Networks

* Section 3: Convolutional Neural Networks (CNNs)
  1) Our first CNN (Classification Problem) - Hand Written Digit Recognition
  2) Image to Image Prediction (Transpose Convolution) - Face Masking

* Section 4: Case Study I - U-Net for Building Mapping
  1) U-Net for Building Mapping

* Section 5: Case Study II - U-Net for Land Cover Mapping
  1) U-Net for Land Cover Mapping

## Pre-requisites

Pre-requisites for this course are as follows,

  * Basics of Python programing with Numpy (numerical computing stuff)
  * Understanding about linear algebra and other basic mathematics is a plus here

## Acknowledgements

Created by [N. Lakmal Deshapriya](https://github.com/lakmalnd) for activites of Geoinformatics Center of Asian Institute of Technology, Thailand.

## References (for sample data used in exercises)
* SpaceNet. (2018). Spacenet on Amazon Web Services (AWS). ”Datasets.” The SpaceNet Catalog. https://spacenetchallenge.github.io/datasets/datasetHomePage.html.
* Huang, G. B., Ramesh, M., Berg, T., & Learned-Miller, E. (2007). Labeled faces in the wild: A database for studying face recognition in unconstrained environments (Tech. Rep. No. 07-49). University of Massachusetts, Amherst.
* Boguszewski, A., Batorski, D., Ziemba-Jankowska, N., Zambrzycka, A., & Dziedzic, T. (2020). LandCover.ai: Dataset for Automatic Mapping of Buildings, Woodlands and Water from Aerial Imagery. ArXiv, abs/2005.02264.
