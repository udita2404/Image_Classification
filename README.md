
# Image Classification Using Landmark Dataset

This project focuses on building an image classification pipeline using metadata from a landmark recognition dataset. The workflow includes data preprocessing, label encoding, and optional image retrieval for visualization.

---

## 📌 Project Overview

The goal of this project is to:
- Process and encode labels from a CSV dataset containing image IDs and landmark labels.
- Retrieve and visualize images (optional, based on dataset accessibility).
- Prepare the dataset for future deep learning or classification model training.

---

## 📁 Dataset

The dataset used includes:
- A `.csv` file with the following columns:
  - `id`: The unique image identifier (image name without extension).
  - `landmark_id`: The label corresponding to a landmark class.

The images are assumed to be accessible either locally or from an online source like the Google Landmark Recognition dataset (if available).

---

## 🔧 Project Features

- ✅ Label encoding using `sklearn.preprocessing.LabelEncoder`
- ✅ CSV-based metadata processing
- ✅ Utility functions for:
  - Encoding/decoding labels
  - Optional image retrieval using constructed URLs
- ✅ Basic visualization of sample images (where accessible)

---

## 🧪 Dependencies

Make sure to install the required Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib pillow scikit-learn opencv-python
```

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Place your CSV file (e.g., `train.csv`) in the working directory.
3. Open `Image_classification.ipynb` and follow the notebook cells.
4. Modify the `base_path` or image retrieval code depending on image access method:
   - Local filesystem
   - External dataset URLs (e.g., Google Cloud)

---

## 🖼 Sample Output

If image access is enabled, the notebook displays a grid of randomly selected images from various classes to visualize the distribution and structure.

---

## 📌 Author

**Udita Srivastava**  
GitHub: [udita2404](https://github.com/udita2404)

---

