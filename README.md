# 🧑 Generate Faces — DCGAN

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

Generate new, realistic human faces using a **Deep Convolutional Generative Adversarial Network (DCGAN)** trained on the CelebA dataset. Part of the **Udacity Deep Learning Nanodegree** program.

## 📖 About

In this project, a DCGAN is defined and trained on a dataset of faces. The goal is to get a generator network to generate new images of faces that look as realistic as possible — similar to [thispersondoesnotexist.com](https://www.thispersondoesnotexist.com/).

The trained generator produces fairly realistic faces with small amounts of noise.

## ✨ Features

- 🧠 **DCGAN Architecture** — Deep Convolutional GAN for face generation
- 🎭 **CelebA Dataset** — Trained on celebrity face images
- 📓 **Full Notebook** — Complete training pipeline with visualizations
- ✅ **Unit Tests** — Included for model validation

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/Sanjays2402/Generate-Faces.git
cd Generate-Faces
conda create --name face_generation python=3.6
conda activate face_generation
conda install pytorch -c pytorch
pip install torchvision
pip install -r requirements.txt
```

### Run

Open `dlnd_face_generation.ipynb` in Jupyter Notebook.

## 📁 Project Structure

```
├── dlnd_face_generation.ipynb   # Main training notebook
├── dlnd_face_generation.html    # Exported notebook
├── problem_unittests.py         # Unit tests
└── requirements.txt             # Dependencies
```

## 👤 Author

**Sanjay Santhanam**

---

⭐ Star this repo if you found it useful!
