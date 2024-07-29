This project explores the integration of Bayesian Optimization (BO) algorithms into
a base machine learning model, specifically Convolutional Neural Networks (CNNs), for classifying
gravitational waves among background noise. The primary objective is to evaluate whether optimizing hyperparameters using Bayesian Optimization enhances the performance of the base model.
For this purpose, a Kaggle [1] dataset that comprises real background noise (labeled 0) and simulated gravitational wave signals with noise (labeled 1) is used. Data with real noise is collected
from three detectors: LIGO Livingston, LIGO Hanford, and Virgo. Through data preprocessing
and training, the models effectively classify testing data, predicting the presence of gravitational
wave signals with a remarkable score, 83.61%. The BO model demonstrates comparable accuracy
to the base model, but its performance improvement is not very significant (84.34%). However, it
is worth noting that the BO model needs additional computational resources and time due to the
iterations required for hyperparameter optimization, requiring an additional training on the entire
dataset. For this reason, the BO model is less efficient in terms of resources compared to the base
model in gravitational wave classification.
