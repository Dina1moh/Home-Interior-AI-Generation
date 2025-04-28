# 🏠 Home Style AI Generation

[🔗 HuggingFace Project Repository](https://huggingface.co/dina301/Fine-Tuning-SDXL-lora-model)

[🔗 HuggingFace dataset_caption Repository](https://huggingface.co/datasets/dina301/interior-dataset-captions-en-blip2-opt-2.7b/viewer
)

[🔗 Image_caption(BLIP)_Final.ipynb](https://drive.google.com/file/d/1OxP5_srT-FuqPUHj44C1En9NRTgvLsCe/view?usp=drive_link
)

[🔗 Live Gradio Demo](https://drive.google.com/file/d/1synkCnIgLoTTMXtb6YEEf7-GnLLy1JDv/view?usp=sharing)

---

## 👩‍💻 Team Members

- Hager Hamed
- Naghem Naser
- Dina Mohammed
- Omnya Mohammed

Under Supervision:  
*Eng. Mohammed Agoor*  
_Instructor of Data Science & AI in Digital Egypt Pioneers Initiative_

---

## 📝 Project Description

We developed a deep learning system to generate high-quality interior design images based on text prompts.

We used Stable Diffusion XL (SDXL) fine-tuned with LoRA (Low-Rank Adaptation) to customize the model for creating stylish home interiors in various designs such as:
- Modern
- Rustic
- Minimalist
- And more!

This project addresses challenges like:
- Fine-tuning large diffusion models under limited resources (Google Colab T4 GPU)
- Applying LoRA, DreamBooth, and Custom Diffusion techniques
- Dataset preparation including:
  - Automatic captioning (using BLIP2)
  - Bilingual translation (using M2M100)

---

## 🛠 Techniques Used

- Stable Diffusion XL (SDXL)
- LoRA (Low-Rank Adaptation)
- DreamBooth Fine-tuning
- BLIP2 Image Captioning
- Gradio for Web UI Deployment

---

## 🚀 API Overview

The project also includes an API for generating home interior designs from text prompts using Gradio.

### Features
- Generate an image from a text prompt.
- Fine-tuned on interior design datasets.
- Supports fast web deployment.

---

## 🔥 Requirements

- torch
- transformers
- datasets
- huggingface_hub
- diffusers
- bitsandbytes
- accelerate
- peft
- Pillow
- matplotlib
- kaggle
- gradio

---

## ⚙️ Setup

1. Clone the repository:

    
    git clone <repository-url>
    cd <repository-folder>
    

2. Install dependencies:

    
    pip install -r requirements.txt
    

3. Setup environment variables:

    Create a .env file and add the following:

    
    HF_TOKEN=your_huggingface_token
    

4. Run the Gradio App:

    
    python app.py
