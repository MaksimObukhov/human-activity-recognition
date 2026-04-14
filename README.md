# PV056 Semestral Project — Human Activity Recognition

**Authors**: Maksim Obukhov (582912), ...
**Topic 1**: Classify smartphone inertial sensor recordings into activity classes.
**Dataset**: [UCI HAR — Kaggle](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones)
**Deadline**: April 19, 2026

## Requirements checklist

| ID   | Task                                                         | Done |
|------|--------------------------------------------------------------|------|
| R1a  | Visualize class label distribution                           | [x]  |
| R1b  | Find outliers / anomalies                                    | [x]  |
| T1a  | Uncover tough cases (T-SNE, error analysis)                  | [x]  |
| R2a  | HPO (hyperparameter optimization)                            | [x]  |
| R2b  | Visualize training progress, train to convergence            | [x]  |
| T1b  | Improve over LSTM baseline (target > 0.8 F1-macro)          | [x]  |
| R3a  | Confusion matrix + explainability                           | [x]  |
| R3b  | Present results (table/plot, optional statistical tests)    | [x]  |


## Setup

The notebook is self-contained for Colab.

**Local setup (e.g. DataSpell):**

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Data: download `train.csv` and `test.csv` from [Kaggle](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones) and place in `data/`.
