# Paper-summerization--DEEP-LEARNING-MADE-EASIER-BY-LINEAR-TRANSFORMATIONS-IN-PERCEPTRONS-
‘DEEP LEARNING MADE EASIER BY LINEAR TRANSFORMATIONS IN
PERCEPTRONS’

Introduction and Aim of the Paper:
This paper talks about the Transformations for implementing Deep Neural Networks using short-connections architecture of two to five hidden layers deep to model and which is implemented to solve the problem of Image recognition in MNIST Handwritten digits and CFIAR-10 classification (using unsupervised autoencoder).Writer have first analyzed theoretically ,that transformations by noting , ‘they make Fisher information matrix close to a diagonal matrix and hence standard gradient closer to the natural gradient(Quasi-Newton’s Method or BFGS)[5]’ ,which is much faster algorithm for optimization of the model but due to harder implementation in higher dimensions it cannot be used.
Further, Proposed paper experimentally proves given the input as normalized (scaled) and centered (close to zero) values to address the problem of vanishing/exploding gradients, output is transformed according to the transformations which results in basic gradient descent can be applied as efficiently as other state-of-the-art algorithms in terms speed and even provides better generalization and be used on both supervised and unsupervised way of learning.
