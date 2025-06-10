🧠 Emotion Detection from Facial Expressions

📌 Overview

Feature               | Description
--                    | --
🎯 Model             | CNN-based Emotion Classifier
🧾 Dataset           | FER-2013 dataset from Kaggle (35,000+ labeled face images)
📱 Deployment        | Web App using Streamlit
🖥️ Display Output    | Real-time webcam prediction using OpenCV
📲 Mobile Interface  | (Optional) PWA mode from Streamlit
🧠 Emotions Detected | Happy, Sad, Angry, Surprise, Fear, Neutral

🛠 Tech Stack

Component        | Tools / Frameworks
--               | --
Model            | TensorFlow, Keras (CNN Architecture)
Optimization     | EarlyStopping, Dropout Layers
Hardware         | Webcam / Pi Camera (optional)
Image Processing | OpenCV, NumPy
Web App          | Streamlit
Dataset Tool     | Kaggle, CSV Parsing

 🚀 How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
