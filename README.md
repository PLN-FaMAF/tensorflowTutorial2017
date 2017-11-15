# Train and visualize a model in Tensorflow

## Overview

This [PyData San Luis Argentina
2017](https://pydata.org/sanluis2017/schedule/presentation/1/) tutorial will
focus on practical aspects of implementing and training deep learning models.
We will follow, step by step, the implementation of linear and nonlinear models
with Tensorflow, focusing on the impact of tuning hyperparameters and
architectures. To keep track of results we will use the visualization tool
Tensorboard and show its functionalities.

### Objective

The goal of this tutorial is for you to learn how to build models in
Tensorflow. You will apply them to a standard document classification dataset,
and keep track of the experiments' performance with Tensorboard, a
visualization tool. 

### Who is this course aimed to?

We strongly recommend to have covered some machine learning basic concepts
previously, as we wont cover them during the tutorial:

- What is a classifier? What is a logistic regression classifier?
- Basic evaluation: metrics like accuracy, precision, and recall. What is the
  train and test split for?
- What is gradient descent and what is a cost function?

## Technical requirements

This tutorial is based in [Jupyter notebooks](http://jupyter.org/) we uploaded
to the [Github platform](https://github.com/PLN-FaMAF/tensorflowTutorial2017).
The notebook named as [**Part 0:
Configuration**](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_0.ipynb)
(which can be rendered directly from Github) has all the software and data
requirements needed to configure the environment. It should be followed before
taking the tutorial in the conference.

### Course slides

The slides shown in the tutorial presentation are available [through this
link](https://docs.google.com/presentation/d/1IoIN5gJPFbvDv_IaIaLFwd6Y9RTVNAxz_5DIhLFZ4bA/edit?usp=sharing).

### Software

The software packages we are using are Python 3.5 (obtained through conda)
along Numpy, Scipy, Jupyter, and the
[Tensorflow](https://www.tensorflow.org/versions/r1.3/install/) (version 1.3)
libraries. 

Please refer to the
[notebook](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_0.ipynb)
for detailed explanation.

### Dataset

The dataset we will use is a pre-processed version of the [20 Newsgroup
Corpus](http://qwone.com/~jason/20Newsgroups/) for document classification.
[Part 1 of the
tutorial](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_1.ipynb)
is optional and explains how this dataset is obtained.  In any case it is
possible to download the dataset directly to use in Tensorflow from part 2 and
after of the tutorial.

Please refer to the
[notebook](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_0.ipynb)
for detailed explanation and download link.

## Structure

The Jupyter notebooks of the tutorial contain code and explanations that the
attendees can download, execute and modify during the talk. It will comprise
the following parts:

### Introduction and environment setup

This part is covered by the [Part 0:
Configuration](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_0.ipynb)
notebook. It has the instruction to configure the environment and download the
dataset to use.

### Dataset preprocessing (optional)

This part is covered by the [Part 1: Dataset
Preprocessing](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_1.ipynb)
notebook. It explains the dataset we are using to experiment with Tensorflow
and how we process it to have the final version ready.

### Basic concepts of Tensorflow

This part is covered by the [Part 2: The Basics of
Tensorflow](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_2.ipynb)
notebook. It explains the implementation of a linear model using a Tensorflow
estimator to exemplify the different components of the Tensorflow pipeline.
This includes compilation of models and how Tensorflow is executing your code.

### Advanced concepts of Tensorflow

This part is covered by the [Part 3: Advanced
Tensorflow](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_3.ipynb)
notebook. In this we will extend the linear model previously built into a
multilayer perceptron using a custom built estimator (instead of the default
provided by Tensorflow) using layers. We will cover the graph of Tensorflow and
how to visualize it with Tensorboard.

### The benefits of Tensorboard

This part is covered by the [Part 4: Inspecting the
model](https://github.com/PLN-FaMAF/tensorflowTutorial2017/blob/master/tensorflow_tutorial_4.ipynb)
notebook.  We will present the Tensorboard interface and how we can use it to
make the experimentation process easier by collecting and visualizing the
results.

---

## About the authors

### [Milagro Teruel](https://cs.famaf.unc.edu.ar/~mteruel/)

> I'm a Computer Scientist based in Córdoba, Argentina. I'm currently pursuing a
> PhD in Computing under the direction of Laura Alonso Alemany at Universidad
> Nacional de Córdoba and Marcelo Luis Errecalde, from the Universidad Nacional
> de San Luis. 

### [Cristian Cardellino](http://crscardellino.me)

> I have a degree in Computer Sciences from Universidad Nacional de Córdoba,
> Argentina, and I am finishing my PhD. in the area of machine learning applied
> to natural language processing.

