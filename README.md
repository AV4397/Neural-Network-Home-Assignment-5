Home Assignment 5

Course: Neural Networks and Deep LearningAssignment: Home Assignment 5 (Chapters 11–12)Author: Arvind Veda (700774397)

Project Overview

This repository contains two main components:

GAN on MNIST (gan_mnist.ipynb)

Implements a basic Generative Adversarial Network in PyTorch.

Generates sample digit images at epochs 0, 50, and 100.

Saves loss curves for both generator and discriminator.

Data Poisoning Simulation (data_poisoning.ipynb)

Trains a logistic regression sentiment classifier on a toy dataset.

Introduces a poisoning attack by flipping labels containing "UC Berkeley."

Compares performance before and after poisoning with plots.

Requirements

Python 3.8+

PyTorch

torchvision

matplotlib

scikit-learn

Install dependencies with:

pip install torch torchvision matplotlib scikit-learn

Running the GAN Script

python gan_mnist.py

Outputs:

samples/epoch_0.png, samples/epoch_50.png, samples/epoch_100.png

loss_curve.png

Running the Data Poisoning Simulation

python data_poisoning.py

Outputs:

poisoning_cm.png (clean vs poisoned confusion matrices)

poisoning_acc.png (accuracy bar chart)

Assignment Details

Chapters: 11–12 (GANs, Adversarial Attacks, Ethics)

Deliverables:

GAN architecture write‑up + diagram (in report)

Ethics scenario (allocational harm) + mitigations

PyTorch GAN code + outputs

Poisoning simulation code + outputs

Discussion of legal & ethical implications

Bias & fairness tool selection and analysis

Github Repo Link - https://github.com/AV4397/Neural-Network-Home-Assignment-5
