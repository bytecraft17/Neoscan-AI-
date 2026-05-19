# NeoScan AI — Research & Development 🍼

**Core AI Engine for the NeoScan Neonatal Screening System.**

This repository contains the deep learning research, training notebooks, and architectural implementations for detecting 15+ neonatal conditions using computer vision.

---

## 🧩 AI Modules & Architectures

| Module | Diagnostic Focus | Architecture |
| :--- | :--- | :--- |
| **Module 1: Skin** | Jaundice, Cyanosis, Anemia | EfficientNetB3 |
| **Module 2: Skeletal Skin** | Bone Fracture Classification | ResNet50 |
| **Module 3: Eye** | ROP, Cataracts | InceptionV3 |
| **Module 4: Face** | Down Syndrome, Cleft Palate | VGG16 |

---

## 📊 Datasets

The project utilizes a comprehensive collection of neonatal datasets, organized by diagnostic module.

### 📁 Project Datasets (Google Drive)
These folders contain the processed images and data used for training and validation:
- **`Module1_Skin/`**: Jaundice, Cyanosis, and Anemia image data.
- **`Module2_Skeletal Skin/`**: Bone fracture binary classification data.
- **`Module3_Eye/`**: Retinal images for ROP and Cataract screening.
- **`Module4_Face/`**: Facial landmark and genetic condition data.

🔗 **Access Datasets:** [NeoScan_AI Main Drive Folder](https://drive.google.com/drive/folders/1n8JRm7RiyTkWSfMwqVijcHGlHMKJ89Bp)

---

### 🌐 External Research References
In addition to our private collection, the following public datasets were used as benchmarks:

| Module | Dataset Source | Download/Reference |
| :--- | :--- | :--- |
| **Skin** | DermaNet + CHOP Jaundice | [Kaggle Jaundice](https://www.kaggle.com/datasets/mubeenshakeel/jaundice-image-data) |
| **Eye** | ROP Retinal Dataset | [Kaggle ROP](https://www.kaggle.com/datasets/vladimirhula/retinal-image-dataset-of-infants-and-rop) |
| **Face** | VisAGe + DS Database | [HDA Face DB](https://www.h-da.de/en/research/research-groups/da-sec/biometric-systems/downloads/hda-down-syndrome-face-database/) |
| **Skeletal Skin** | Bone Fracture Dataset | [Kaggle](https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data) |

---

## 🛠️ Research Tech Stack

- **Machine Learning**: Scikit-Learn, XGBoost, LightGBM
- **Deep Learning**: PyTorch, TensorFlow / Keras
- **Computer Vision**: OpenCV, PIL
- **Deployment & Prototyping**: FastAPI, React
- **Analysis**: Jupyter Notebooks (.ipynb)

---

## 📂 Repository Contents

- `Module1_Skin_Analysis.ipynb`: Training pipeline for jaundice and skin tone analysis.
- `Module2_Skeletal Skin Analysis.ipynb`: Bone fracture binary classification.
- `Module3_Eye_Analysis.ipynb`: Retinal screening for ROP and pediatric cataracts.
- `Module4_Face_Analysis.ipynb`: Genetic condition detection via facial landmark analysis.

---
*Developed for the advancement of neonatal care and early diagnosis through AI.*
