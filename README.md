## 🍅 Tomato Leaf Disease Detection Using Deep Learning

### 🧠 Objective

Develop a deep learning-based image classification model to automatically detect tomato leaf diseases using Convolutional Neural Networks (CNNs), aiming to support early detection in agriculture.

---

### 📂 Dataset

* **Source**: *(e.g., Kaggle PlantVillage dataset or a custom dataset)*
* **Classes**:

  * Tomato\_\_\_Bacterial\_spot
  * Tomato\_\_\_Early\_blight
  * Tomato\_\_\_Late\_blight
  * Tomato\_\_\_Leaf\_Mold
  * Tomato\_\_\_Septoria\_leaf\_spot
  * Tomato\_\_\_Spider\_mites
  * Tomato\_\_\_Target\_Spot
  * Tomato\_\_\_Tomato\_YellowLeaf\_Curl\_Virus
  * Tomato\_\_\_Tomato\_mosaic\_virus
  * Tomato\_\_\_healthy
* **Structure**: Images are organized in `train`, `val`, and `test` directories by class.

---

### 🔧 Methodology

* **Model**: Fine-tuned MobileNetV2 (pretrained on ImageNet).
* **Data Augmentation**: Applied using Keras `ImageDataGenerator`.
* **Preprocessing**: Images resized and normalized.
* **Unique Feature**: Uses SHA256 hash to detect whether an image was already in the training data.

---

### ✅ Features

* 🔍 Real-time prediction of disease from uploaded leaf images.
* 🔐 Identifies if the uploaded image was part of training data (via SHA256 hashing).
* 🌿 Useful for farmers and agronomists to identify diseases early and take preventive actions.

---

### 📊 Model Performance

* **Model Used**: MobileNetV2
* **Training Tool**: Google Colab
* **Validation Accuracy**: 90.62%

---


### 🖼️ Sample Output

Prediction output includes:

* Predicted disease class
* Model confidence score
* Notification if image was already part of the dataset

---

### 📚 Requirements

* Python 3.x
* TensorFlow/Keras
* NumPy, Matplotlib
* Google Colab (preferred for GPU usage)

---

### 🙋‍♀️ Author

**Aalisha Patwekar**


