# ⚙️ Hand-Made Data Standardizer

A lightweight Python implementation of **feature standardization (z-score normalization)** without relying on external libraries like scikit-learn. This project demonstrates the fundamentals of preprocessing numerical data manually for machine learning models.

## 🧮 What It Does

- Computes the **mean** and **standard deviation** of each feature
- Applies **z-score normalization**:  
  \[
  z = \frac{x - \mu}{\sigma}
  \]
- Supports restoring the original values from standardized data
- Provides a clean class-based interface

## 📁 Project Structure

```text
data-hand-made-standardizer/
├── src/
│   ├── standardizer.py     # Core logic for manual z-score normalization
│   └── main.py             # Example usage and testing
├── data/
│   └── dataset.csv         # Sample dataset (optional)
├── notebooks/
│   └── demo.ipynb          # Interactive notebook for demonstration
├── outputs/
│   └── transformed.csv     # Standardized output
├── requirements.txt
└── README.md
```
## 📌 TODO
Add unit tests

Add min-max normalization as an option

Add CLI support

Support for missing values

## 👤 Author
Saran Jaya Thilak
