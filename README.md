# 🌸 Teachable Machine Image Classifier - Cherry Blossom Example

This project demonstrates an image classifier trained using [Teachable Machine by Google](https://teachablemachine.withgoogle.com/), and tested using a Python script on Google Colab.

The classifier was trained to recognize multiple flower types, and successfully identified a **Cherry Blossom** image with **99.64% confidence**.

---

## 🗂 Project Files

- `keras_Model.h5` – Trained image classification model exported from Teachable Machine.
- `labels.txt` – List of class labels used in the model.
- `test.jpg` – Sample image of a **Cherry Blossom** used for testing.
- `TeachableModel.ipynb` – Google Colab notebook to upload and test the model.
- `screenshot.png` – Screenshot of the classification result.

---

## 🚀 How to Run the Model in Google Colab

1. Open the notebook `TeachableModel.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Upload the following files when prompted:
   - `keras_Model.h5`
   - `labels.txt`
   - `test.jpg` (or your own image for testing)
3. Run all the code cells.
4. View the predicted class and confidence score in the output.

---

## ✅ Example Output

1/1 [==============================] - 1s 1s/step
Class: Cherry Blossom
Confidence Score: 99.64 %
