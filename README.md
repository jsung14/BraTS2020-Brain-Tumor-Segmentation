# Brain Tumor Segmentation and Prediction Using MONAI & PyTorch

This project implements a deep learning pipeline for brain tumor segmentation and survival prediction using multimodal MRI scans from the BraTS 2020 dataset. The project tackles several tasks related to medical imaging using the MONAI framework and PyTorch. These include tumor segmentation, overall survival prediction, and uncertainty estimation.

## Introduction
The BraTS 2020 dataset consists of multimodal Magnetic Resonance Imaging (MRI) scans from patients with brain tumors (gliomas). These scans include the following modalities:

- T1-weighted (T1) <br>
- Post-contrast T1-weighted (T1ce) <br>
- T2-weighted (T2) <br>
- Fluid Attenuated Inversion Recovery (FLAIR) <br><br>

The dataset is used for:
<br><br>Task 1: Brain tumor segmentation (different sub-regions like necrotic tumor core, peritumoral edema, and enhancing tumor).
<br>Task 2: Predicting overall survival.
<br>Task 3: Distinguishing between pseudoprogression and true tumor recurrence.
<br>Task 4: Estimating uncertainty in segmentation.
## Project Tasks
1. Tumor Segmentation: Using a U-Net-based architecture to segment tumor subregions from multimodal MRI scans.
2. Overall Survival Prediction: Predicting patient overall survival using radiomic features extracted from tumor segmentations.<br>
3. Pseudoprogression vs Recurrence: Using radiomic features to differentiate between pseudoprogression and true tumor recurrence.<br>
4. Uncertainty Estimation: Estimating model uncertainty in tumor segmentation.<br><br>

## Requirements
The project requires the following dependencies:

- Python 3.7+
- PyTorch
- MONAI
- NumPy
- Scikit-learn
- TensorBoard
- Nibabel (for handling .nii files)
- Matplotlib
- Pandas
