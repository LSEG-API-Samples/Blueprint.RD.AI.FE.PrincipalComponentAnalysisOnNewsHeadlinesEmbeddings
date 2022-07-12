# Feature Engineering - Principal Component Analysis on news headlines embeddings


## <a id="overview"></a>Overview
One of the fundamental stages of a successful Artificial Intelligence (AI) solution is feature engineering. The goal of the process is maximization of the AI predictive power by transforming the raw data in an effort to provide high insight designed feature sets.

In AI models, we are often confronted by high-dimensional data and features. Generally, a big feature space is considered positive. However, sometimes as dimensionality increases, the volume space increases so fast giving rise to multiple problem. One such is that the available data can become sparse. This causes machine learning models to be less effective and will result in an exponential increase in computational complexity. This issue is referred to as the "curse" of dimensionality and can be tackled by dimensionality reduction techniques. The idea behind dimensionality reduction is trying to represent the variance of the data space with fewer variables while preserving as much of the existing structure in the data as possible. This can be accomplished by keeping existing or creating new features with high separability and variance.

One very common technique for dimensionality reduction is Principal Component Analysis (PCA) which helps us uncover the underlying drivers hidden in our data by summarising huge feature sets into a few principal components.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [pandas](https://pypi.org/project/pandas/), [scikit-learn](https://pypi.org/project/scikit-learn/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Haykaz Aramyan**
