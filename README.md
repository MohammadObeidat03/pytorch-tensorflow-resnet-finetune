🚀 pytorch-tensorflow-resnet-finetune

Implementation of two ResNet50 fine-tuning scenarios using PyTorch and TensorFlow:

Full Fine-Tuning
Training all pretrained ImageNet weights after replacing the final FC layer.

Frozen Backbone + Custom CNN + FC Head
Using ResNet50 as a fixed feature extractor while training only a newly added CNN + FC classification head.

This repository includes clean, modular code for experiments, comparison, and academic use.

🔗 Google Colab Notebook

You can view and run the complete implementation here:

👉 https://colab.research.google.com/drive/1XqW-rLxCmWjtQpWFAKl7YU8AW9W8eWp_?usp=sharing
