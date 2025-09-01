# Vehicle Number Plate Detection System  

This project detects vehicle license plates using a **Convolutional Neural Network (CNN)** and extracts alphanumeric text using **OCR (Tesseract)**. It is divided into two parts:  
1. **Training & Detection** → Detects the license plate region from input images.  
2. **OCR Processing** → Extracts the number from the detected license plate.  

---

## 🚀 Features  
- Detects number plate regions in vehicle images.  
- Uses CNN for detection and localization.  
- Applies **Tesseract OCR** to extract license plate text.  
- End-to-end workflow from training → detection → OCR.  

---

## 📂 Project Structure  

├── Training and Detection.ipynb  
# Train CNN model and detect number plate region

├── OCR based.ipynb              
# Apply OCR on detected plate to extract text

├── README.md                     
# Project documentation

yaml
Copy code

---

## ⚙️ Requirements  
Install dependencies before running:  

'''bash
pip install tensorflow keras opencv-python pytesseract matplotlib
Also, install Tesseract OCR on your system:

Windows: Download Tesseract

Linux/macOS:

bash
Copy code
sudo apt-get install tesseract-ocr

## 📖 Usage

# Step 1: Training and Detection
Run Training and Detection.ipynb:

Trains a CNN model.

Detects number plate regions in given vehicle images.

Outputs cropped number plate images.

# Step 2: OCR Processing
Run OCR based.ipynb:

Takes cropped number plate images as input.

Applies Tesseract OCR.

Extracts and prints the alphanumeric plate number.

## 📊 Results
Detection Accuracy: ~78% for plate localization.

OCR Performance: Extracted plate numbers successfully on clear images.

# Example:

yaml
Copy code
Detected Plate: MH12AB1234

## 🔮 Future Improvements
Improve CNN accuracy with a larger dataset.

Integrate YOLO or Faster R-CNN for real-time detection.

Enhance OCR preprocessing for noisy/blurry images.

## 🙌 Acknowledgements
OpenCV for image processing.

Tesseract OCR for text extraction.

TensorFlow/Keras for CNN model.

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve this project.

📜 License

This project is licensed under the GPL-3.0 License .

