# 🧠 PokeScan — Pokémon Image Classification

PokeScan is a deep learning-based image classification project that identifies Pokémon from uploaded images.  
It uses a convolutional neural network (CNN) trained on a curated dataset of Pokémon images to accurately classify Pokémon species based on user-provided images.

---

## 📌 Project Overview

PokeScan allows users to:

- Upload a Pokémon image
- Run a deep learning model to predict which Pokémon it is
- View prediction results directly

This repository contains the trained model, dataset references, and code used to build and test the classifier. It’s ideal for anyone interested in computer vision, deep learning, and Python-based AI projects.

---

## 📦 Dataset Information

### 🐾 Pokémon Image Dataset

We used the following dataset for training and testing:

🔗 **Dataset URL:**  
[Pokémon Image Dataset on Kaggle](https://www.kaggle.com/datasets/lovekmr/image-dataset)

This dataset contains labeled Pokémon images in folders per Pokémon class, suitable for supervised image classification.  

### 📊 About the Dataset

- Thousands of images covering multiple Pokémon characters  
- Different poses and styles included  
- Structured format with class labels  
- Useful for deep learning practice and model training  

---

## 🔧 Installation & Setup

### 🧾 Prerequisites

- Python 3.8+  
- Git  
- Jupyter Notebook or VS Code  
- (Optional) Git LFS for large model files  

---

### 🐍 Step 1 — Clone & Installing the Repository

```bash
git clone https://github.com/byteblud/Pokescan.git
cd Pokescan

# ========================================================
# Step 1, 2 & 3 Combined — Clone Repo, Setup Virtual Env, Install Dependencies
# ========================================================

# 1️⃣ Clone the repository
git clone https://github.com/byteblud/Pokescan.git
cd Pokescan

# 2️⃣ Create a virtual environment named 'venv'
python -m venv venv

# 3️⃣ Activate the virtual environment
# Windows:
venv\Scripts\activate
# macOS / Linux:
# source venv/bin/activate

# 4️⃣ Upgrade pip (optional but recommended)
python -m pip install --upgrade pip

# 5️⃣ Install dependencies
# If requirements.txt exists:
pip install -r requirements.txt
# If requirements.txt does NOT exist, install manually:
pip install tensorflow numpy pandas matplotlib jupyter pillow

# ✅ All done! Virtual environment is ready and dependencies installed.
# You can now run Jupyter Notebook or Python scripts inside this environment.
echo You can now run Jupyter Notebook or Python scripts inside this environment.
