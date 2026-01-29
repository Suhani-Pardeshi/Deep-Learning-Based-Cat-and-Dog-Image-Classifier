# Deep-Learning-Based-Cat-and-Dog-Image-Classifier

# 📌 Project Overview

* This project is a Deep Learning–based Cat and Dog Image Classification System built using a pretrained MobileNetV2 model and deployed with a Gradio web interface.

* The application allows users to upload an image and accurately predicts whether the image contains a cat or a dog, along with a confidence score.

* The model uses transfer learning on the ImageNet dataset to achieve fast and accurate predictions.

# 🎯 Key Features

* 🧠 Pretrained MobileNetV2 CNN model

* 📸 Upload image directly via browser

* 🐱 Cat detection with confidence score

* 🐶 Dog detection with confidence score

* ❌ Handles uncertain predictions gracefully

* 🌐 Interactive UI using Gradio

* ⚡ Fast and lightweight inference

# 🛠️ Technologies Used

* Python

* TensorFlow / Keras

* MobileNetV2 (Transfer Learning)

* NumPy

* Pillow (PIL)

* Gradio

* Deep Learning & Computer Vision

# 🧠 How the System Works

* User uploads an image through the Gradio interface

* Image is resized to 224 × 224

* Image is preprocessed using preprocess_input

* MobileNetV2 predicts ImageNet classes

* Predictions are analyzed using keyword matching

* Confidence scores are calculated

* Final classification is displayed (Cat 🐱 / Dog 🐶)

# 📂 Project Structure
📁 Cat-Dog-Classifier
│── app.py                # Main application file
│── README.md             # Project documentation
│── requirements.txt      # Dependencies

# ▶️ How to Run the Project
* 1️⃣ Clone the Repository
git clone https://github.com/your-username/cat-dog-classifier.git
cd cat-dog-classifier

* 2️⃣ Install Required Libraries
pip install tensorflow numpy pillow gradio

* 3️⃣ Run the Application
python app.py

* 4️⃣ Upload an Image (Important ✅)

Open the local Gradio URL shown in the terminal
(usually http://127.0.0.1:7860)

Click Upload Image

Select a clear image of a cat or dog

View the prediction and confidence score instantly

# 🖼️ Sample Output

* 🐱 It's a Cat (confidence: 0.78)

* 🐶 It's a Dog (confidence: 0.85)

* ❌ Unable to confidently classify as Cat or Dog

* Output like :
<img width="1751" height="824" alt="● Traffic-Sign-Detection-System ipynb - Visual Studio Code 29-01-2026 18_30_52" src="https://github.com/user-attachments/assets/4a81b9eb-086c-4573-9f82-df3e9a5f6b97" />
