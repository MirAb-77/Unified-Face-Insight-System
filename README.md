# Unified Face Insight System

## 📌 Project Overview
The **Unified Face Insight System** is an **AI-powered solution** designed to address critical public health challenges through advanced **facial recognition, mask compliance monitoring**, and **demographic analysis**. This project integrates **deep learning techniques** to detect mask usage, classify mask types, estimate age, and predict gender — even with occluded facial features.

With real-time capabilities and robust accuracy, this system aims to support **public health monitoring, surveillance systems, and demographic data collection** in environments like hospitals, educational institutions, and public spaces.

---

## 🔑 Key Features
| Feature               | Description                                              | Model Used        | Performance      |
|-----------------------|---------------------------------------------------------|------------------|----------------|
| Mask Detection       | Detects whether a person is wearing a mask or not        | Custom CNN       | 97% Accuracy   |
| Mask Type Classification | Classifies mask type (Cloth, Surgical, N95)           | ResNet-50 v2     | 91.5% Accuracy |
| Gender Prediction    | Classifies gender from masked or unmasked faces         | PyTorch Custom CNN | 92% Accuracy   |
| Age Estimation       | Predicts age category even with partial facial occlusion | DenseNet-121     | 95.7% F1-Score |
| Real-Time Monitoring | Provides real-time alerts and insights                  | OpenCV + TensorFlow | ✅ Supported    |

---

## 🎯 Project Objectives
- Provide **real-time mask compliance monitoring** with demographic insights.
- Create a **single unified system** to handle multiple tasks from facial images.
- Improve model performance in **dynamic environments** like public spaces.
- Offer **easy-to-use API endpoints** for developers and researchers.
- Make the system **scalable, inclusive, and robust** for global applications.

---

## 🔑 Why This System?
| Feature                    | Benefit                         |
|-----------------------------|---------------------------------|
| Multi-Task Integration     | Detects mask, mask type, age, and gender in one system |
| Non-Binary Gender Inclusion | Supports inclusive gender detection (Future Scope) |
| Real-World Robustness      | High accuracy in **low-light** and **crowded** environments |
| API Support               | Easy integration into **external applications** |
| Scalability               | Adaptable to **new datasets** and **applications** |

---

## ⚙️ How to Use the Repository
### 1. Clone the Repository
```bash
git clone https://github.com/MirAb-77/Unified-Face-Insight-System.git
cd Unified-Face-Insight-System
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Dataset Download
Download the required datasets from the following links:
- [Masked Face Dataset](https://www.kaggle.com/datasets/banilkumar20phd7071/masked-face-age-and-gender-identify-artificial-masking)
- [Face Mask Types Dataset](https://www.kaggle.com/datasets/bahadoreizadkhah/face-mask-types-dataset)
- [Gender Detection Dataset](https://www.kaggle.com/datasets/trainingdatapro/gender-detection-and-classification-image-dataset)
- [Masked Age Dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset)

### 4. Model Training
To train the models, run the following command:
```bash
python train.py --task mask_detection --epochs 50
```

### 5. Inference and Testing
Use the pre-trained models for inference:
```bash
python predict.py --image_path sample_image.jpg
```

### 6. API Usage
The system provides **API endpoints** for easy integration:
```bash
POST /detect_face
POST /classify_mask
POST /predict_age_gender
```
Example Request:
```json
{
  "image": "base64_encoded_image"
}
```

---

## 🔥 Performance Results
| Task                  | Accuracy | Precision | Recall | F1-Score |
|-----------------------|----------|-----------|-------|----------|
| Mask Detection       | 97%     | 96%      | 98%   | 97%     |
| Mask Type Classification | 91.5%   | 90%      | 92%   | 90.6%   |
| Gender Classification | 92%     | 88% (Male) | 100% (Male) | 93%     |
| Age Estimation       | 94%     | 77%      | -     | 95.7%   |

---

## 🔍 Evaluation Metrics
- **Accuracy**
- **Precision & Recall**
- **F1-Score**
- **Confusion Matrix Visualizations**
- **Area Under Curve (AUC)**

---

## 📌 Pre-Trained Models
| Task       | Model Name       | Download Link             |
|------------|----------------|--------------------------|
| Mask Detection | CNN Model    | [Download](https://github.com/MirAb-77/Unified-Face-Insight-System/releases) |
| Mask Type Classification | ResNet-50v2 | [Download](https://github.com/MirAb-77/Unified-Face-Insight-System/releases) |
| Gender Detection | PyTorch Model | [Download](https://github.com/MirAb-77/Unified-Face-Insight-System/releases) |
| Age Detection | DenseNet-121 | [Download](https://github.com/MirAb-77/Unified-Face-Insight-System/releases) |

---

## 📊 Visualizations
- Accuracy & Loss Plots
- Confusion Matrix
- Heatmaps
- Prediction vs Ground Truth Comparison

---

## 🔗 API Documentation
Visit the **API Documentation** for more information:
[API Documentation](https://github.com/MirAb-77/Unified-Face-Insight-System/wiki)

---

## Future Roadmap
- ✅ Real-Time Mask Detection
- ✅ Mask Type Classification
- ✅ Gender Classification
- ✅ Age Estimation
- 🔄 Non-Binary Gender Classification
- 🔄 Cloud-Based API Hosting
- 🔄 Mobile Application Integration
- 🔄 Ensemble Learning Models

---

## 🌐 Real-World Applications
- Public Health Monitoring
- Surveillance Systems
- Workplace Safety
- Retail Stores
- Educational Institutions
- Airports and Transportation Hubs

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, raise issues, or submit PRs.

### Contribution Guidelines
- Fork the repo
- Create a new branch
- Raise a PR with proper description

---

## 📌 Author
**Abdullah Imran**  
BS-Data Science Department  
University of Management and Technology  

---

## 🔗 Contact
- [GitHub Repository](https://github.com/MirAb-77/Unified-Face-Insight-System)
- LinkedIn: [Abdullah Imran](https://www.linkedin.com/in/abdullah-mir-211658230/)

---

## 🎓 Acknowledgments
Special thanks to **Miss Shaista Habib**, Professor of Deep Learning and Neural Networks, for her mentorship and support.

---

## 📜 License
This project is licensed under the **MIT License**.

