Tumor Imaging and Clustering Analysis
- This repository contains Jupyter notebooks for processing medical imaging, performing clustering analysis using PCA, and implementing U-Net for tumor segmentation.

Repository Contents:
Imaging Processing and Tumor Mapping.ipynb
- Performs image preprocessing and mapping of tumor regions. Raw images have not been uploaded due to file size constraints. However, the resulting .pkl file can be found in the Releases tab.

PCA and Clustering.ipynb
- Applies Principal Component Analysis (PCA) and clustering techniques to analyze imaging data.

U-Net Prediction and Validation.ipynb
- Implements a U-Net deep learning model for tumor segmentation and validates its performance.

Installation
- To run the notebooks, install the required dependencies:
	pip install -r requirements.txt

Usage
- Clone this repository:
	git clone https://github.com/tylervasse/DOCI-Prediction.git
	cd DOCI-Prediction
- Install dependencies.
- Open Jupyter Notebook:
	jupyter notebook
- Run the notebooks in order for proper workflow.

Requirements
- The required Python libraries are listed in requirements.txt. Ensure you have Python 3.1 installed.
