![repo_preview_wide](https://github.com/AlexanderShulzhenko/Short-term-Volatility-Prediction/assets/80621503/f2e6f611-f992-48ac-aa78-7975d9b3914d)

# Short-term volatility prediction with LightGBM

This repo introduces a framework with implemented **LightGBM model** and **feature engineering scripts** to predict **short-term volatility fluctuations** of financial assets.

Repo caontains proof of concept for the original paper, which could be found via ??

Emphasizing cryptocurrency markets, known for their heightened volatility compared to traditional asset markets, the repo concentrates on engineering predictive features crucial for volatility estimation. The comprehensive methodology delineates the creation of a feature set employing a modular structure. Additionally, it briefly outlines the process of selecting the most informative features. The repo meticulously examines the predictive quality of the generated forecasts while dissecting samples where the model gives wrong predictions. Beyond the developed model, an evaluation of existing models pertaining to this task is conducted.

The structure of this repo is outlined on the fugure below (marked parts are presented in the repo):

<img width="656" alt="Снимок экрана 2023-12-22 в 19 53 08" src="https://github.com/AlexanderShulzhenko/Short-term-Volatility-Prediction/assets/80621503/9a9ba5ae-aca0-443e-8e60-9fd4c5ececd1">

## Repo structure

The repo contains **4 main feature modules**:
- Candlestick features;
- Tech. indicators features;
- Exchange data features;
- Stochastic process features.

Repo also contains **module combination** part, which merges all the features and trains the **model using LightGBM**. This notebook also contains model results analysis and basic statistics needed for the performance check. 
