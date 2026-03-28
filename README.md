
# Clothing Item Classifier using CNN

## Project Overview

This project implements a **Convolutional Neural Network (CNN)** to classify clothing items from the **Fashion-MNIST dataset**. The model learns to identify 10 different clothing categories using grayscale images of size 28x28 pixels.

---

## Technologies Used

- **Python**
- **TensorFlow / Keras** (for building and training the CNN)
- **NumPy** (for numerical operations)
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for evaluation metrics)

---

## Dataset

- **Fashion-MNIST** dataset: 70,000 grayscale images of clothing items.
- **10 classes**:
  1. T-shirt/Top
  2. Trouser
  3. Pullover
  4. Dress
  5. Coat
  6. Sandal
  7. Shirt
  8. Sneaker
  9. Bag
  10. Ankle Boot

- **Training set:** 60,000 images
- **Testing set:** 10,000 images

---

## How to Run

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   cd Clothing-Item-Classifier-CNN
   ```
````

2. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

3. Activate the virtual environment:
   - **Windows:** `.venv\Scripts\activate`
   - **Linux/Mac:** `source .venv/bin/activate`

4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. (Optional) Load the saved model `models/clothing_item_classifier_cnn.h5` to make predictions without retraining.

---

## Outputs

- **Training Accuracy:** ~91.5%
- **Test Accuracy:** ~90.7%

---

## File Structure

```
Clothing-Item-Classifier-CNN/
│
├── models/                           # Saved CNN model
│   └── clothing_item_classifier_cnn.h5
├── notebooks/                        # Jupyter Notebooks
│   └── Clothing_Item_Classifier.ipynb
├── README.md                         # Project documentation
├── requirements.txt                  # Python dependencies
└── images/                           # Sample images or plots
```

---

## References

- [Fashion-MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
- TensorFlow & Keras documentation
