Project Title: Neural Network Library and Taxi Trip Duration Prediction

Project Overview
This project involves developing a custom neural network library and applying it to solve two distinct problems: classifying the XOR function and predicting NYC taxi trip durations. The project provides an in-depth understanding of neural networks, backpropagation, and model evaluation techniques.

Key Features and Implementations

1. Custom Neural Network Library  
   - Designed and implemented a neural network library that allows users to construct models with a flexible number of layers and nodes.  
   - The library provides a modular approach to building deep learning models.  

2. Implemented Core Neural Network Layers  
   - Developed essential layers, including Linear, Sigmoid, ReLU, and Binary Cross-Entropy Loss.  
   - Each layer includes properly defined forward and backward propagation functions to facilitate learning.  

3. Sequential Model Implementation  
   - Created a Sequential class to manage and train multiple layers efficiently.  
   - This structure ensures ease of use when stacking multiple layers together.  

4. Model Persistence (Saving & Loading)  
   - Implemented functionality to save and load trained model weights, allowing easy reuse and deployment.  

5. Solving the XOR Problem  
   - Built and trained a neural network to classify the XOR function using a hidden layer with two nodes.  
   - Tested the model with Sigmoid and Tanh activation functions, analyzing which activation led to better convergence.  

6. Predicting NYC Taxi Trip Durations  
   - Used the custom neural network library to construct models for predicting NYC taxi trip durations.  
   - Conducted extensive feature selection and preprocessing, transforming dataset features to improve model performance.  

7. Hyperparameter Tuning and Model Selection  
   - Experimented with different model architectures, including varying the number of layers and nodes per layer.  
   - Used early stopping to prevent overfitting by halting training when validation loss stopped improving.  
   
8. Benchmarking and Performance Analysis  
   - Compared model performance against a baseline neural network with 3 layers using ReLU activations.  
   - Achieved a competitive RMSLE score by carefully selecting relevant features and applying proper normalization techniques.  

Conclusion
This project demonstrates expertise in building deep learning models from scratch, implementing core neural network operations, and optimizing models for real-world applications. The neural network library provides flexibility in constructing models, and its application to solving XOR and taxi trip duration prediction showcases the ability to apply machine learning effectively in different domains.

