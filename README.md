# 🎨 Gen AI Text-to-Image

A **Generative AI Text-to-Image** project using **Stable Diffusion v1.5**.
This notebook demonstrates how to generate high-quality AI images from text prompts using **Hugging Face Diffusers** and **PyTorch**.

---

## 🚀 Features

* Generate realistic images from text descriptions
* Uses the pre-trained **Stable Diffusion v1.5** model
* Easy to run on **Google Colab** with GPU support
* Simple and beginner-friendly implementation

---

## 🧩 Requirements

Install all dependencies before running the notebook:

```bash
pip install transformers diffusers torch pillow gradio
```

If you're running locally with a CUDA GPU, you can install GPU-enabled PyTorch:

```bash
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

---

## 💻 How to Run

1. Open the Jupyter/Colab notebook:

   ```bash
   Text_to_Image.ipynb
   ```

2. Make sure your runtime has a **GPU** (recommended).

3. Run all cells.
   When prompted, enter your **Hugging Face token** (you can create one [here](https://huggingface.co/settings/tokens)).

4. Enter any descriptive text and generate your AI image 🎨

---

## 🧠 Model Used

* Model: [`runwayml/stable-diffusion-v1-5`](https://huggingface.co/runwayml/stable-diffusion-v1-5)
* Framework: [Hugging Face Diffusers](https://github.com/huggingface/diffusers)
* Backend: PyTorch

---

## 🖼️ Example

| Prompt                           | Example Output            |
| -------------------------------- | ------------------------- |
| “A fantasy castle on a mountain” | 🏰 *(AI-generated image)* |
| “A futuristic city at night”     | 🌃 *(AI-generated image)* |

---



---

## 📦 requirements.txt

```
transformers
diffusers
torch
pillow
gradio
```


