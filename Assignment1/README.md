# Assignment 1

Welcome to our first assignment!

### Access
You can open the assignment by downloading the notebook [(26F_CS163_Assignment1.ipynb)](./26F_CS163_Assignment1.ipynb) locally and upload it to Google [Colab](https://colab.research.google.com/).

### Goals
In the first assignment, you will learn:
* How to use Google Colab
* How to implement a PyTorch data loader to load and preprocess the MiniPlaces dataset.
* How to implement a linear/logistic/softmax regression classifier
* How to build and train a fully-connected neural network from scratch and using built-in PyTorch modules.

Free free to raise issues in the Piazza forum if you find any bugs or have any questions about the assignment. 

Please do not directly copy code from other sources.

Please **do not use any Code AI** to derive the answers to the questions.

This assignment is due on **Tuesday, October 13**.

❗**Once you have finished all the questions, it will still take approximately *60 minutes* to re-run the entire notebook in order to prepare the submission version. Make sure to allocate enough time for this task and start early.**

### Submission
Submit a rendered PDF of the notebook and the .ipynb file to Gradescope. Make sure you have completed all the code implementations with all the results printed(marked as **Your Implementations **), and answered all the blanks at the end of each question.

---

### Overview

In this assignment, you will be working with the [MiniPlaces dataset](https://github.com/CSAILVision/miniplaces), a small-scale version of the [Places2 dataset](http://places2.csail.mit.edu/), which is a large-scale dataset of scene images (10+ million images) with a wide variety of real-world environments (400+ unique scene categories). The MiniPlaces dataset is a subset of the [Places2 dataset](http://places2.csail.mit.edu/) and contains 100,000 images for training, 10,000 images for validation, and 10,000 images for testing, each of which has been annotated with one of 100 different scene categories. These images are divided into three folders: train, val, and test. 

The MiniPlaces dataset is a useful resource for developing and testing image classification models, particularly those that are designed to recognize different types of environments and scenes.

In this assignment, you will use PyTorch to load the MiniPlaces dataset and compare different image classification methods including linear/logistic/softmax regression classifier and a fully-connected neural network.

Throughout the course, we will be using [PyTorch](https://pytorch.org/) for building and training different neural networks. It would be highly beneficial to go through the PyTorch [tutorials](https://pytorch.org/tutorials/) and get familiar with its APIs.

---
Good luck with your work!
