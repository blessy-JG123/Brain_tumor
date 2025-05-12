Brain Tumor Segmentation using OpenCV and Deep Learning

This project automates the segmentation of brain tumors from MRI images
using traditional image processing and deep learning (U-Net). It includes
preprocessing, model training, evaluation, and deployment using Streamlit.
Dataset:
- The dataset contains MRI images and corresponding binary masks.
- White pixels (255) in the mask indicate tumor regions.
- Black pixels (0) indicate healthy tissue.
Features:
- Preprocessing of images (normalization, resizing)
- Exploratory Data Analysis (EDA)
- Traditional methods: Thresholding, Edge &amp; Contour detection
- Deep Learning using U-Net for accurate segmentation
- Evaluation using Dice Score, IoU, Precision, Recall
- Streamlit app for user interaction (upload &amp; visualize results)
How to Run:
1. Clone the repository.
2. Place your dataset in the `data/` directory.
3. Run the notebook:
jupyter notebook Brain_Tumor_Segmentation.ipynb
4. To deploy:
streamlit run app.py
Requirements:
Install required packages:
```bash
pip install numpy opencv-python tensorflow matplotlib streamlit

�� Model Evaluation Metrics
 Dice Coefficient
 IoU (Intersection over Union)
 Precision / Recall
 Inference Time
�� Streamlit App
 Upload MRI image
 View predicted segmentation mask
o Download result as image

�� Deliverables
 Trained model file (e.g., model.h5)
 Streamlit app (app.py)
 Jupyter notebook with full workflow
 README documentation
