[![UNIE Universidad](https://www.fsie.es/documentos/imagenes/Ventajas_afiliados/2024/UNIE/Brand_Unie_Vertical_Positive.png)](https://www.universidadunie.com/programas/master-formacion-permanente-virtual-inteligencia-artificial-deep-learning)

# Máster en Inteligencia Artificial y Deep Learning

## Machine Learning — Decision Trees: Car Evaluation Dataset

Asignatura Machine Learning del Máster en IA y Deep Learning de UNIE. Practical Lab: Decision Tree Classification

---

## Summary

End-to-end Decision Tree pipeline applied to the [Car Evaluation dataset](https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set) (1,728 instances, 6 categorical features, 4-class target). The notebook covers:

- Exploratory data analysis and class imbalance visualisation
- Ordinal encoding with domain-aware category ordering
- Baseline `DecisionTreeClassifier` (Gini and Entropy criteria)
- Hyperparameter tuning with `GridSearchCV` and `RandomizedSearchCV`
- Effect of `max_depth`, `min_samples_split`, `min_samples_leaf`, and `max_features` on accuracy
- Model evaluation: accuracy, classification report, confusion matrix, ROC-AUC (OvR macro)
- Tree visualisation with `plot_tree` and `export_text`
- Feature importance analysis

## Project Structure

```
datasets/
└── car_evaluation.csv          # Car Evaluation dataset (CC0: Public Domain)
src/
└── decision_tree_car_evaluation.ipynb
```

## Quick Start

```bash
# Create and activate environment
python3 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook src/
```

---

## Disclaimer

Provided as is, for academic use only.

## Copyright and License

- Notebook: [MIT License](LICENSE)
- Data: [CC0: Public Domain](https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set)

Developed and tested on Python ≥ 3.10. Dependencies: see `requirements.txt`.
