
# 🛡️ Terrorist Detection using YOLOv8 and DeepSORT

This project leverages the power of **YOLOv8** for object detection and **DeepSORT** for real-time multi-object tracking to identify and track terrorists on a ground-level surveillance feed. The system can detect, track, and assign **unique IDs** to each individual present, providing a real-time count and movement pattern which can be crucial for **military intelligence and armed forces operations**.

---

## 🔍 Overview

- **YOLOv8**: Utilized as the object detection model, pretrained and fine-tuned to identify terrorist entities within video frames.
- **DeepSORT**: Integrated for associating detections across frames and assigning unique track IDs to each individual.
- **Use Case**: Real-time surveillance system to support **military response**, **border security**, and **threat monitoring**.

---

## 🎯 Features

- Real-time object detection and tracking
- Each terrorist is assigned a **unique Track ID**
- Displays **total count of individuals** present on the ground
- Can be adapted to different environments and datasets

---

## 🧠 Model Training

The detection model is built upon the **YOLOv8 architecture** and fine-tuned on a custom dataset related to terrorist identification. The combination with DeepSORT ensures persistent tracking across frames.

---

## 🛠️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/Harshkumar0403/terrorist_detection_yolo.git
   cd terrorist_detection_yolo
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up DeepSORT**

   Follow the setup in the [`deep_sort/`](./deep_sort/) folder for additional dependencies and configurations.

---

## 📂 Project Structure

```
├── deep_sort/               # DeepSORT module
├── requirements.txt         # Python dependencies
├── data/                    # mask and input videos
├── main.py                  # main file
├── trackers.py              # Helper function
└── README.md                # Project documentation
```

---

## 📽️ Demo

> https://drive.google.com/file/d/1wM19oTkVta3nQfTrcVEyI0nY199PepuE/view?usp=drive_link

---

## 🔐 Applications

- Real-time battlefield surveillance
- Threat detection for high-security zones
- Border patrol and anti-infiltration monitoring
- Intelligence support for defense operations

---

## 📌 Requirements

- Python ≥ 3.8  
- Ultralytics YOLOv8  
- OpenCV  
- NumPy  
- DeepSORT dependencies (in `deep_sort/`)  
- Other libraries listed in `requirements.txt`

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---
