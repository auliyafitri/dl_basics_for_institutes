[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/auliyafitri/dl_basics_for_institutes/HEAD)


<h2>List of tutorials:</h2>

* Introduction
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/auliyafitri/dl_basics_for_institutes/blob/main/01_Introduction_Notebook.ipynb)
* Regression
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/auliyafitri/dl_basics_for_institutes/blob/main/02_Regression_Tutorial.ipynb)
* Classification
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/auliyafitri/dl_basics_for_institutes/blob/main/03_Classification_Tutorial.ipynb)
* Image Classification
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/auliyafitri/dl_basics_for_institutes/blob/main/04_Image_Classification_Tutorial.ipynb)
* Variational Autoencoder
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/auliyafitri/dl_basics_for_institutes/blob/main/05_VAE_Tutorial.ipynb)


All files are taken from https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html and https://github.com/Atcold/pytorch-Deep-Learning


````Python
git clone https://github.com/auliyafitri/dl_basics_for_institutes.git
cd dl_basics_for_institutes/
curl -LsSf https://astral.sh/uv/install.sh | sh
uv init
uv add setuptools wheel torch torchvision torchtext torchsummary torchinfo torchviz numpy matplotlib seaborn tqdm scikit-learn debugpy ipywidgets jupyterlab datasets transformers
````

The, activate the environment and launch the jupyterlab
```bash
source .venv/bin/activate
jupyter lab
```
