# ASL Visualizer – Real-Time Sign Recognition

A real-time American Sign Language (ASL) visualizer that detects hand gestures using a webcam and predicts the corresponding ASL sign using computer vision and machine learning .

---

## Features

- Real-time hand detection via webcam
- Automatic hand cropping using bounding boxes
- Custom dataset collection for ASL signs
- Machine learning based gesture recognition
- Live prediction overlay on video feed

---

## Dataset & Model

- The `Data/` directory is used to store training images for each ASL sign.
- Due to the large number of images, the dataset is **not included** in this repository.
- An example pre-trained model file `asl_knn_model.pkl` is included and used by `recognize_gesture.py` for quick testing.

### Data Folder Structure

```text
Data/
├── A/
│   ├── img_1.jpg
│   ├── img_2.jpg
│   └── ...
├── B/
└── ...
```

You can generate your own dataset using `train.py`.

---

## Dependencies

### Python Dependencies

- opencv-python
- cvzone
- numpy
- scikit-learn
- joblib

Install all dependencies using:

```bash
pip install opencv-python cvzone numpy scikit-learn joblib
```
Contributed by Ansh Dixit.