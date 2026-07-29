# Credit Score Classification

DATA 1030 Final Project · Brown University

This project develops an end-to-end machine learning pipeline to classify credit score categories (Poor, Standard, Good) based on a synthetic financial dataset. The analysis compares multiple machine learning models, evaluates predictive performance, and investigates both global and local feature importance. The repository is structured to meet DATA 1030 reproducibility and organization standards.

# Dataset

The dataset is synthetic and comes from Kaggle:
https://www.kaggle.com/datasets/parisrohan/credit-score-classification

This repository includes only small sample files (train_sample.csv, test_sample.csv) for illustration.
To fully reproduce results, please download the complete dataset from Kaggle.

# Repository Structure

The project follows the directory format:

    data/ — raw and sample data files
    figures/ — EDA visualizations, model evaluation plots, SHAP figures
    results/ — saved models, predictions, evaluation metrics
    report/ — final PDF report
    src/ — source code (Jupyter notebooks or Python scripts), including main.ipynb
    environment.yml — conda environment specification
    README.md — project overview and documentation
    LICENSE — project license
    .gitignore — ignored files and directories

# Environment and Dependencies

The project uses: Python 3.13.5

Additional packages listed in environment.yml

To reproduce the environment:
```
conda env create -f environment.yml
conda activate credit-score-project
```

# Running the Analysis
Clone the repository:https://github.com/yhu249/credit-score-classification.git

Create and activate the environment:
```
conda env create -f environment.yml
conda activate credit-score-project
```

Open and run the main notebook:
src/Main.ipynb

The notebook includes exploratory data analysis, preprocessing, model training, evaluation, global feature importance and local feature interpretability. Generated figures are saved in the figures/ directory and model outputs are stored in results.

# License

This project is released under the MIT License.
See the LICENSE file for details.

# Author

Holly Hu
Brown University DATA 1030
