# CPV301 - Traffic Sign Classification with HOG and LinearSVC

This repository contains the notebooks and paper artifacts for a CPV301 project on traffic sign classification using the German Traffic Sign Recognition Benchmark (GTSRB).

The implemented pipeline crops annotated traffic sign regions, resizes them to 32 x 32 pixels, converts them to grayscale, extracts Histogram of Oriented Gradients (HOG) descriptors, standardizes the features, and trains a class-weighted LinearSVC classifier.

## Results

| Metric | Value |
| --- | ---: |
| Validation accuracy | 92.36% |
| Macro F1-score | 93.43% |
| Weighted F1-score | 92.27% |
| W&B training time | 295.68 s |

The official GTSRB test set is used only for qualitative sample inspection in the supplied notebooks. Full official test-set accuracy is not claimed.

## Repository Structure

```text
CPV301/
├── notebooks/
│   ├── data_overview.ipynb
│   ├── traffic_sign_wandb.ipynb
│   ├── visualization_pipeline.ipynb
│   └── visualization_for_paper.ipynb
├── paper/
│   ├── CPV301.pdf
│   ├── main.tex
│   ├── references.bib
│   └── figures/
├── outputs/
└── models/
```

## Notebooks

Run the notebooks in this order:

1. `notebooks/data_overview.ipynb`
2. `notebooks/traffic_sign_wandb.ipynb`
3. `notebooks/visualization_pipeline.ipynb`
4. `notebooks/visualization_for_paper.ipynb`

## Dataset

The dataset is GTSRB. Dataset archives, extracted images, cached HOG features, trained models, and W&B run folders are not included in this repository because of size and reproducibility concerns.

## Setup

```bash
pip install -r requirements.txt
```
