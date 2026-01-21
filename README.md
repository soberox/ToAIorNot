# ToAIorNot
This is a work-in-progress project where I use a fastai model to detect whether an image is AI-generated or not. This project was inspired by the courses and lectures made by fastai themselves. I’m doing this project out of curiosity and for practice; I’m still learning about deep learning, so the model used will need to be fine-tuned by me.

By clicking the link, you’ll be taken to a live demonstration hosted by Hugging Face. The website was made thanks to the Gradio library, and the model was trained using a fastai learner. You’ll be greeted by three sample images, where you can click on one of them to see the likelihood that the image is AI-generated. Aside from that, feel free to drag or upload any image and use my model to test it.

The model itself still needs work, as it performs well on some types of images but poorly on others. The model was also trained on older AI images, so it tends to be fooled by newer ones. I plan to expand the dataset, feed fresh data to the model, and experiment with other architectures that may yield better results.

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
