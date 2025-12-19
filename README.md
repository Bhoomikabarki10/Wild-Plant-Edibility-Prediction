# Wild-Plant-Edibility-Prediction
This project is a Flask-based web application that uses deep learning models (CNN and ResNet) to classify  plant images and predict whether they help cure diabetes. Users can upload images, select a model, and  receive predictions with accuracy details. It also includes authentication and simple navigation pages. 
Plant-Leaf-Diabetes-Prediction-DeepLearning/


│


├── app.py                     # Flask application


├── requirements.txt           # Python dependencies


├── README.md                  # Project documentation


│


├── models/


│   ├── cnnmodel.h5             # CNN trained model


│   └── resnetplant.h5          # ResNet trained model


│
├── uploads/                    # Uploaded images


│
├── static/


│   ├── css/


│   │   └── style.css


│


├── templates/


│   ├── home.html


│   ├── index.html


│   ├── login.html


│   ├── about.html


│


├── dataset/


│   └── README.md               # Dataset description


│
├── screenshots/


│   ├── home_page.png


│   ├── upload_page.png


│   └── result_page.png


│


└── report/


    └── Project_Report.docx

    
🧾 README.md (Copy–Paste This)


markdown
Copy code
# 🌿 Plant Leaf Disease Cure Prediction Using Deep Learning

This project is a Deep Learning–based web application that predicts whether a plant leaf helps in curing diabetes. The system uses CNN and ResNet models for image classification and is deployed using the Flask web framework.

---

## 📌 Features
- Upload plant leaf image
- Choose between CNN and ResNet models
- Predict medicinal usefulness
- Display result with model accuracy
- Web-based user-friendly interface

---

## 🧠 Learning Technique
- **Supervised Learning**
- **Binary Image Classification**
- Models Used:
  - Convolutional Neural Network (CNN)
  - ResNet50 (Transfer Learning)

---

## 🛠️ Technologies Used
- Python 3.x
- TensorFlow & Keras
- Flask
- NumPy
- HTML / CSS

---

## 📂 Dataset
The dataset consists of labeled plant leaf images categorized into:
- Helps to cure diabetes
- Does not help to cure diabetes

Images were collected from public datasets and online sources and manually labeled.

---

## ⚙️ Installation & Execution

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Plant-Leaf-Diabetes-Prediction-DeepLearning.git
cd Plant-Leaf-Diabetes-Prediction-DeepLearning
2️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ Run the Application
bash
Copy code
python app.py
4️⃣ Open Browser
cpp
Copy code
http://127.0.0.1:5001
