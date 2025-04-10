![Banner](assets/banner_iris_recognation.png)


# 👁️ Iris Identification using Manual HOG + MLPClassifier (Backpropagation)

This project performs **iris recognition** using grayscale images of rotated iris samples.  
It extracts features using a **manually implemented Histogram of Oriented Gradients (HOG)** and classifies them using an **MLPClassifier (Backpropagation Neural Network)**.

---

## 🚀 Project Overview

- 📷 **Input**: Grayscale rotated iris images
- 🔍 **Feature Extraction**: Manual HOG (using OpenCV gradients + binning)
- 🧠 **Model**: `MLPClassifier` (from scikit-learn)
- 🔧 **Hyperparameter Tuning**: Performed manually
- 🎯 **Classes**: 30 different individuals
- 🧪 **Output**: Predicted identity of the iris image
- 💡 **Bonus**: Prediction from single image available via separate notebook

---

## 🧠 Workflow

```text
📁 Dataset
   ├── Hasil_Rotate_Latih/
   └── Hasil_Rotate_Uji/
       └── [label]-*.jpg

Pipeline:
1. Load and preprocess images
2. Extract label from filename
3. Convert to grayscale and resize
4. Compute manual HOG features
5. Train MLPClassifier with tuned parameters
6. Evaluate accuracy and classification report
7. Predict on single image (separate app)
```

---

## 📊 Evaluation Sample

| Metric     | Result (example) |
|------------|------------------|
| Accuracy   | ~92%             |
| Classes    | 30 individuals   |
| Model Type | MLP (SGD solver) |

*(Evaluate)*

---

## 📂 Repository Structure

```
📦 iris-identification
 ┣ 📄 iris_backprop_PRO_v2.ipynb
 ┣ 📄 Aplikasi_Identifikasi_IRIS.ipynb
 ┣ 📄 README.md
 ┗ 📁 dataset/
     ┣ Hasil_Rotate_Latih/
     ┗ Hasil_Rotate_Uji/
```

---

## 🧪 Single Image Prediction

The file `Aplikasi_Identifikasi_IRIS.ipynb` is used for predicting the identity of a **single iris image**.  
It uses the same manual HOG method and MLP model (already trained) to infer the class label.

---

## 👨‍💻 Author

**Indra Eka Mandriana S.Kom**  
_Machine Learning Engineer_  
[LinkedIn]([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/indra-eka-mandriana-47a885148/)) | [GitHub](https://github.com/indraekam)

---

## ⭐ If you like this project, give it a star!

