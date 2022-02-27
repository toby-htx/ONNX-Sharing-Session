# ONNX Sharing Session

The brainchild of Microsoft, AWS, and Facebook, Open Neural Network Exchange (ONNX) is an open/common format to represent AI models. It offers 2 advantages:

**1) Interoperability**

The same model can now be used across different frameworks by first converting it to an ONNX model. This new ONNX model can then be converted to other frameworks. To showcase this, in our first demo, we are going to convert a BiLSTM model written in the PyTorch framework to ONNX format, then convert the new ONNX model into a Tensorflow model.  

**2) Hardware Access**

Previously, models had to be exported using a hardware's toolkit to optimise its performance on the hardware. With each hardware having its own toolkit, it meant machine learning engineers had the extra step/hassle of learning different toolkits. However, with ONNX Runtime serving as a common runtime, an ONNX model can now run across different hardware (eg. CPU, GPU) without the need to use any extra toolkit. We will show an example in our second demo by converting a BiLSTM model written in the Tensorflow framework to ONNX format and running it with ONNX Runtime, which also promises faster inference speeds.

## Instructions

![image](https://user-images.githubusercontent.com/81354022/155877909-1be4b9cc-abc7-4830-902e-32eeb1327f51.png)
