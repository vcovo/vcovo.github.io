+++
title = 'Machine Learning to Predict Standard Enthalpy of Formation of Hydrocarbons'
date = 2019-08-29
tags =['machine-learning']
draft = false
+++

DOI: [10.1021/acs.jpca.9b04771](https://doi.org/10.1021/acs.jpca.9b04771)

## Contribution

In this study, my key contribution was developing and implementing Artificial Neural Networks (ANNs) and Support Vector Regression (SVR) models. These models were engineered to accurately estimate the standard enthalpy of formation for a variety of hydrocarbons. I optimized these models using a two-level K-fold cross-validation method, enhancing both accuracy and reliability.

Additionally, I was responsible for defining the hyperparameter search space for these models, ensuring a balance between model complexity and generalizability. This careful tuning was vital to prevent overfitting while maintaining high predictive accuracy. The models I developed notably surpassed conventional methods in predicting standard enthalpy of formation, marking a significant advancement in the fields of chemical kinetics and thermodynamics.

The developed code in addition to the results can be found [here]](https://github.com/vcovo/enthalpy-prediction).

## Abstract

Thermodynamic properites of molecules are used widely in the study of reactive processes. Such properties are typically measured via experiments or calculated by a variety of computational chemistry methods. In this work, machine learning (ML) models for estimation of standard enthalpy of formation at 298.15 K are developed for three classes of acyclic and closed-shell hydrocarbons, viz. alkanes, alkenes, and alkynes. Initially, an extensive literature survey is performed to collect standard enthalpy data for training ML models. A commercial software (Dragon) is used to obtain a wide set of molecular descriptors by providing SMILES strings. The molecular descriptors are used as input features for the ML models. Support vector regression (SVR) and artificial neural networks are used with a two-level K-fold cross-validation (K-fold CV) workflow. The first level is for estimation of accuracy of both the ML models, and the second level is for generation of the final models. The SVR model is selected as the best model based on error estimates over 10-fold CV. The final SVR model is compared against conventional Benson’s group additivity for a set of octene isomers from the database, illustrating the advantages of the proposed ML modeling approach.
