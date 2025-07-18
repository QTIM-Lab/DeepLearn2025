# DeepLearn2025: Learning demographics from retinal fundus images

This repository contains the code for the DeepLearn2025 summer school.

The code aims to learn demographics from retinal fundus images using deep learning in two ways:
1) Using the raw images as input and training a model to predict the demographics
2) Using the RETFound features as input and training a model to predict the demographics

The code is organized as follows:

- `feature_extraction`: folder with code to extract features from the retinal fundus images using RETFound. For convenience, the features are already available in the `features` folder.
    - `extract_retfound_features.ipynb`: notebook to extract the RETFound features from the raw images - Colab version [here](https://drive.google.com/file/d/1uAZ7SOPxHSl2g0U6pm8Ht530GUgTo4Hd/view?usp=sharing)
- `demographics_prediction`: folder with code to train models to predict the demographics:
    - `demographics_resnet.ipynb`: notebook to train a model to predict the age from the CFP images - Colab version [here](https://drive.google.com/file/d/11IIWWg_rwYkKGJ3FzrRPcid0Erqq5Tgu/view?usp=sharing)
    - `demographics_RETFound_features.ipynb`: notebook to train a model to predict the demographics from the RETFound features - Colab version [here](https://drive.google.com/file/d/1OLB6L5m5Utjk6ZC-oUBuRRnXc4dSI6UO/view?usp=sharing)

Already trained models are available in the `results` folder, downloadable [here]() as a zip file.

To download, run:
`gdown https://drive.google.com/uc?id=1c0MXiUnsxstsIK0ETjD1ZBs9iU_kryHy`
