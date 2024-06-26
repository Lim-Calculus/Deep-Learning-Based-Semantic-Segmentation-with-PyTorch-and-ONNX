# Deep Learning-Based Semantic Segmentation with PyTorch and ONNX
![image](https://github.com/Lim-Calculus/Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX/assets/64350431/7e10d50e-0a73-46be-9e99-3d17915d00f8)

## Introduction
This project entails the development of a deep learning-based semantic segmentation model utilizing the PyTorch framework. Upon completion of the training phase, the model will be converted to the ONNX format to facilitate inference using ONNX Runtime. The segmentation model will be implemented using the segmentation_models.pytorch library, with the dataset sourced from the Human Segmentation Dataset. Following the training, the model will be converted to ONNX format for deployment purposes. The loss function employed will integrate Dice loss with binary cross-entropy (using logits=True). Given that the model's output is in logit form, a softmax activation will be applied to derive the final prediction mask.

## Final Predictions
![image](https://github.com/Lim-Calculus/Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX/assets/64350431/d8e32fcf-4d55-4ff5-8605-d5716f6c454d)
![image](https://github.com/Lim-Calculus/Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX/assets/64350431/70fb7bc4-9533-4393-bb7b-78d737b3df1e)
![image](https://github.com/Lim-Calculus/Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX/assets/64350431/841dbb23-99e0-44af-ac6f-22b3d6693fb2)

## References:
1. Deep Learning with PyTorch : Image Segmentation. (n.d.). Retrieved June 17, 2024, from https://www.coursera.org/projects/deep-learning-with-pytorch-image-segmentation
2. Export a PyTorch model to ONNX — PyTorch Tutorials 2.3.0+cu121 documentation. (n.d.). Retrieved June 17, 2024, from https://pytorch.org/tutorials/beginner/onnx/export_simple_model_to_onnx_tutorial.html
3. qubvel/segmentation_models.pytorch: Semantic segmentation models with 500+ pretrained convolutional and transformer-based backbones. (n.d.). Retrieved June 17, 2024, from https://github.com/qubvel/segmentation_models.pytorch






