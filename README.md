# DeepLearn2025: Learning demographics from retinal fundus images

This repository contains the code for the DeepLearn2025 summer school.

The code aims to learn demographics from retinal fundus images using deep learning in two ways:
1) Using the raw images as input and training a model to predict the demographics
2) Using the RETFound features as input and training a model to predict the demographics

The code is organized as follows:

- `feature_extraction`: folder with code to extract features from the retinal fundus images using RETFound. For convenience, the features are already available in the `features` folder.
- `demographics_prediction`: folder with code to train models to predict the demographics:
    - `Age_from_CFP.ipynb`: notebook to train a model to predict the age from the CFP images - Colab version [here](https://colab.research.google.com/drive/1U4IIbNoWM7X8ENsr3CrYfx6_0TL0p4I1?usp=sharing)
    - `demographics_RETFound_features.ipynb`: notebook to train a model to predict the demographics from the RETFound features - Colab version [here](https://drive.google.com/file/d/1OLB6L5m5Utjk6ZC-oUBuRRnXc4dSI6UO/view?usp=sharing)


## Setup

1. Clone the repository
2. Install the dependencies
3. Run the code

## Usage