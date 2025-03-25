# 🏥 Computer Vision Framework for Capsule Endoscopy  
**Automated Disease Classification using Deep Learning**  

![Healthcare AI](https://img.shields.io/badge/Field-Medical%20AI-blue) ![Python](https://img.shields.io/badge/Python-3.8%2B-green) ![License](https://img.shields.io/badge/License-MIT-orange) ![Classes](https://img.shields.io/badge/Classes-10%20Conditions-purple)

## 📌 Project Overview  
This project develops a **Computer Vision framework** to analyze capsule endoscopy images and classify gastrointestinal diseases using deep learning. The system assists medical professionals in faster and more accurate diagnosis of conditions like:
### 🔍 Target Conditions
| Category | Conditions |
|----------|------------|
| **Vascular** | Angioectasia, Bleeding |
| **Inflammatory** | Erosion, Erythema, Ulcer |
| **Structural** | Polyp, Lymphangiectasia, Foreign Body |
| **Infectious** | Worms |
| **Normal** | Healthy mucosa |
### Key Features  
✅ **Image Preprocessing** – Noise reduction, contrast enhancement, resizing  
✅ **CNN Architecture** – Custom deep learning model for disease classification  
✅ **Efficient Data Pipeline** – Optimized dataset handling and augmentation  
✅ **Comprehensive Metrics** – Accuracy, precision, recall, and F1-score tracking  
✅ **Web Interface** (Optional) – StreamLit-based UI for clinical use  

## 📂 Project Structure  
```bash
capsule-endoscopy-CV/
├── Data/                  # Dataset (external storage)
├── Models/                # Saved model weights (.h5/.pth)
├── Notebooks/             # Jupyter notebooks for EDA & prototyping
│   ├── Custom_CNN.ipynb   # Custom CNN Model Training
|   ├── Resnet.ipynb       # Resnet Model Training
│   └── VGG16.ipynb        # VGG Model Training 
├── src/                   # Production code  
│   ├── main.py            # StreamLit application  
│   ├── Model_Train.ipynb  # Training Model  
│   └── class_indices.json # Classes  
├── requirements.txt       # Python dependencies  
├── LICENSE                # MIT License  
└── README.md              # This document

```

🛠️ Installation & Setup

1️⃣ Clone the Repository
```bash
git clone https://github.com/Adithya1110/Capsule-Endoscopy-CV.git

cd capsule-endoscopy-CV
```

2️⃣ Install Dependencies
```bash

pip install -r requirements.txt
```

3️⃣ Download Dataset
```bash
Use the script in data/ directory:

python data/Data.py

Or Use it directly from GitHub:

Folder -> Data
```

4️⃣ Train the Model
```bash

After downloading the dataset, train the model using the provided Jupyter notebook:

Open notebooks/Model_Train.ipynb

Change the dataset and model path as needed

Train the model
```

5️⃣ Run Streamlit Application

Once the model is trained, deploy it using Streamlit:

Modify the paths in src/main.py to point to the trained model and class indices.

Run the application:
```bash

streamlit run src/main.py
```

## 📊 Model Performance

### Classification Metrics (Weighted Average)

| Metric     | Score  | Description |
|------------|--------|-------------|
| **Accuracy** | 92.5% | Overall correct predictions |
| **Precision** | 89.8% | True positives / (True positives + False positives) |
| **Recall** | 91.2% | True positives / (True positives + False negatives) |
| **F1-Score** | 90.5% | Harmonic mean of precision and recall |

## 🤝 Contributors

### Core Development Team
- **Sai Sathwik Kosuru**  :microscope::wrench:  

- **Adithya Om Sangani** :robot::computer: 

- **Srinivas Pullaboina** :book::bar_chart:  

- **Sandhya Baindla** :art::test_tube:  

📝 License

This project is licensed under the MIT License – see the LICENSE file for details.
