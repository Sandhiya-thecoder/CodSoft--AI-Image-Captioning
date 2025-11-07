<h1 align="center">🖼️ Image Captioning using Vision Transformer + GPT-2</h1>

<p align="center">
An advanced AI project that generates natural language descriptions for images using the powerful <b>ViT-GPT2</b> model.  
It combines <b>Computer Vision</b> and <b>Natural Language Processing</b> to understand images and describe them like a human! 🤖✨
</p>

---

## 🧠 Overview

This project demonstrates **Image Captioning** — an AI technique that automatically generates textual descriptions for images.  
It uses a **Vision Transformer (ViT)** as the image encoder and **GPT-2** as the language decoder, fine-tuned together using the `nlpconnect/vit-gpt2-image-captioning` model from Hugging Face.

---

## ⚙️ Features

- 🧩 Generates human-like captions for any input image  
- ⚡ Uses **pretrained ViT-GPT2 model** for fast, high-quality results  
- 💻 Supports both **CPU and GPU (CUDA)**  
- 📷 Works with any image format (JPG, PNG, etc.)  
- 🔁 Simple, reusable Python function `predict_step()`  

---

## 🎯 Learning Objectives

By studying this project, you will:
- Understand how **Vision Encoder-Decoder** models work  
- Learn how to use **Transformers** for image-to-text generation  
- Practice loading and running **pretrained Hugging Face models**  
- Explore the integration of **Computer Vision** and **NLP**

---

## 🧰 Requirements

Install the required dependencies before running the code:

```bash
pip install transformers torch pillow
