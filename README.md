# Number-plate-detection
# 🚗 Automatic Number Plate License Detection

This Streamlit web application automatically detects and reads license plate numbers from uploaded vehicle images using OpenCV and EasyOCR.

---

## 🛠️ Features

- Upload vehicle images in JPG, PNG, BMP, or WEBP formats
- Detect license plate region using image processing
- Extract and display license plate text using OCR (EasyOCR)
- Visualize results with bounding boxes and annotations

---

---

## 🔧 Technologies Used

- **Python**
- **Streamlit** – For creating the interactive web interface
- **OpenCV** – Image processing and contour detection
- **EasyOCR** – Optical character recognition (OCR)
- **Pillow** – Image file handling
- **NumPy** – Numerical operations

---

## 🎯 Features

- Upload a vehicle image containing a number plate.
- Automatically detects the number plate using contour approximation.
- Extracts and reads text from the plate using EasyOCR.
- Displays the image with bounding box and detected text.

---

## 🚀 How to Run Locally

### 1. Clone the Repository

git clone https://github.com/Srinivasan3009/Number-plate-detection.git

cd number_plate_detection


## 📦 Dependencies

Make sure you have Python 3.7+ installed. Then install the required Python libraries:

```bash
pip install streamlit pillow opencv-python imutils easyocr numpy

```
### Run the Streamlit App

streamlit run app.py

Then open your browser and navigate to http://localhost:8501

###  Future Enhancements
Support for live webcam or video input

Integration with vehicle databases

Handle multiple license plates in one image

Improve plate localization accuracy with deep learning (YOLO, SSD, etc.)

### License

This project is licensed under the MIT License.

