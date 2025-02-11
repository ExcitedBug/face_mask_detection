🛡️ Face Mask Detector 

A deep learning-based project for real-time face mask detection using OpenCV, TensorFlow/Keras, and a Convolutional Neural Network (CNN). The model classifies whether a person is wearing a mask, not wearing a mask, or wearing it incorrectly.  


📌 Features  
✅ Real-time face mask detection using OpenCV  
✅ Trained on a dataset of masked and unmasked faces  
✅ CNN-based deep learning model for accurate classification  
✅ Works with webcam and pre-recorded video feeds  
✅ Deployment-ready with Flask (optional)  


🏗️ Tech Stack  
- Python 🐍  
- OpenCV 👁️  
- TensorFlow/Keras 🤖  
- NumPy, Pandas 📊  
- Matplotlib 📉  


📂 Project Structure  
```
Face-Mask-Detection/
│── dataset/               # Contains images of masked and unmasked faces  
│── models/                # Trained model files  
│── src/                   # Source code  
│   ├── face_mask_detector.py  # Model training & testing script  
│   ├── detect_mask_video.py   # Real-time detection using webcam  
│── app.py                 # Flask app for web deployment  
│── requirements.txt        # Dependencies  
│── README.md              # Project documentation  
```  

🚀 Installation  
1️⃣ Clone this repository  
```
git clone https://github.com/your-username/Face-Mask-Detection.git
cd Face-Mask-Detection
```

2️⃣ Install dependencies  
```
pip install -r requirements.txt
```

3️⃣ Run the real-time detection script  
```
python src/detect_mask_video.py
```

📊 Dataset  
The dataset consists of images of people with and without face masks. You can download and preprocess publicly available datasets such as:  
- [Kaggle Face Mask Dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset)  


🏋️ Model Training  
To train the model from scratch, run:  
```
python src/face_mask_detector.py
```


📜 License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  


🙌 Contributing  
Contributions are welcome! Please open an issue or submit a pull request.  


📩 Contact  
For any queries, reach out via:  
📧 Email: [sahilashat14@hotmail.com]  
📌 GitHub: [https://github.com/ExcitedBug] 

