# Vehicle Number Plate Detection System

##  Overview
A computer vision system that detects vehicle number plates in images using a combination of **CNN** and **OCR**.  
Developed in Python and executed within Jupyter notebooks for ease of experimentation.

---

##  Key Features
- **Image Preprocessing**: Uses OpenCV for cleaning, noise reduction, and region of interest extraction.  
- **CNN-based Detection**: Identifies potential number plate areas using Convolutional Neural Network techniques.  
- **Optical Character Recognition (OCR)**: Extracts the license plate text from detected regions.  
- **Interactive Notebooks**: Includes both training and detection workflows in Jupyter notebooks.

---

##  Tech Stack
- **Language & Development**: Python, Jupyter Notebook  
- **Libraries**: OpenCV, Keras/TensorFlow (for CNN), Tesseract (for OCR)  
- **Data Handling & Visualization**: NumPy, Matplotlib

---

##  Getting Started

### 1. Clone the repository
bash
git clone https://github.com/Yashwardhan-R/Vehicle-Number-Plate-detection-System.git
cd Vehicle-Number-Plate-detection-System

2. Install dependencies
bash
Copy code
pip install -r requirements.txt

3. Explore the notebooks
OCR based.ipynb: Quick OCR detection on sample images

Training and Detection.ipynb: End-to-end pipeline from training to extraction

4. Run the detection
Open the notebook in Jupyter and run the cells to preprocess images, detect plates, and extract text.

Example Usage
Functionality	Description
Plate detection	Input image → CNN detects plate region
OCR extraction	Crop region → Tesseract retrieves text
Visualization	Detected bounding box and extracted text displayed

Include your own test images (e.g., image1.jpg) to evaluate performance.

Results
Demonstrated detection and text extraction capability across sample images.

Provided visual confirmation through annotated image outputs.

Contributing
Feel free to submit issues or pull requests — improvements and optimizations are welcome!

License
This project is open-sourced under the MIT License.

Contact
Yashwardhan R
GitHub: Yashwardhan-R
