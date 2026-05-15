#  Scikit-Learn Cookbook

> Over 80 recipes for machine learning in Python with scikit-learn

A comprehensive, hands-on collection of Jupyter Notebooks covering the full machine learning pipeline — from data preprocessing to model deployment — using [scikit-learn](https://scikit-learn.org/).

## 📖 Table of Contents

| # | Chapter | Topics Covered |
|---|---------|---------------|
| 01 | **API Elements of scikit-learn** | Estimators, transformers, pipelines, datasets API, fit/predict paradigm |
| 02 | **Data Preprocessing** | Scaling, normalization, encoding, imputation, feature extraction |
| 03 | **Dimensionality Reduction** | PCA, LDA, t-SNE, feature selection, variance thresholding |
| 04 | **Models with Distance Metrics and Nearest Neighbors** | KNN classification & regression, distance metrics, ball trees, KD-trees |
| 05 | **Linear Models and Regularization** | Linear regression, Ridge, Lasso, ElasticNet, SGD |
| 06 | **Advanced Logistic Regression** | Binary & multiclass classification, regularization, ROC curves |
| 07 | **Support Vector Machines and Kernel Methods** | SVM classification & regression, kernel tricks, hyperparameter tuning |
| 08 | **Tree-Based Algorithms and Ensemble Methods** | Decision trees, Random Forest, Gradient Boosting, AdaBoost, bagging |
| 09 | **Text Processing and Multiclass Classification** | TF-IDF, CountVectorizer, text pipelines, multiclass strategies |
| 10 | **Clustering Techniques** | K-Means, DBSCAN, hierarchical clustering, silhouette analysis |
| 11 | **Novelty and Outlier Detection** | Isolation Forest, One-Class SVM, LOF, elliptic envelope |
| 12 | **Cross-Validation and Model Evaluation** | K-Fold, stratified CV, GridSearchCV, scoring metrics, learning curves |
| 13 | **Deploying Models in Production** | Model serialization (joblib/pickle), pipelines for production, model serving |

##  Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/farrelrassya/scikit-learn-cookbook.git
cd scikit-learn-cookbook

# Install dependencies
pip install scikit-learn numpy pandas matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook
```

### Key Dependencies

| Package | Purpose |
|---------|---------|
| `scikit-learn` | Machine learning algorithms & utilities |
| `numpy` | Numerical computing |
| `pandas` | Data manipulation & analysis |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical visualization |

##Repository Structure

```
scikit-learn-cookbook/
├── 01. API Elements of scikit-learn/
├── 02. Data Preprocessing/
├── 03. Dimensionality Reduction/
├── 04. Models with Distance Metrics and Nearest Neighbors/
├── 05. Linear Models and Regularization/
├── 06. Advanced Logistic Regression/
├── 07. Support Vector Machines and Kernel Methods/
├── 08. Tree-Based Algorithms and Ensemble Methods/
├── 09. Text Processing and Multiclass Classification/
├── 10. Clustering Techniques/
├── 11. Novelty and Outlier Detection/
├── 12. Cross-Validation and Model Evaluation/
├── 13. Deploying Models in Production/
└── README.md
```

Each chapter folder contains Jupyter Notebooks (`.ipynb`) with self-contained recipes that include explanations, code, and visualizations.

##How to Use This Cookbook

1. **Sequential learning** — Work through chapters 01–13 in order for a complete ML curriculum.
2. **Recipe-based** — Jump to any specific chapter for targeted recipes on a particular topic.
3. **Reference** — Use individual notebooks as quick references for specific scikit-learn techniques.

Each notebook is designed to be self-contained with:
- Clear problem statements
- Step-by-step code walkthroughs
- Visualizations of results
- Practical tips and best practices

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Open an issue for bugs or suggestions
- Submit a pull request with improvements
- Add new recipes or enhance existing ones

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- [scikit-learn documentation](https://scikit-learn.org/stable/documentation.html)
- [scikit-learn Cookbook, Third Edition](https://www.packtpub.com/) — Packt Publishing
- The scikit-learn community and contributors

---

⭐ **If you find this repository helpful, please consider giving it a star!**
