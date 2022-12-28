Uncertainty quantification - in brain MRI images using Bayesian CNN.

Introduction :
Jupyter notebook walks thru building probablistic deep learning models. These models incorporate distribution into the model architecture using 
Tensorflow probability.
As a example we will analyze and build probabilistic deep learning model to classify brain tumor using brain MRI images(training dataset is from Kaggle).
The main advantage for applying probablistic approach to deep learning is that it provides a means for dealing with uncertainty involved in the modeling process. This is very important for cirtical application where there is high penalty for inaccurate prediction, such as medical diagnoses.

Data: 
Brain MRI images from Kaggel. Added red noise to these images to analyze the probabilistic prediction made by models.
