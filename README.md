# Deep-Learning-Based-Semantic-Segmentation-with-PyTorch-and-ONNX
This project involves developing a deep learning-based semantic segmentation model using the PyTorch framework. After training, the model will be converted to the ONNX format and used for inference with ONNX Runtime.
I will be using the segmentation_models.pytorch library for the segmentation model, and the dataset will be sourced from the Human Segmentation Dataset. Once the model is fully trained, it will be converted to the ONNX format for deployment. The loss function will be a combination of Dice loss and binary cross-entropy (with logits=True). Since the model's output is in logits form, we'll apply a softmax activation to obtain the final prediction mask.


