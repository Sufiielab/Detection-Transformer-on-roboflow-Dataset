🎯 Custom Object Detection using DETR (DEtection TRansformer)
This repository demonstrates how to fine-tune Facebook AI’s DEtection TRansformer (DETR) for custom object detection tasks using PyTorch and Hugging Face's transformers library.

DETR combines a CNN backbone with a Transformer encoder-decoder to directly predict object bounding boxes and labels in an end-to-end fashion—no need for anchors, NMS, or hand-crafted pipelines.

📌 Highlights
✅ Fine-tuning DETR on a custom dataset

✅ Supports PyTorch Lightning for cleaner training loops

✅ Implements data augmentation & preprocessing using supervision

✅ Inspired by the Balloon dataset fine-tuning example

✅ Fully customizable for your own dataset

🛠️ Installation & Setup
Make sure to have Python 3.7+ installed. You can install all required packages using the following commands:

bash
复制
编辑
python -m pip install --upgrade pip

pip install supervision==0.3.0
pip install transformers
pip install pytorch-lightning
pip install timm
pip install cython
pip install pycocotools
pip install scipy


![image](https://github.com/AarohiSingla/Detection-Transformer/assets/60029146/363726ba-01d0-4856-80a7-f5adc103ee7e)

![image](https://github.com/AarohiSingla/Detection-Transformer/assets/60029146/297a2dae-7525-4bdb-8f40-6571fa201160)
![image](https://github.com/AarohiSingla/Detection-Transformer/assets/60029146/55fe0e82-e744-4787-9567-49d764928a3c)




📖 Recommended Reading
Original DETR Paper (2020)
End-to-End Object Detection with Transformers
📄 https://arxiv.org/abs/2005.12872

Official Facebook DETR GitHub
🔗 https://github.com/facebookresearch/detr
📊 Results & Evaluation
Add your model performance here (example):

mAP: 0.71 @ IoU=0.5

Epochs: 50

Dataset: Custom (e.g., Balloon, or replace with your own)

Hardware: NVIDIA RTX 3090
