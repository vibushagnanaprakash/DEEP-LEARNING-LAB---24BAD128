# ANN Activation Functions and Optimization Algorithms

## Aim

To analyze the impact of different activation functions and optimization algorithms on the performance of Artificial Neural Networks (ANNs) and to learn best practices for managing deep learning experiments using cloud-based tools and version control.

## Objectives

- To understand the role of activation functions in neural networks.
- To visualize and compare Sigmoid, Tanh, and ReLU activation functions.
- To evaluate the performance of different activation functions in ANN models.
- To analyze different gradient-based optimization algorithms.
- To compare optimizer convergence and model accuracy.
- To learn experiment management using Google Colab, Google Drive, and GitHub.
- To maintain reproducible deep learning experiments using version control.

## Dataset

The MNIST Handwritten Digit Dataset was used for training and evaluating the Artificial Neural Network models.

The dataset contains grayscale images of handwritten digits from 0 to 9. Each image has a size of 28 × 28 pixels.

## Activation Functions Compared

The following activation functions were implemented and compared:

- Sigmoid
- Tanh
- ReLU

The activation functions were compared based on:

- Output range
- Saturation regions
- Gradient behavior
- Computational efficiency
- Typical applications

## Optimization Algorithms Compared

The following optimization algorithms were used:

- Stochastic Gradient Descent (SGD)
- SGD with Momentum
- RMSProp
- Adam

The optimizers were compared based on:

- Training loss
- Validation loss
- Convergence speed
- Training accuracy
- Validation accuracy

## ANN Architecture

The same ANN architecture was used for comparing the activation functions and optimization algorithms.

- Input Layer: 784 neurons
- Hidden Layer 1: 128 neurons
- Hidden Layer 2: 64 neurons
- Output Layer: 10 neurons

The output layer used the Softmax activation function for multi-class classification.

## Technologies Used

- Python
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Google Colab
- Google Drive
- GitHub

## Experiment Management

Google Colab was used to write and execute the deep learning experiments. Google Drive was used to store notebooks, trained models, and experiment results.

GitHub was used for version control and project management. The experiment files and documentation were uploaded to the repository, and changes were tracked using commits.

## Results

The activation functions were compared based on training accuracy, validation accuracy, training loss, validation loss, and convergence behavior.

ReLU generally showed faster learning and better gradient flow compared to Sigmoid and Tanh.

The optimizers were compared using training and validation loss graphs and accuracy graphs.

Adam generally showed faster convergence and stable performance compared to the other optimization algorithms.

## Conclusion

This experiment demonstrated the impact of activation functions and optimization algorithms on the performance of Artificial Neural Networks.

ReLU generally provided faster training and better gradient flow, while Sigmoid and Tanh showed different learning behaviors due to their mathematical properties.

Among the optimization algorithms, Adam generally provided fast and stable convergence because it combines adaptive learning rates with momentum-based optimization.

The experiment also provided practical experience in using Google Colab, Google Drive, and GitHub to manage, document, store, and reproduce deep learning experiments.

## Files in This Repository

- `ANN_Experiment.ipynb` – Google Colab notebook containing the complete experiment.
- `activation_results.csv` – Results of the activation function comparison.
- `optimizer_results.csv` – Results of the optimizer comparison.
- `README.md` – Documentation of the experiment.

## Student Details

**Name:** Vibusha G.  
**Roll Number:** 24BAD128  
**Department:** B.Tech Artificial Intelligence and Data Science
