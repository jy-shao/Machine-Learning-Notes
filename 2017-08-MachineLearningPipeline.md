# Machine Learning Pipeline

## 1\. Introduction

This note presents a general pipeline to solve machine learning problems. It is for both:<br>

- (1) Problems with handcrafted features and solved by traditional machine learning algorithms such as: logistic regression, svm, CART (classification and regression tress), random forest,
- (2) Problem that are solved by End-to-End deep learning neural networks.

The difference for (1) and (2) in term of solution process is that:<br>

- For the 1st type of problem, there are usually two separate parts in solution process: (a) feature engineering and (b) use classification/regression/clustering/boosting/ensemble models to make predictions based on the handcrafted features.

- On the other hand, End-to-End deep learning models incorporate features (such as filters for image or embeddings for features) as part of learning parameters, and they were trained and refined together in training/optimization process (This learning to learn concept can also be extended to neural network structure selection).

## 2\. Machine Learning Problem Solution Pipeline

The note here is based on the well explained process in Chapter 18 from the book [Machine Learning With Python](http://machinelearningmastery.com/products/) by [Jason Brownlee](http://machinelearningmastery.com/about/).

### 2.1 General Outline

- (0) Define problem
- (1) Prepare data (e.g. folder/data structure, save in certain format/loading)
- (2) Review data (e.g statistic features and visualization)
- (3) Pre-processing and feature engineering
- (4) Evalutate algorithms (in a hierarchical way, e.g. from simple to complex)
- (5) Improve results (iterate over step 2 to 5, sometime even include step 1)
- (6) Finalize algorithm and predict

### 2.2 Define Problem

Before open a '.py' file and start coding, it is important to clearly define:

- What is problem we want to solve?
- What is the target variable to be predicted? What is the real impact/value of this variable?
- What kind of data is needed to solve the problem (necessary features, source of data, size of data)?
- What matrix we need to quantitatively evaluate the results?

### 2.3 Establish a Pipeline (WIP)

## 3\. Pipeline: Dimension Reduction Process of Machine Learning algorithms

On my way of solving machine learning problems, for both traditional algorithms as well as deep learning problems, I found that pipeline allows to solve and evaluate results systematically, and greatly minimize repetitive works. I think the reason is that, although there are lots of algorithms, machine learning problems can be classified into several categories (e.g. regression/classification/clustering/computer vision/NLP/reinforcement learning/generative problem). And a set of hierarchically grouped algorithms/techniques can be used to efficiently solve the same type of problems. Once this pipeline is established, one can quickly establish benchmark results by feed in pre-processed data. In some way, pipeline is a dimension reduction of machine learning algorithms and evaluation process :). The new axis is problem category.
