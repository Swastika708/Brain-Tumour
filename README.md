# 🧠 Brain Tumor Detection using Deep Learning
This project is a **Deep Learning-based web application** that detects brain tumors from MRI scans using a trained **Convolutional Neural Network (CNN)**. It is designed to provide real-time tumor classification and assist in medical diagnostics.

---

## 🛠 Technologies Used
- **Programming Language**: Python
- **Framework**: Flask
- **Deep Learning**: TensorFlow, Keras (CNN architecture)
- **Data Processing**: NumPy, Pandas
- **Visualization**: Matplotlib
- **Web Development**: HTML, CSS (for UI)
- **Deployment**: Flask web server

---

## 📊 Dataset Used
- **Source**: Public dataset from [Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- **Size**: 3,058 MRI images  
  - 2,998 for training  
  - 60 for testing  
- **Classes**: Tumor, No Tumor

---

## ⚙️ Project Workflow
1. **Image Preprocessing**
   - Images resized to **64x64 pixels**
   - Grayscale conversion
   - Pixel normalization

2. **Model Building**
   - Built with **Convolutional Neural Network (CNN)**
   - Trained with **Keras** + **TensorFlow**
   - Achieved **85% accuracy** on test data

3. **Web App Integration**
   - Developed a Flask-based UI
   - Allows users to upload MRI images for real-time classification
   - Displays prediction result (Tumor / No Tumor)

---

## 🖥️ How to Run Locally
### 1. Clone the repository
```bash
git clone https://github.com/Swastika708/Brain-Tumour.git
cd Brain-Tumour/BTDfinal
pip install -r requirements.txt #Install dependencies
pip install flask tensorflow keras numpy pandas matplotlib #If requirements.txt is not available, install manually:
python app.py #run the app

---

## 📁 Project Structure
BTDfinal/
├── templates/ # HTML files for Flask
│ └── index.html
├── static/ # CSS or static assets
├── app.py # Flask app (main entry point)
├── model.h5 # Trained CNN model
├── predict.py # Tumor prediction logic
├── sample_mri_scan.png # Sample MRI image (optional)
└── README.md # Project documentation

---

## 📌 Features
- 🧠 Real-time tumor detection from MRI scans
- ⚡ Lightweight and fast Flask server
- 🎯 Clean, minimal UI
- 🧬 Trained on real-world medical data
- ✅ Achieves ~85% accuracy on test data

---

## 🧠 Author
**Swastika Kumari**  
📧 [swastikathakur2345@gmail.com](mailto:swastikathakur2345@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/swastika-kumari-a7bb61228/)  
💻 [GitHub](https://github.com/Swastika708)

---

## 📄 License
This project is open source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

