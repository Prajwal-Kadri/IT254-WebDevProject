# Network Intrusion Detection System

Machine-learning experiments and a companion web interface for identifying malicious network connections.

## Project layout

- `KDDCUP99/` — notebook, dataset files, requirements, performance plots, and results
- `NSL-KDD/` — experiment materials for the NSL-KDD dataset

## Models evaluated

The KDD Cup '99 study compares Gaussian Naive Bayes, Decision Tree, Random Forest, SVM, Logistic Regression, Gradient Boosting, and an artificial neural network. The included report records accuracy and runtime comparisons.

## Run the notebooks

Each dataset folder contains a `main.ipynb` notebook. Install the requirements and run the appropriate notebook:

```bash
python -m pip install -r KDDCUP99/requirements.txt
jupyter notebook KDDCUP99/main.ipynb
```

## Web application

A related Flask deployment using the UNSW-NB15 dataset is available in the [IT254-WebDevProject-vercel](https://github.com/Prajwal-Kadri/IT254-WebDevProject-vercel) repository.
