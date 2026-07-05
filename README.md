# genai-text-generator
# Character-Level GPT Text Generator from Scratch

This repository contains a lightweight, self-contained implementation of an autoregressive Generative Pre-trained Transformer (GPT) decoder built entirely from scratch using PyTorch.

## 🚀 How to Run this Project in Google Colab

The easiest way to run this code is directly in your browser:

1. Go to [Google Colab](https://colab.research.google.com/).
2. Click **New Notebook**.
3. In the top menu, click **Runtime** -> **Change runtime type**. Select **T4 GPU** and click **Save**.
4. Copy the Python code from this project, paste it into the cell, and press the **Play (▶️)** button.

## 📊 Expected Deliverables
* **Training Logs:** Prints cross-entropy loss tracking metrics every 200 iterations.
* **Loss Curve:** Generates a learning progression plot (`loss_curve.png`).
* **Text Generation:** Automatically completes a copywriting prompt starting with `"The world "`.
