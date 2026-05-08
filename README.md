# Face Mask Detection

Real-time Face Mask Detection system using Python, TensorFlow, OpenCV, and MobileNetV2 for detecting masked and unmasked faces through webcam/video input.

---

## Features

- Real-time face mask detection
- Webcam/video stream support
- Deep learning-based classification
- MobileNetV2 transfer learning model
- Detects masked and unmasked faces
- Training visualization graphs
- Lightweight and fast detection

---

## Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Structure

```text
Face_Mask_Detection/
│
├── dataset/
│   ├── with_mask/
│   └── without_mask/
│
├── detect_mask_video.py
├── train_mask_detector.py
├── requirements.txt
├── README.md
├── .gitignore
├── face_detector/
└── screenshots/

```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Shivank2005/Face_Mask_Detection.git
cd Face_Mask_Detection
```

### 2. Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the virtual environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Dataset Structure

Placed the dataset inside the `dataset` folder:

```text
dataset/
├── with_mask/
└── without_mask/
```

Each folder should contain images of faces with and without masks.

---

## Train the Model

Run the following command to train the model:

```bash
python train_mask_detector.py
```

This will:
- Load and preprocess the dataset
- Train the MobileNetV2 model
- Save the trained model
- Generate training graphs

Generated files:

```text
mask_detector.keras
plot_training.png
```

---

## Run Real-Time Detection

```bash
python detect_mask_video.py
```

The webcam will open and start detecting faces with or without masks in real time.

---

## Results

The model can detect masked and unmasked faces in real time using transfer learning and computer vision techniques.

---
---

## Screenshots

Add screenshots or demo GIFs here.

Example:

```text
screenshots/demo.png
```

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

**Shivank**

GitHub: https://github.com/Shivank2005
