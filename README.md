# PV056 Semestral Project — Human Activity Recognition

**Topic 1**: Classify smartphone inertial sensor recordings into activity classes.
**Dataset**: [UCI HAR — Kaggle](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)
**Deadline**: April 19, 2026

## Requirements checklist

| ID   | Task                                                         | Done |
|------|--------------------------------------------------------------|------|
| R1a  | Visualize class label distribution                           | [ ]  |
| R1b  | Find outliers / anomalies                                    | [ ]  |
| T1a  | Uncover tough cases (T-SNE, error analysis)                  | [ ]  |
| R2a  | HPO (hyperparameter optimization)                            | [ ]  |
| R2b  | Visualize training progress, train to convergence            | [ ]  |
| T1b  | Improve over LSTM baseline (target > 0.8 F1-macro)          | [ ]  |
| R3a  | Confusion matrix + explainability                           | [ ]  |
| R3b  | Present results (table/plot, optional statistical tests)    | [ ]  |

## Structure

```
semestral-project/
├── notebook.ipynb          # Main Colab notebook (all work here)
├── report/                 # LaTeX report (Springer template)
│   └── report.tex
├── outputs/                # Saved figures & tables
└── README.md
```

## Setup

The notebook is self-contained for Colab. To run locally:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch optuna
```

Data is downloaded inside the notebook via `kagglehub` or manual upload.

## Deliverables

- [ ] Colab link (publicly shared, anyone with link can view)
- [ ] `report.pdf` submitted to IS MU vault
- [ ] 10-min presentation (May 4+)
