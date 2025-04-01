# 🎨 Neural Style Transfer with PyTorch

This project implements Neural Style Transfer using a pre-trained VGG19 model in PyTorch. The goal is to generate a new image that combines the **content of one image** with the **style of another**.


---

## 🚀 Getting Started

### 1. Clone the Repository

### 2. Set Up Environment

pip install torch torchvision matplotlib numpy pillow

### 3. Run the Code

### 4. How It Works
Uses VGG19 pretrained on ImageNet

Extracts features from:

conv4_2 for content

conv1_1, conv2_1, conv3_1, conv4_1, conv5_1 for style

Computes:

Content loss (MSE between content and target)

Style loss (MSE between Gram matrices of style and target)

Optimizes a target image initialized from the content image using Adam



