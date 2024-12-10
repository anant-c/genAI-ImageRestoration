# Image Restoration using GANs
![image](https://github.com/user-attachments/assets/cd9283ff-a6f6-41f9-9c09-e1b35d1a7274)


This repository contains code for training and inference of a GAN-based image restoration model. The generator is designed using a U-Net architecture, and the discriminator is implemented as a PatchGAN. The model has been evaluated using average SSIM (Structural Similarity Index Measure) and PSNR (Peak Signal-to-Noise Ratio) values.

## Features
- **Generator**: U-Net-based architecture for generating restored images.
- **Discriminator**: PatchGAN architecture for improving the quality of restored images.
- **Evaluation Metrics**: SSIM and PSNR are used to evaluate the performance of the model.
  ![image](https://github.com/user-attachments/assets/f5e605b3-142f-492d-877c-e408ac443cfa)

- **Pretrained Weights**: Pretrained model weights are available for inference.

---

## Requirements
- Python 3.8+
- TensorFlow 2.2 or higher
- Required Python packages (install using `pip install -r requirements.txt`)
---

## Usage

### 1. Inference
The code for running the inference is provided in the notebook at last.
To run an inference with pre-trained weights:
1. Download the pre-trained weights from the https://drive.google.com/file/d/1IS_UAi6eDpTFtRzr_CwzmSYb0588YqJx/view?usp=sharing then provide the relative path in the code to it.
2. Use the provided notebook or script to load the model and run inference on your input images.

### 2. Training the model
Training is available in the model itself. You just need to update the relative paths of the dataset used. Rest for the architecture it is mentioned in the report of the project linked.<br>
**Dataset link:** https://www.kaggle.com/datasets/bharatadhikari/humanface8000
In the dataset, the color folder contains the good images without any damage and the gray folder contains images with damage.
