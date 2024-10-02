# Model-Interpretability
This project uses a loan dataset to predict loan approvals using Linear, Tree-Based models, and AutoML H2O. It incorporates SHAP and LIME for model interpretability, providing insights into how model predictions are influenced by different features.

---

## Aim
Interpret results from multiple models:
- Linear Model
- Tree Based Model
- AutoML H2O's best model

Using:
- SHAP analysis
- LIME analysis

---

## Variable Description
Variables include the percentage of the premium paid by cash or credit, age in days of policyholder, income, late premium counts, underwriting score, premiums paid, sourcing channel, and residence type.

---

## Installation
```bash
pip install shap lime requests tabulate "colorama>=0.3.8" future h2o
```

---

## Usage
Import necessary libraries such as numpy, pandas, matplotlib, seaborn, sklearn, h2o, shap, and lime. Set up and run models including linear regression, tree-based models, and H2O AutoML. Conduct model interpretability analyses using SHAP and LIME.

---

## Models
- **Linear Model**: Fit and interpret a linear regression.
- **Tree Based Model**: Fit and visualize a decision tree.
- **H2O AutoML**: Find the best model automatically with H2O and interpret it.

---

## SHAP and LIME Analyses
Perform SHAP and LIME analyses for both linear and tree-based models to understand the impact of each feature. These analyses help explain model predictions in terms of the contributions of individual features.

---

## Conclusion
Comparative interpretation of SHAP vs. LIME for model interpretability highlights their approaches and effectiveness in feature importance evaluation. SHAP provides a global perspective while LIME offers local explanations, making both essential depending on the interpretability needs.

---

## License
MIT License

---

Copyright (c) 2023 Charmi Parmar

---

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

---

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## References
- Scikit-learn official documentation: [https://scikit-learn.org/stable/modules/preprocessing.html](https://scikit-learn.org/stable/modules/preprocessing.html)
- SHAP official documentation: [https://shap.readthedocs.io/en/latest/index.html](https://shap.readthedocs.io/en/latest/index.html)
- Molnar, C. (2022). Interpretable Machine Learning: A Guide for Making Black Box Models Explainable (2nd ed.): [christophm.github.io/interpretable-ml-book/](https://christophm.github.io/interpretable-ml-book/)
- Articles on SHAP and LIME analyses: [https://towardsdatascience.com/explain-your-model-with-the-shap-values-bc36aac4de3d](https://towardsdatascience.com/explain-your-model-with-the-shap-values-bc36aac4de3d), [https://medium.com/@kalia_65609/interpreting-an-nlp-model-with-lime-and-shap-834ccfa124e4](https://medium.com/@kalia_65609/interpreting-an-nlp-model-with-lime-and-shap-834ccfa124e4)
