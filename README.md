Below is your README with an MIT License section added:

---

# zsl-open-class-detector

**ZSL Open Class Detector** is a Vision Transformer-based MAE model that detects whether an image belongs to a known class or performs zero-shot classification on unseen categories using masked autoencoding.

## Overview

This project demonstrates the use of a Vision Transformer (ViT) based Masked Autoencoder (MAE) to solve two related problems:
- **Seen/Unseen Detection:** Determine if an input image belongs to the set of classes on which the model was trained.
- **Zero-Shot Classification:** Identify and classify images from categories that were not present in the training dataset.

The approach leverages self-supervised learning techniques to reconstruct images and infer their properties, supporting both open-set recognition and zero-shot learning.

## Features

- **Hybrid Approach:** Combines reconstruction-based detection with Zero-Shot Learning (ZSL) for effective open-set recognition.
- **Masked Autoencoding:** Utilizes a state-of-the-art MAE model to generate image reconstructions.
- **Vision Transformer (ViT):** Employs a Transformer architecture optimized for image data.
- **CIFAR-10 Dataset:** Demonstrates training on a subset of classes while testing generalization on unseen classes.

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/siddhartha296/zsl-open-class-detector.git
cd zsl-open-class-detector
pip install -r requirements.txt
```

## Usage

1. **Training:** Run the training script to train the model on the known classes.
2. **Testing:** Use the testing script to evaluate the model on unseen classes, where the model performs zero-shot classification.

Example commands:

```bash
python train.py
python test.py
```

## Author

- **Siddhartha Pittala**  
  B.Tech Information Technology (2026)  
  VR Siddhartha Engineering College  
  [GitHub Profile](https://github.com/siddhartha296)
  [Linkedin Profile](https://www.linkedin.com/in/siddhartha-pittala-036001254/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
