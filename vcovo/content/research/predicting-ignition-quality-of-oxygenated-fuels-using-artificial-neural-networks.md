+++
title = 'Predicting Ignition Quality of Oxygenated Fuels Using Artificial Neural Networks'
date = 2021-05-05
tags =['machine-learning']
draft = true
+++

DOI: [10.4271/04-14-02-0005](https://doi.org/10.4271/04-14-02-0005)

## Contribution

## Abstract
Artificial intelligence-based computing systems like artificial neural networks (ANN) have recently found increasing applications in predicting complex chemical phenomena like combustion properties. The present work deals with the development of an ANN model that can predict the derived cetane number (DCN) of oxygenated fuels containing alcohol and ether functionalities. Experimental DCNs of 499 fuels comprised of 116 pure compounds, 222 pure compound blends, and 159 real fuel blends were used as the dataset for model development. DCN measurements of sixty new fuels were carried out in the present work, and the data for the rest were collected from the literature. Fuel chemical composition expressed in the form of eight functional groups, namely, paraffinic CH3 groups, paraffinic CH2 groups, paraffinic CH groups, olefinic -CH=CH2 groups, naphthenic CH-CH2 groups, aromatic C-CH groups, alcoholic OH groups, and ether O groups, along with two structural parameters, namely, molecular weight and branching index (BI), were used as the ten input features of the model. The qualitative and quantitative determination of functional groups present in real fuels was performed using 1H nuclear magnetic resonance (NMR) spectroscopy. A robust ANN methodology was then applied to prevent overfitting, using a multilevel grid search and genetic algorithm. The final developed model with two hidden layers was tested with 15% of randomly generated unseen points from the dataset, and a regression coefficient (R2) of 0.992 was observed between the experimental and predicted DCN values. An average absolute error of 0.91 obtained from the test set indicates that the developed ANN model is successful in predicting the DCN of oxygenated fuels and captures the dependence of the fuel’s ignition quality (i.e., DCN) on its constituent functional groups.