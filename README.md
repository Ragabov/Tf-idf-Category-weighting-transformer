# Tf-idf类目加权转换 Tf-idf-Category-weighting-transformer

[![PyPI version](https://img.shields.io/badge/python-2.7-blue.svg)](https://badge.fury.io/py/Tf-Idf-CategoryWeighting)
[![PyPI version](https://badge.fury.io/py/Tf-Idf-CategoryWeighting.svg)](https://badge.fury.io/py/Tf-Idf-CategoryWeighting)

Formula Derivation
=========================
![main-formula](https://github.com/ArnoldGaius/Tf-idf-Category-weighting-transformer/blob/master/formula_png/main-formula.png)
![wt](https://github.com/ArnoldGaius/Tf-idf-Category-weighting-transformer/blob/master/formula_png/wt-formula.png)
![N](https://github.com/ArnoldGaius/Tf-idf-Category-weighting-transformer/blob/master/formula_png/N.png)
![Nt](https://github.com/ArnoldGaius/Tf-idf-Category-weighting-transformer/blob/master/formula_png/Nt.png)

Sample Usage
===================
```python
>>> import TfIdfCategoryWeighting
>>> Tf_idf_cw_vectorizer = TfIdfCategoryWeighting.TfidfPro_Vectorizer(use_idf=True,use_Wt=True)
>>> Tf_idf_cw_vectorizer.fit(X,Y)
>>> X_vec = Tf_idf_cw_vectorizer.transform(X)
```

Installation
----------------------
    $ pip install Tf-Idf-CategoryWeighting
