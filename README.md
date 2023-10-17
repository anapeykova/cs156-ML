# cs156-ML

## #1 Pipeline

I trained a k-NN model to differentiate between my twin sister and me in a collection of childhood photos. Facial features in the input images were identified using dlib's facial landmarks recognition and then represented numerically as 128-dimensional vectors through a pre-trained Residual Neural Network model. I used grid search to optimize the model hyperparameters and assessed the binary classification using two metrics: accuracy and precision, each aligned with a slightly different problem formulation. The model does not perform well in respect to either of the measures, proving my point that my sister and I were indistinguishable as children.
