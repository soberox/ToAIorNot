# ToAIorNot
This is a working-progress project, where I use a fastai model to detect if an image is AI generated or not. This project was inspired by the courses and lectures made by fastai themselves. I'm doing this project for curiosity and practice, I'm still learning about deep learning so the model used will need to be finetuned by me.

---

## 🔴 Live Demo

👉 **Try the live application here:**  
[https://huggingface.co/spaces/<your-username>/<your-space-name>](https://huggingface.co/spaces/brawl7787/AIorNot)

---

# AI vs Real Image Detector

This project is a computer vision application that determines whether an image is **AI-generated or real** using a trained deep learning model. The system is built with **FastAI** and **PyTorch**, and deployed as an interactive web application using **Gradio** on Hugging Face Spaces.

---

## 🧠 Model Overview

- **Architecture:** ResNet18  
- **Framework:** FastAI / PyTorch  
- **Task:** Binary image classification  
- **Classes:**  
  - `class_0` – Real image  
  - `class_1` – AI-generated image  

The model was trained on a curated dataset containing both real photographs and AI-generated images, learning visual artifacts and patterns characteristic of synthetic imagery.
