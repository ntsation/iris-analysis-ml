# Iris Dataset Data Analysis

This repository contains a notebook that performs a detailed data analysis of the **Iris Dataset**, a classic dataset used in machine learning. The code covers various tasks such as exploratory data analysis, descriptive statistics, visualizations, and the training of classification models (such as Random Forest and Support Vector Machine) to predict flower species based on morphological features.

## Requirements

To run this project, you need to have the following Python libraries installed:

- `pandas`: for data manipulation and analysis.
- `numpy`: for numerical operations.
- `matplotlib`: for creating visualizations.
- `seaborn`: for advanced statistical plots and visuals.
- `scikit-learn`: for machine learning tools, including classification algorithms.

You can install all the necessary dependencies at once using the `pip` command:

```bash
pip install -r requirements.txt
```

Alternatively, you can install each library manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Use

### 1. Clone this repository to your local environment

First, clone the repository to your local machine:

```bash
git clone https://github.com/ntsation/IrisML.git
```

### 2. Download the `iris.csv` file

The Iris dataset can be downloaded directly from Kaggle, or you can use a local file if you already have it.

- Download the `iris.csv` file from Kaggle [here](https://www.kaggle.com/datasets/uciml/iris).
- Place the `iris.csv` file in the same directory as the `irisML.ipynb` notebook to ensure the code can access it.

### 3. Run the notebook

Open the Jupyter notebook or any interactive Python environment of your choice and run the `irisML.ipynb` file.

```text
irisML.ipynb
```

### 4. What does the notebook do?

The notebook performs the following tasks:

- **Descriptive Analysis**: Generates descriptive statistics about the flower's characteristics such as sepal length, sepal width, petal length, and petal width.
- **Exploratory Analysis**: Displays class distributions, correlations between features, and differentiation between species of flowers.
- **Visualizations**: Creates graphs to facilitate the interpretation of the data, including scatter plots, box plots, and histograms.
- **Training of Classification Models**: Applies machine learning models such as **Random Forest** and **SVM (Support Vector Machine)** to predict flower species based on the provided features.

### 5. Expected Results

- Descriptive statistics of the dataset's numerical variables.
- Visualizations, such as histograms and boxplots, to explore data distributions.
- Model evaluation results, including **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**.
- Comparison of models to help choose the best classifier for the dataset.

---

## Repository Structure

The repository contains the following files:

- **`irisML.ipynb`**: The Jupyter notebook that contains all the code and analysis.
- **`iris.csv`**: The Iris dataset in CSV format (if not downloaded separately from Kaggle).
- **`requirements.txt`**: A list of dependencies required to run the code. Simply run `pip install -r requirements.txt` to install all the libraries.
