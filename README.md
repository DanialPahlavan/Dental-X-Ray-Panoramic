# Dental X-Ray Panoramic Analysis Notebook

This repository contains a Jupyter Notebook for working with panoramic dental X-ray images. It covers downloading datasets, enhancing image quality, and performing related analyses using modern tools and libraries.

## Contents

### 1. Loading the Dataset
The notebook begins by downloading a dental disease panoramic detection dataset from Kaggle. Ensure you have Kaggle CLI credentials set up to access and download the data.

### 2. Enhancing Image Quality
Using models like GFPGAN and RealESRGAN, the notebook improves the quality of the X-ray images to facilitate better analysis and visualization.

### 3. Setup and Dependencies
The notebook utilizes various tools and libraries, including:
- **KaggleHub**: For dataset download and management.
- **GFPGAN/RealESRGAN**: For enhancing image quality.
- **Git**: To clone repositories for the enhancement models.

### 4. Usage

#### Prerequisites
- Python 3.7+
- Jupyter Notebook or Jupyter Lab
- Kaggle API credentials

#### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/DanialPahlavan/Dental-X-Ray-Panoramic
   cd Dental-X-Ray-Panoramic
   ```
2. Install the necessary Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Dental_X_Ray_Panoramic.ipynb
   ```
4. Follow the cells to download the dataset, enhance images, and analyze the results.

### 5. Notes
- The notebook makes use of shell commands (e.g., `!git clone` and `!cp`) to perform certain actions. Ensure these commands are supported in your environment.
- Image enhancement can be resource-intensive. Use a system with sufficient computational power.

### 6. License
GNU 3 License
---

For questions or contributions, feel free to open an issue or submit a pull request.

