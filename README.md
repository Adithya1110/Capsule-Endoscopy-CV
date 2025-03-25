Computer Vision Framework for Capsule Endoscopy

🚀 Automated Disease Classification using Deep Learning

This project focuses on developing a Computer Vision framework for analyzing capsule endoscopy images and classifying diseases. Using deep learning models, we aim to assist medical professionals in detecting gastrointestinal disorders more efficiently.

📌 Project Overview

✅ Image Preprocessing – Noise reduction, contrast enhancement, resizing.

✅ Deep Learning Model – CNN-based architecture for disease classification.

✅ Dataset Handling – Efficient storage and preprocessing pipeline.

✅ Evaluation & Metrics – Accuracy, precision, recall, and F1-score.

✅ User Interface – Web-based interface (optional).

📁 Project Structure

bash

Copy

Edit

capsule-endoscopy-CV/

│── data/                 # Dataset (stored externally, use download script)

│── models/               # Trained models

│── notebooks/            # Jupyter notebooks for EDA & model training

│── src/                  # Source code for image classification

│   ├── main.py           # StreamLit Script

│   ├── Model_Train.py    # Model training script

│   ├── Class_indices.json  #Involves classes of diseases

│── requirements.txt      # Dependencies

│── README.md             # Project overview

│── LICENSE               # License information

🛠️ Installation & Setup

1️⃣ Clone the Repository

bash

Copy

Edit

git clone https://github.com/your-username/capsule-endoscopy-CV.git

cd capsule-endoscopy-CV

2️⃣ Install Dependencies

bash

Copy

Edit

pip install -r requirements.txt

3️⃣ Download Dataset
Since the dataset is too large for GitHub, download it using the script:

bash

Copy

Edit

python download_data.py

4️⃣ Train the Model

bash

Copy

Edit

python src/train.py

5️⃣ Run StreamLit Script

bash

Copy

Edit

streamlit run .\main.py

📊 Model Performance

Metric	Score

Accuracy	92.5%

Precision	89.8%

Recall	91.2%

F1-Score	90.5%

🤝 Contributors

Sai Sathwik Kosuru

Adithya Om Sangani

Srinivas Pullaboina

Sandhya Baindla

📝 License
This project is licensed under the MIT License – see the LICENSE file for details.
