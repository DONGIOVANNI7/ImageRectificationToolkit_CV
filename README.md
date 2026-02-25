# Computer Vision Pipeline: Image Rectification Toolkit

A comprehensive Computer Vision pipeline implemented in Python. This project focuses on building core image processing algorithms **from scratch** (using NumPy) to demonstrate a bottom-up understanding of pixel manipulation, feature extraction, and geometric transformations. For a more detailed analysis check the PDF report!

## 🚀 Features

* **Part A: Convolution & Filtering:** Manual 2D convolution implementation. Includes custom Gaussian and Mean filters, and noise simulation (Gaussian, Salt & Pepper, Poisson).
* **Part B: Edge Detection:** Custom Canny Edge Detector implementation (gradient magnitude, non-maximum suppression, and hysteresis thresholding).
* **Part C: Corner Detection:** Implementation and comparison of Moravec and Harris corner detection algorithms, including multi-scale analysis using Gaussian pyramids.
* **Part D: Document Rectification:** Automated perspective correction (document scanning) using Harris corners, geometric quadrant heuristics, and Homography.

## 📁 Repository Structure

* `ImageRectificationToolkit_CV_2025_Ioannis_Petrakis.ipynb` - The main Jupyter Notebook containing all code and experiments.
* `assets/` - Directory for input test images (e.g., book.jpg, building.jpg, etc.).
* `results/` - Directory containing saved output visualizations.

## 🛠️ Usage

**Clone the repository:**
```bash
git clone https://github.com/DONGIOVANNI7/ImageRectificationToolkit_CV.git
cd ImageRectificationToolkit_CV
