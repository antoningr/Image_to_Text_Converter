# 🖼️ Image to Text Converter (OCR) with EasyOCR

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![EasyOCR](https://img.shields.io/badge/Model-EasyOCR-blue?logo=ai&logoColor=white)](https://github.com/JaidedAI/EasyOCR)
[![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-ff4b4b?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)


A complete project that demonstrates **optical character recognition (OCR)** using [EasyOCR](https://github.com/JaidedAI/EasyOCR).  

Includes:
- 📱 **Streamlit Web App** for easy image upload and text extraction
- 📓 **Step-by-Step Jupyter Notebook** for experimentation
- 📂 **Sample Image Dataset** for quick testing


## 📌 Project Overview

**OCR (Optical Character Recognition)** is the task of **extracting machine-readable text from images**.  
This project uses **EasyOCR**, a lightweight yet powerful OCR library supporting 80+ languages.

We provide:
- A **Streamlit app** for interactive OCR extraction
- A **Jupyter Notebook** for step-by-step exploration
- A **sample dataset** with images for quick tests


## 🚀 Features

✅ Upload one or multiple images and extract text instantly  
✅ Support for multiple languages (English, French, German, Spanish, Italian, etc.)  
✅ Configurable OCR parameters (contrast adjustment, paragraph grouping, threshold tuning)  
✅ Copy-to-clipboard button for extracted text  
✅ History of all extractions within the session  
✅ Clean and user-friendly UI with helpful tooltips  
✅ GPU acceleration when available  


## 📸 Screenshots

### Streamlit Web App

![Streamlit App Screenshot](image/image_captioning_app_1.jpg)
![Streamlit App Screenshot](image/image_captioning_app_2.jpg)


![Streamlit App Screenshot](image/image_captioning_app_3.jpg)


## 🛠 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/antoningr/Image_to_Text_Converter
cd Image_to_Text_Converter
```

### 2️⃣ Create a Virtual Environment (optional)

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```


## ▶️ Usage

### Run the Streamlit App

```bash
streamlit run app.py
```

Then open your browser at: http://localhost:8501


### Run the Jupyter Notebook

```bash
jupyter notebook notebook/image_to_text_easyocr.ipynb
```


## 🧠 How It Works

1. OCR Reader: EasyOCR loads the language-specific model.
2. Preprocessing: Image is prepared with optional contrast adjustment.
3. Text Extraction: EasyOCR detects bounding boxes and extracts text.
4. Output: Text is displayed and can be copied or saved in the history.


Pipeline:

```bash
Image → EasyOCR Reader → Text Detection → Extracted Text
```


## 📜 License
This project is licensed under the **MIT License**.