## Overview
This project uses a neural network model built with Keras to perform sentiment analysis on the IMDb dataset. The model achieves an accuracy of 86.49%.

## Model Architecture
The neural network consists of three layers:
1. Input Layer: A Dense layer with 16 units, using L1 and L2 regularization, and ReLU activation.
2. Hidden Layer: Another Dense layer with 16 units, using L1 and L2 regularization, and ReLU activation.
3. Output Layer: A Dense layer with 1 unit and sigmoid activation to output the probability of the sentiment being positive.
