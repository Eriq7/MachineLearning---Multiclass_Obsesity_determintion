Multi-Class Classification — OvR vs OvO (Logistic Regression)

This project demonstrates a multi-class classification pipeline that compares One-vs-Rest (OvR) and One-vs-One (OvO) logistic regression strategies.
It provides an easy way to evaluate and visualize which approach delivers higher accuracy and more robust performance.


🧰 Tech Stack

Python 3.10+

NumPy, Pandas – data processing

scikit-learn – LogisticRegression, OneVsRestClassifier, OneVsOneClassifier, cross-validation

Matplotlib / Seaborn – visualization

Jupyter Notebook – interactive workflow


🤖 Why Machine Learning?

Traditional rule-based methods or manual analysis often fail when dealing with multi-class problems because:

They require manual feature engineering for each class.

They do not scale well when the number of categories grows.

Accuracy heavily depends on human-defined rules, which may be biased or incomplete.

By applying Machine Learning in this project, we gain:

Scalability → OvR and OvO strategies allow classification across many classes without rewriting rules.

Automation → feature importance is learned directly from data rather than hand-designed.

Performance-driven insights → cross-validation provides objective accuracy and F1 comparisons, showing which strategy is better supported by the data.

Reusability → once trained, the model can be applied to new datasets instantly with minimal changes.

👉 In short: ML transforms the classification problem into a repeatable, data-driven, and adaptive process, ensuring that the best approach (OvR vs. OvO) can be identified quickly and applied to real-world scenarios.


📊 Feature Importance

The notebook also includes a feature importance analysis by averaging absolute coefficients across classifiers
By this project, the top 3 features that will effect Obesesity level are --> weight, gender, height


🔄 Pipeline & Reusability

By building the model inside a scikit-learn Pipeline, this project ensures that the workflow is:

Reproducible → preprocessing (e.g., scaling) and model training are bundled together.

Reusable → anyone can run the model with minimal setup.

Plug-and-Play → just provide a data path, and the pipeline handles cleaning, scaling, training, and evaluation automatically.
