## Main Code

The main workflow and code are contained in [`main.ipynb`](main.ipynb). The notebook covers:
- Downloading and preparing datasets (including additional data from external sources)
- Exploratory Data Analysis (EDA) on essay datasets
- Feature engineering (e.g., word counts, TF-IDF vectorization)
- Training and evaluating classification models (Logistic Regression, Random Forest)
- Visualizing feature importances and model results

## Getting Started

### 1. Install Dependencies

Before running the notebook, install the required Python packages:

```bash
pip install -r requirements.txt
```

### 2. Download Data

The notebook will automatically download the necessary datasets from Kaggle. Make sure you have Kaggle API credentials set up. See [Kaggle API documentation](https://www.kaggle.com/docs/api) for instructions.

### 3. Run the Notebook


## Requirements

All dependencies are listed in [`requirements.txt`](requirements.txt).

## Credits

- Parts of the EDA are adapted from [this Kaggle notebook](https://www.kaggle.com/code/alexia/kerasnlp-starter-notebook-llm-detect-ai-generate/notebook).
- Additional data borrowed from [DAREK KŁECZEK's Kaggle discussion](https://www.kaggle.com/competitions/llm-detect-ai-generated-text/discussion/455517).