# Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX
![image](https://github.com/Lim-Calculus/Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX/assets/64350431/7e10d50e-0a73-46be-9e99-3d17915d00f8)

## Introduction
This project involves developing a deep learning-based semantic segmentation model using the PyTorch framework. After training, the model will be converted to the ONNX format and used for inference with ONNX Runtime.
I will be using the segmentation_models.pytorch library for the segmentation model, and the dataset will be sourced from the Human Segmentation Dataset. Once the model is fully trained, it will be converted to the ONNX format for deployment. The loss function will be a combination of Dice loss and binary cross-entropy (with logits=True). Since the model's output is in logits form, I will apply a softmax activation to obtain the final prediction mask.

## Final Predictions
![image](https://github.com/Lim-Calculus/Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX/assets/64350431/d8e32fcf-4d55-4ff5-8605-d5716f6c454d)



