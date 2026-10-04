# First TFLite Micro Inference

## Aim

To deploy a small TensorFlow Lite model on an ESP32 using TensorFlow Lite Micro and predict a class from a sample input.

## Technologies

* Python and TensorFlow
* TensorFlow Lite
* TensorFlow Lite Micro
* ESP32 and ESP-IDF

## Classes

* Dark
* Normal
* Bright

## Working

A small neural network is trained in Google Colab and converted into TensorFlow Lite format. The model is embedded into the ESP32 firmware as a C array. The ESP32 executes model inference on a sample input and prints the predicted class through the serial monitor.

## Result

A TensorFlow Lite model is deployed on the ESP32, and a predicted class is displayed through the serial monitor.
