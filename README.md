# Fundus Super-Resolution Project

This project implements Super-Resolution for medical images (fundus) using EDSR with perceptual + SSIM loss.
Trained and tested on custom dataset.

## Training
```bash
python train.py
```

## Inference
```bash
python inference.py --input path/to/image.png --output outputs/result.png
```
