# plant-disease-prediction-cnn-computer-vision-project
This repository is about building an Image classifier CNN with Python on Plant Disease Prediction.

Kaggle Dataset Link: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

# 🌿 Plant Disease Prediction using CNN
This project is a **Deep Learning-based Image Classification system** that predicts plant diseases from leaf images using a **Convolutional Neural Network (CNN)**.
It helps in early detection of plant diseases, which can improve crop health and reduce losses.

---

## 📌 Project Overview
- 🔬 Model: Convolutional Neural Network (CNN)
- 🖼️ Input: Leaf Images (JPG/PNG)
- 🎯 Output: Predicted Plant Disease
- 📊 Dataset: PlantVillage Dataset (Kaggle)

The model learns patterns from plant leaf images and classifies them into healthy or diseased categories.

---

## 🧠 Workflow (Step-by-Step)

This is the complete workflow of the project:

### 1️⃣ Data Collection
- Dataset is taken from Kaggle (PlantVillage Dataset)
- Contains thousands of images of plant leaves  
- Includes both **healthy and diseased classes**

👉 Data collection is the first and most important step in CNN projects :contentReference[oaicite:0]{index=0}
---

### 2️⃣ Data Preprocessing
- Resize images (e.g., 224x224)
- Normalize pixel values
- Split dataset into:
  - Training set
  - Validation set
  - Testing set
---

### 3️⃣ Model Building (CNN)
- Use CNN layers:
  - Conv2D
  - MaxPooling
  - Dropout
  - Dense layers
- Activation functions: ReLU, Softmax
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
---

### 4️⃣ Model Training
- Train model on training dataset
- Validate performance using validation set
- Tune hyperparameters (epochs, batch size)
---

### 5️⃣ Model Evaluation
- Evaluate accuracy on test dataset
- Check metrics:
  - Accuracy
  - Loss
  - Confusion Matrix
---

### 6️⃣ Prediction
- Input: New leaf image
- Output: Predicted disease class
---

### 7️⃣ Deployment (Optional)
- Can be deployed using:
  - Streamlit
  - Flask
---

## 📂 Project Structure
plant-disease-prediction/

├── app/ # Web app (if using Streamlit/Flask)

├── model_training_notebook/ # Jupyter notebooks for training

├── test_images/ # Folder for testing images

├── model/ # Saved trained model

├── requirements.txt # Dependencies

└── README.md

## 🚀 How to Run the Project

#1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Model / App
python app.py

OR (if using Streamlit)
streamlit run app.py

##### How to Test Your Model
Go to test_images/ folder
Add your leaf images
Run the model
Get prediction output

📊 Dataset
Source: Kaggle - PlantVillage Dataset
Contains:
50,000+ images
Multiple plant disease classes

✨ Features
Predict plant diseases from images
Easy-to-use structure
Can be extended to real-time prediction
Works with custom datasets

⚠️ Limitations
Accuracy depends on dataset quality
May not perform well on unseen plant types
Requires good preprocessing
🔮 Future Improvements
Add real-time camera detection
Improve accuracy with advanced models (ResNet, EfficientNet)
Deploy on mobile/web apps
