# Principal Component Analysis (PCA) for Multi-format Document Feature Compression

## Overview

This project implements **Principal Component Analysis (PCA)** from scratch to reduce the dimensionality of feature vectors extracted from multiple file formats. Instead of relying on existing PCA libraries, the project focuses on understanding and implementing the PCA algorithm while maintaining a modular software architecture.

The system supports reading different document formats, extracting feature vectors, performing dimensionality reduction using PCA, and evaluating reconstruction quality through quantitative metrics.

---

## Objectives

The main objectives of this project are:

- Implement the PCA algorithm from scratch.
- Reduce the dimensionality of feature vectors while preserving important information.
- Support feature extraction from multiple document formats.
- Evaluate reconstruction quality using statistical metrics.
- Build a modular and extensible software architecture.

---

## Features

- 📂 Read data from multiple file formats
- 📊 Feature vector generation
- 📉 Custom PCA implementation
- 📈 Data reconstruction
- 📋 Performance evaluation
- 🧩 Modular project architecture

---

## Supported File Types

The project is designed to process feature vectors extracted from different types of files, including:

- CSV
- TXT
- DOCX
- PDF
- XLSX
- Images
- MP3

---

## Technologies

- Python
- NumPy
- Pandas

---

## Project Structure

```text
PCA Project
│
├── Source/
│   ├── Reader/
│   ├── Vectorizer/
│   ├── PCA/
│   ├── Evaluate/
│   └── main.py
│
├── Test_Data/
│
└── README.md
```

---

## PCA Workflow

The project follows the standard PCA pipeline:

1. Read input files.
2. Extract feature vectors.
3. Standardize the data.
4. Compute the covariance matrix.
5. Calculate eigenvalues and eigenvectors.
6. Select principal components.
7. Transform the original data into a lower-dimensional space.
8. Reconstruct the data.
9. Evaluate reconstruction quality.

---

## Evaluation Metrics

The reconstructed data is evaluated using:

- **Mean Squared Error (MSE)**
- **Explained Variance**

These metrics measure how well the reduced-dimensional representation preserves the original information.

---

## How to Run

1. Open the project in your preferred Python environment.
2. Navigate to the `Source` directory.
3. Execute the main program:

```bash
python main.py
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Implementing Principal Component Analysis from scratch.
- Understanding dimensionality reduction techniques.
- Designing modular Python applications.
- Working with feature extraction pipelines.
- Evaluating machine learning algorithms using quantitative metrics.

---

## Future Improvements

Potential future enhancements include:

- Visualize principal components using scatter plots.
- Compare the custom PCA implementation with Scikit-learn's PCA.
- Optimize computational performance for larger datasets.
- Add support for additional evaluation metrics.
- Improve feature extraction for multimedia files.

