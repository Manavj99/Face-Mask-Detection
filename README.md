# Real-Time Face Mask Detection using Computer Vision

## 📖 Overview
This project implements a **real-time face mask detection system** using deep learning and computer vision.  
It was developed during the COVID-19 pandemic to monitor mask compliance in public and workplace environments.  
The system identifies whether a person is wearing a mask properly and triggers alerts for non-compliance.  

This work is also published in the **International Journal of Research and Analytical Reviews (IJRAR), June 2022, Vol. 9, Issue 2** (https://www.ijrar.org/papers/IJRAR22B3385.pdf) as:  

> **Automatic Face Mask Detection for Covid-19**  
> *Authors: Prof. Devika Rani Roy, Kanchan Yadav, Manav Jaiswal, Sameer Jadhav*

The proposed system achieves **95.77% training accuracy** and **94.58% testing accuracy** on benchmark datasets.  

---

## 🚀 Features
- Real-time detection using webcam or video input  
- Trained CNN model for mask / no-mask classification  
- Alerts via **buzzer sound** (`alarm.wav`) or **voice announcement** (`announce.mp3`)  
- Automatic **screenshot capture** of violations  
- GUI support with custom backgrounds and narration  
- Dataset augmentation for robust performance  

---

## 📂 Project Structure
```
face-mask-detection-using-computer-vision-main/
│── code.py                     # Main Python script for real-time detection
│── mask detection.ipynb        # Training notebook
│── mask detection final.ipynb  # Final optimized notebook
│── mask_detector.model         # Trained CNN model
│── dataset/                    # Dataset (with_mask / without_mask) 
│── GUI/                        # GUI assets (backgrounds, narration, icons, sounds)
│── flow chart.png              # Flow diagram of the system
│── Project flow chart.png      # Project workflow chart
│── requirements.txt            # Dependencies
│── README.md                   # Documentation
```

---

## ⚙️ Installation
1. Clone the repository:
```bash
git clone https://github.com/Manavj99/face-mask-detection.git
cd face-mask-detection
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run the Detection System
```bash
python code.py
```

### Train or Retrain the Model
```bash
jupyter notebook "mask detection final.ipynb"
```

---

## 📦 Requirements
- Python 3.7+
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Imutils  
- Matplotlib  
- Playsound  

(Complete list is provided in `requirements.txt`)

---

## 📊 Dataset
The dataset contains images of **people with and without masks**.  
Due to storage constraints, it is not included in this repository.  

You can download similar datasets here:  
- [Kaggle – Face Mask Detection Dataset](https://www.kaggle.com/andrewmvd/face-mask-detection)  
- [Prajnasb Observations GitHub](https://github.com/prajnasb/observations/tree/master/experiements/data)  

After downloading, place the dataset inside:
```
face-mask-detection-using-computer-vision-main/dataset/
```

---

## 📸 Screenshots

Example flow:  
1. ✅ Mask detected (green)
<img width="618" height="454" alt="image" src="https://github.com/user-attachments/assets/bf07fa6c-afb7-46af-9f44-fbf666b4a384" />
 
2. ❌ No mask detected (red alert + alarm + Screenshot)
<img width="564" height="408" alt="image" src="https://github.com/user-attachments/assets/9a22d716-507e-4dc2-b7e1-7bec6690736a" />
  
3. ⚠️ Improper mask detected (warning)  
<img width="566" height="418" alt="image" src="https://github.com/user-attachments/assets/ce080a78-cdf9-4932-94e0-8febeea0a16a" />

---

## 📄 Research Publication
This project is based on our published paper:  

**Automatic Face Mask Detection for Covid-19**  
*Prof. Devika Rani Roy, Kanchan Yadav, Manav Jaiswal, Sameer Jadhav*  
International Journal of Research and Analytical Reviews (IJRAR), Vol. 9, Issue 2, June 2022.  
[Read Paper on IJRAR](http://www.ijrar.org/)  

---

## 📝 License
This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.  

---

## 🤝 Contributing
Contributions are welcome!  
- Fork the repo  
- Create a feature branch  
- Commit changes  
- Submit a pull request  

---

## 🙌 Acknowledgments
- **TensorFlow** and **Keras** for deep learning  
- **OpenCV** for computer vision support  
- **Kaggle** and **Prajnasb Observations** for datasets  
- Published in **IJRAR Journal** (2022)  
