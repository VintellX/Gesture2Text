# Gesture2Text: An Image Processing Approach Using LSTM & CNN Models

This repository contains the code and resources for our project on comparing Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) models for hand gesture recognition and converting them into text.

## Installation
To get started with this project, clone the repository and install the necessary dependencies.

```bash
git clone "https://github.com/VintellX/Gesture2Text.git"
pip3 install -r requirements.txt
```

## Model Architechture

The project consists of two models:
- [CNN Model](./CNN_Model.ipynb)
- [LSTM Model](./LSTM_Model.ipynb)

### CNN 
The Convolutional Neural Network (CNN) model extracts spatial features from images using multiple convolutional layers, pooling layers, fully connected layers, and an output layer.

### LSTM
The Long Short-Term Memory (LSTM) model processes sequences of spatial features extracted from image sequences, capturing temporal dependencies with LSTM layers.

## License

This project is licensed under the [GNU General Public License v3.0](./LICENSE).
