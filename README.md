# BreastCancerPrediction

## What is it?

The **Breast Cancer Prediction project** is a project that uses the breast cancer cell information in the *data.csv* file to train various machine learning algorithms in order to determine the type of cancer cell (malignant or benign) for a given test data.

This project was written in *Jupyter Notebook* within the *Anaconda Navigator* environment.


## Installation

1) First, you need to download python from [here](https://www.python.org/downloads/). 
1) You need the **anaconda navigator** environment management in order to install jupyter notebook. [download anaconda from here](https://www.anaconda.com/download/success) 

**NOT**: Or you can install jupyter notebook without anaconda navigator with the command below but anaconda is recommended.

```bash
pip install notebook
```

3) Open anaconda prompt and install jupyter notebook with command below:
```bash
conda install anaconda::jupyter
```
4) Open jupyter notebook with command below in anaconda prompt:

```bash
jupyter notebook
```
## Usage

Open the **.jpynb** files in the "files" section of this repository one by one and paste the code from the .jpynb files into your own Jupyter Notebook.

For example, in order to train Artificial Neural Network(ANN) model, first import the libraries below:

```python
import pandas as pd
import numpy as np
import seaborn as sns
from matplotlib import pyplot as plt
import plotly.express as px
from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import LabelEncoder
from sklearn import decomposition
from sklearn import datasets
from sklearn import metrics 
from sklearn.metrics import confusion_matrix, RocCurveDisplay
from sklearn.model_selection import train_test_split
import keras
from keras.models import Sequential
from keras.layers import LeakyReLU,PReLU,ELU
from keras.layers import Dropout
from keras.models import Sequential
from keras.layers import Dense, Dropout
from sklearn.model_selection import GridSearchCV
```
Then, from the .jpynb files in the "files" section of this reposiory, copy the entire code block by block for whichever model you want to train and see the test result, and paste it into your own Jupyter Notebook. Run the code block by block.



