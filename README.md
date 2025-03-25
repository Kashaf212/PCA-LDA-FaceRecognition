# Face vs. Non-Face Classification using PCA, LDA, and KNN

This project performs **face vs. non-face image classification** using two popular dimensionality reduction techniques: **PCA (Principal Component Analysis)** and **LDA (Linear Discriminant Analysis)**. After dimensionality reduction, classification is done using a **K-Nearest Neighbors (KNN)** classifier.

---

##  Project Overview

- Dataset: Grayscale face and non-face images (resized to 92x112)
- Dimensionality Reduction:
  - **PCA**: Keeps maximum variance
  - **LDA**: Maximizes class separability
- Classification: **KNN (k=1)**
- Visual Analysis:
  - Eigenfaces (principal components)
  - Failure and success cases
  - Accuracy trends with varying data

---


---

##  Steps Performed

1. **Load and Flatten Images**
2. **Label and Shuffle Data**
3. **Train-Test Split (Flexible ratio)**
4. **Apply PCA / LDA**
5. **Project Data into Reduced Space**
6. **Train KNN Classifier**
7. **Evaluate Accuracy**
8. **Visualize Eigenfaces and Results**
9. **Analyze Performance under Different Scenarios**

---

## Key Results

| Technique | Accuracy (k=1) |
|-----------|----------------|
| PCA       | **94%**        |
| LDA       | **78.75%**     |

- PCA retained **85% variance** using ~42 components.
- LDA used 1 component (binary classification).

---

## Visualizations

- Eigenfaces
- Failure vs. Success classification examples
- Accuracy vs. number of non-face images
- Comparison between 50-50 and 70-30 train-test splits

---

##  How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/yourprojectname.git
   cd yourprojectname
   ```
2. Install dependencies:
   ``` bash
   pip install numpy matplotlib pillow scikit-learn
   ```
3. Run the main notebook or script in your preferred IDE (e.g., PyCharm, Jupyter, VSCode).

## Dependencies

- numpy  
- matplotlib  
- Pillow  
- scikit-learn  

## Concepts Used

- Eigenfaces  
- Covariance matrices  
- Eigen decomposition  
- Between-class and within-class scatter  
- Dimensionality reduction  
- K-Nearest Neighbors (KNN)  


### Feel free to fork or star the project! Contributions are welcome.
