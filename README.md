# Number-plate-detection
# 🚗 Automatic Number Plate License Detection

This Streamlit web application automatically detects and reads license plate numbers from uploaded vehicle images using OpenCV and EasyOCR.

---

### 📸 Project Features
Easy input support for images and videos

Accurate license plate detection using contour detection

Text recognition from license plates with EasyOCR

Real-time video processing optimized with frame skipping

Outputs a processed video with detected license numbers overlaid on the frames

### 🛠️ Tech Stack
Python 3.x

OpenCV

EasyOCR

NumPy

imutils

Google Colab (for cloud-based processing)

### 🧑‍💻 How to Run

Google Colab (Recommended)

Open the project in Google Colab.

Upload your image or video file when prompted.

The processed output will be displayed and saved automatically.

Local Setup:
Make sure Python 3.x is installed on your system.

Install the required dependencies:

```
pip install opencv-python easyocr imutils numpy
```
Run the main script:

```
python main.py
```

### 🧾 Requirements
Install necessary packages using pip:
```
pip install opencv-python easyocr imutils numpy
```
For GPU acceleration (optional but recommended for faster OCR):

```
pip install torch torchvision torchaudio
```

### 🖼️ Sample Output
The processed images and videos will show license plates with bounding boxes and the recognized text overlaid.

### 🎥 Video Output (Colab)
After uploading a video in Google Colab, you’ll be able to download the processed video with bounding boxes and recognized license plate numbers.

### ⚠️ Limitations
Only rectangular license plates are supported.

EasyOCR may struggle with very blurry or angled license plates.

Frame skipping is enabled by default (only processes every 5th frame) to optimize performance.

### License

This project is intended for educational use under the Naan Mudhalvan initiative and is not for commercial deployment.

