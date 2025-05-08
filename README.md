License Plate Detection and Recognition using YOLOv8 and Transformers:

This project detects and recognizes vehicle license plates using YOLOv8 for object detection and compares EasyOCR with a transformer-based model (TrOCR) for text recognition.

---

Objective:

- Detect license plates from vehicle images using a YOLOv8 model.
- Extract license plate numbers using:
  - EasyOCR (CNN-based)
  - TrOCR (Transformer-based OCR)
- Compare the recognition performance of both OCR techniques using standard metrics.

---

Models Used

| Component              | Model/Library       |
|------------------------|---------------------|
| License Plate Detection| YOLOv8 (Ultralytics)|
| OCR Model 1            | EasyOCR             |
| OCR Model 2            | TrOCR (Hugging Face Transformers)|

---

 Dataset

- Source: Roboflow Universe  
- Project: `license Plate Detection`   
- Train/Valid Split: Reduced to 400 train / 100 valid samples for faster processing.

---

 Installation
 
pip install ultralytics easyocr opencv-python-headless transformers roboflow
