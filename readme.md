# 🚗 Automatic License Plate Detection and Recognition

This project detects and recognizes license plates from images and videos using **YOLO-based contour detection** and **EasyOCR** for Optical Character Recognition. It's designed for real-time or batch processing and runs seamlessly in environments like Google Colab.

---

## 📸 Project Features

* Easy image and video input support
* Accurate license plate localization using contour detection
* Text recognition from license plates using EasyOCR
* Real-time video processing with frame skipping optimization
* Outputs a processed video with detected license numbers overlaid

---

## 🛠️ Tech Stack

* Python 3.x
* OpenCV
* EasyOCR
* NumPy
* imutils
* Google Colab

---

## 🧑‍💻 How to Run

### Google Colab (Recommended)

1. Open the project in Google Colab.
2. Upload your image or video when prompted.
3. The processed output will be displayed and saved.

### Local Setup

Ensure you have Python 3.x installed and run the following:

```
pip install opencv-python easyocr imutils numpy
python main.py
```

---

## 🧾 Requirements

Install all required packages using pip:

```
pip install opencv-python easyocr imutils numpy
```

For GPU support (optional but faster OCR):

```
pip install torch torchvision torchaudio
```

---

## 🖼️ Sample Output

Processed images and videos will show license plates highlighted with recognized text overlaid.

---

## 🎥 Video Output (Colab)

After uploading a video in Colab, the processed video with bounding boxes and recognized plate numbers will be available for download.

---

## ⚠️ Limitations

* Only rectangular license plates are supported
* EasyOCR might misread very blurry or angled plates
* Frame skipping is enabled (processes every 5th frame) for performance

---

## 📜 License

This project is licensed under the MIT License.

---



