# 🚀 Space Station Object Detection using YOLOv8

A submission for CodeClash 2.0 – National Hackathon @ Google Office, Gurugram  
🏆 Sponsored Track: DualityAI – Synthetic Object Detection Challenge

---

## 🔍 Overview

This project develops an object detection system using YOLOv8, trained on Falcon’s synthetic dataset. The objective is to detect space station items such as:

- 🧯 Fire extinguishers  
- 🧰 Toolboxes  
- 🪫 Oxygen tanks  

The system is optimized for challenging conditions such as occlusion, varying lighting, and diverse camera angles.

---

## 🎯 Goals

- Train a YOLOv8 model on synthetic space station data
- Tune for performance using mAP@0.5 as a benchmark
- Build a simple interactive demo using Gradio or Streamlit
- Showcase real-time inference via a user-friendly interface

---

## 🛠️ Tech Stack

| Layer              | Tools & Frameworks                                 |
|--------------------|----------------------------------------------------|
| Model Training     | Python, Ultralytics YOLOv8                         |
| Data Handling      | OpenCV, Albumentations                             |
| Visualization      | Gradio / Streamlit                                 |
| Experimentation    | Jupyter Notebook, Google Colab                     |
| Deployment         | Hugging Face Spaces / Localhost Web App            |

---

## 🧪 Dataset

- Provided by DualityAI via the Falcon Simulation Platform
- Format: YOLOv8-compatible (images + labels)
- Objects to Detect: Fire Extinguisher, Toolbox, Oxygen Tank

---

## 🧠 Methodology

1. Data preprocessing & augmentation
2. YOLOv8 model configuration (data.yaml, custom anchors)
3. Training & evaluation (using val images)
4. Model testing with unseen test set
5. Web app integration (Gradio demo)

---

## 🚀 How to Run Locally

1. Clone this repo  
   git clone https://github.com/Harshith422/Duality-AI-Space-Station-Hackathon-.git  
   cd Duality-AI-Space-Station-Hackathon-

2. Install dependencies  
   pip install -r requirements.txt

3. Train the model  
   python train.py

4. Launch the demo app  
   python app.py  # Gradio/Streamlit based UI

---

## 📈 Evaluation Metrics

- mAP@0.5: Key metric for object detection accuracy
- Confusion Matrix: To visualize class-level performance
- Visual validation with bounding boxes

---

## 👨‍💻 Contributors

- Harshith P. 
- Manikanta E.

---

## 📝 License

MIT License. See LICENSE file for more details.

---

## 🌐 Links

- GitHub Repo: https://github.com/Harshith422/Duality-AI-Space-Station-Hackathon-
- Falcon Dataset Info: https://www.duality.ai/falcon  
- YOLOv8 Docs: https://docs.ultralytics.com

---

© 2025 | Built with ❤️ for CodeClash 2.0 Hackathon
