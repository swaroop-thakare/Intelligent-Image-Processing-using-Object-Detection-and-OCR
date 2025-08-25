# 🖼️ Intelligent Image Processing using Object Detection and OCR

A robust Computer Vision project integrating **YOLOv5** for real-time object detection and **Tesseract OCR** for multilingual text extraction, delivered through a lightweight **HTML + Python backend** interface.

This system enables automated image processing, object detection, and text extraction, with practical applications such as **business card scanning and auto-saving extracted details to Google Sheets for automated form filling**.

---

## 🚀 Features

- 🔍 **Object Detection:** Real-time, accurate object detection powered by YOLOv5 (PyTorch).
- 📝 **Optical Character Recognition (OCR):** Extracts multilingual text using Tesseract OCR.
- 📇 **Business Card Automation:** Seamlessly captures business card details, auto-saves to Google Sheets, and supports automated form-filling.
- 🌐 **Web Interface:** Intuitive HTML/CSS frontend with a Python (Flask/FastAPI) backend.
- 💾 **Downloadable Results:** Save and download processed images with bounding boxes and OCR outputs.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS
- **Backend:** Python (Flask / FastAPI)
- **Core Libraries & Tools:**
  - **OpenCV:** Image preprocessing & visualization
  - **YOLOv5:** Object detection (PyTorch)
  - **Tesseract OCR:** Text recognition via `pytesseract`
  - **NumPy, Matplotlib:** Data handling & visualization
  - **Google Sheets API:** Automation & data persistence

---

## 📂 Project Structure

```bash
📦 Intelligent-Image-Processing-using-Object-Detection-and-OCR
┣ 📂 static            # CSS/JS files
┣ 📂 templates         # HTML frontend pages
┣ 📂 models            # YOLOv5 model weights
┣ 📂 uploads           # Uploaded images
┣ 📂 outputs           # Processed images & OCR results
┣ 📜 app.py            # Main backend (Flask/FastAPI)
┣ 📜 requirements.txt  # Python dependencies
┗ 📜 README.md         # Project documentation
