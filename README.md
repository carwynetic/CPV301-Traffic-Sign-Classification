# CPV301 - Traffic Sign Classification with HOG and LinearSVC

This project implements a traffic sign classification pipeline on the GTSRB dataset using ROI cropping, grayscale preprocessing, HOG feature extraction, StandardScaler, and LinearSVC.

## Results

Validation accuracy: 92.36%  
Macro F1-score: 93.43%  
Weighted F1-score: 92.27%

## Repository Structure

- `notebooks/`: exploratory analysis, W&B training notebook, and paper visualizations
- `paper/`: final report PDF, LaTeX source, and figures
- `src/`: reusable Python scripts
- `outputs/`: generated metrics and tables
- `models/`: local trained models, not tracked by Git

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
