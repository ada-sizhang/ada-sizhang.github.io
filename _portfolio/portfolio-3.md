---
title: "Low-thrust transfer cost estimation based on Deep Learning"
excerpt: "This project is using machine learning techiniques to etimate low-thrust transfer cost without performing the actual optimisation. This technique greatly reduces the computation time and the accuracy outperforms and analytical solution, these two features enable more complex mission designs."
collection: portfolio
date: 2020-05-01
---

## Highlights
* A DNN classifier improves the low-thrust optimisation convergence rate from 7% to over 98%.
* An online DNN regressor with mean relative error of 0.6%.
* A scalable online framework that can efficiently construct, train, optimise and update DNN models for low thrust trajectory optimisation.
* Applicable to scenarios such as Main-Belt Asteroid missions and Active Debris Removal missions.

## Introduction
In the preliminary interplanetary mission design stage, a fast low-thrust (LT) transfer cost approximator will improve the mission design efficiency and enable us to design more complex missions. In this study, we propose a Deep Neural Network (DNN) based on-line framework for training approximators for fast low-thrust trajectory optimisation. The online characteristic refers to the ability to continuously adjust the trained DNNs using new LT transfer data from newly found asteroids, which avoids repeated and costly re-training and is particularly useful for mission scenarios where new data are obtained regularly. The framework contains a DNN-classifier and an online-DNN regressor. The Bayesian optimisation (BO) technique is adapted to determine the network structure as well as the feature selection and processing methods. The proposed DNN-classifier significantly improves the LT optimisation convergence rate from 7% to over 98%. The proposed on-line DNN regressor proves to have better generalization ability and scalability comparing to series network structure, giving a mean relative error (MRE) of approximately 0.6% in the test Near-Earth Asteroid (NEA) rendezvous mission scenario. The proposed on-line DNN framework can also be extended to solve other trajectory optimisation problems in other mission scenarios, such as Main-Belt Asteroid (MBA) missions, active debris removal mission (ADR), etc.


See the data release page to access the low thrust transfer data. You may use the data to train and test your models.

Current the DNN-based approximation technique and workflow are well developed. But we are seeking further performance improvements

![DNN approximation workflow](/images/project3.png "DNN approximation workflow")

## Related Publications
* Xie, R. and Dempster, A.G., 2022. Low-thrust Accessibility Evaluation for Near-Earth Asteroids. IEEE Aerospace Conference.(Accepted)
* Xie, R. and Dempster, A.G., 2021. Feasible low-thrust trajectory identification via a deep neural network classifier. 2021 AAS/AIAA Astrodynamics Specialist Conference
* Xie, R. and Dempster, A.G., 2021. An on-line deep learning framework for low-thrust trajectory optimisation. Aerospace Science and Technology, 118, p.107002.

