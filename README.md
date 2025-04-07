# smart-pcb-component--detection-and--text-detection--using-GEN-AI
Smart PCB defect detection and component recognition using YOLOv8 and Generative AI-based OCR for text extraction — built to automate inspection in electronics manufacturing.
# Smart PCB Component Detection & Text Recognition

This project uses **YOLOv8** for real-time detection of PCB components and defects, along with **Generative AI (OCR)** for reading printed labels/text on the board. Developed as a smart inspection tool for electronics quality control.

## 🔧 Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- EasyOCR / Tesseract (or custom OCR)
- NumPy, Pandas

## 📂 Project Structure

- `smart_pcb_inspection.py` → Main script with all logic, model inference, and annotations
- Images & trained model weights are not included here due to size constraints

## 🚀 Features
- Detects multiple PCB components using YOLOv8
- Recognizes text labels (like IC part numbers, pin labels)
- Annotates bounding boxes with both object class and text
- Can be extended to classify defects like missing, rotated, or incorrect parts

## 🧠 Model Training
- YOLOv8 trained on custom PCB dataset (annotated via Roboflow)
- OCR model fine-tuned using real PCB print samples

## ❗Note
Due to file size, images and model weights are not uploaded to this repository.  
Please contact me if you'd like a sample set or to test the model.


