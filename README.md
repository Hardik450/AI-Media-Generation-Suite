

# 🧠 AI Media Generation Suite — Text, Image, Audio & Video with Gemini & Kokoro

This repository showcases a collection of **Jupyter Notebooks** that explore **Google’s Gemini AI** and **Kokoro** for multimodal content generation — including **text extraction from images (OCR)**, **AI image generation**, **AI video creation**, and **AI audio synthesis**.

---

## 🚀 Features

### 🖼️ Gemini Vision

* Extracts and explains text directly from images (OCR + context-aware understanding).
* Supports multiple image inputs and provides clean, structured text output.

### 🎨 Gemini Image Generation

* Generates creative images from text prompts using Gemini’s multimodal capabilities.
* Supports prompt tuning and batch generation.

### 🎥 Gemini Video Generation

* Experimental notebook for generating **short AI videos** or **animated visual sequences** from text prompts.

### 🔊 Kokoro Audio Generation

* Generates **natural-sounding AI speech** from any text input.
* Ideal for narration, podcasts, or educational voiceovers.
* Supports multiple voices and tonal variations.

---

## 📁 Repository Structure

```
📂 AI-Media-Generation-Suite
│
├── 📘 gemini_text_image_video.ipynb   # Notebook using Gemini for OCR, image, and video generation
├── 🎧 kokoro_audio_generation.ipynb    # Notebook using Kokoro for AI audio/speech generation
│
├── README.md                           # You are here
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Hardik450/AI-Media-Generation-Suite.git
cd AI-Media-Generation-Suite
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` isn’t present yet, here’s a sample you can create:

```txt
google-generativeai
pillow
requests
torch
transformers
```

### 3️⃣ Set Up API Keys

You’ll need valid API keys for **Gemini**.

Create a `.env` file (or set environment variables) as follows:

```
GOOGLE_API_KEY=your_gemini_api_key_here
```

In the notebooks, make sure to load them like:

```python
import os
from dotenv import load_dotenv
load_dotenv()
api_key = os.getenv("GOOGLE_API_KEY")
```

---

## 🧩 How to Use

### 🔹 Run the Gemini Notebook

Open `gemini_text_image_video.ipynb` in **Jupyter** or **Google Colab**, and execute the cells to:

* Upload or link an image for OCR.
* Provide prompts for image/video generation.
* View and save generated outputs.

### 🔹 Run the Kokoro Notebook

Open `kokoro_audio_generation.ipynb`, and:

* Enter any text prompt.
* Generate natural speech in seconds.
* Play or download the audio directly in the notebook.

---

## 🧠 Example Use Cases

| Use Case                | Description                                                     |
| ----------------------- | --------------------------------------------------------------- |
| 📚 Educational Videos   | Convert written text into narrated video content.            |
| 🎙️ Podcast Automation  | Generate human-like voiceovers using Kokoro.                    |
| 🖼️ Visual Storytelling | Create dynamic visuals or concept art from text prompts.        |
| 🔍 Smart OCR            | Extract structured text with Gemini’s contextual understanding. |

---

## 📊 Tech Stack

* **Python 3.10+**
* **Jupyter Notebook / Google Colab**
* **Google Gemini (Generative AI)**
* **Kokoro AI**
* **Pillow** (image handling)

---

## ⚠️ Notes & Limitations

* Gemini’s video generation is **experimental** — expect variability in output.
* API usage may incur costs depending on quota and account plan.
* Always handle API keys securely and never push them publicly.

---

## 🧑‍💻 Author

**Hardik Jain**
📧 [[hardikjainharsora@gmail.com](mailto:hardikjainharsora@gmail.com)]

---

## ⭐ Acknowledgements

* [Google Generative AI (Gemini)](https://ai.google.dev/)
* [Kokoro Speech AI](https://kokoro.ai/)
* [Pillow](https://python-pillow.org/)

---
