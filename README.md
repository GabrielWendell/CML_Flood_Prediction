# QML Research in Flood Forecasting
## Overview
Welcome to the QML Research in Flood Forecasting Repository, a comprehensive collection of ongoing projects dedicated to developing Predictive Statistics, Machine Learning, Quantum Machine Learning algorithms in flood forecasting.

### Motivation
Natural disasters, particularly floods, pose a significant threat to lives, infrastructure, and economies worldwide. The increasing frequency and intensity of such events, driven by climate change and urbanization, underscore the urgent need for more accurate and reliable forecasting methods. Developing advanced techniques in predictive statistics, machine learning, and quantum machine learning offers the potential to better anticipate these events, providing critical time for preparation and response. By improving the precision of flood predictions, we can mitigate the devastating impacts of these disasters, safeguard communities, and enhance the effectiveness of early warning systems, ultimately contributing to greater resilience in the face of natural hazards.

This repository is organized based on the methods used to conduct the study, each exploring unique aspects of the models analyzed. Below, you will find a brief description of each method, along with links to their respective folders for more detailed information.

---

## Projects
### 1. Predictive Statistics
This project explores the use of predictive statistics for flood forecasting, with a primary focus on autoregressive modeling techniques. The first approach involves the application of methods such as Autoregressive Integrated Moving Average (ARIMA) and Seasonal ARIMA (SARIMA) to analyze and predict key hydrological variables, including water levels and discharge rates. By modeling the temporal dependencies and seasonality inherent in the time series data, these methods aim to produce accurate and reliable forecasts that can be crucial for early flood warning systems.


#### References
> [Ho, S.L. & Xie, M., 1998. *Computers & industrial engineering*, **35**(1-2), pp.213-216.](https://www.sciencedirect.com/science/article/abs/pii/S0360835298000667)

You can check project updates here : [Log 1](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/Project_1/README.md)


### 2. Classical Machine Learning
This project consists of two parts: the first part focuses on the application of K-Nearest Neighbors (KNN) algorithms for both classification and regression tasks, aiming to predict flood occurrences and quantify key hydrological variables such as water levels and discharge rates. By utilizing a time series dataset spanning several decades, the KNN models are trained to identify patterns and make forecasts with high accuracy. In the second part, the project advances to the development of Recurrent Neural Networks (RNNs), which are well-suited for sequential data, to further enhance the predictive capabilities.

#### References
> [Sherstinsky, A., 2020. *Physica D: Nonlinear Phenomena*, **404**, p.132306.](https://www.sciencedirect.com/science/article/pii/S0167278919305974?casa_token=MfYQf8rsvmMAAAAA:pXVCO-ry4R0Oj_vLaJ541uyI6dcbQ7VTsAyc_elwYzqZDtFzWBBMB3nUsCbmeyuwNXnYjnyk8yQt)

You can check project updates here : [Log 2](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/Project_2/log_project2.md)


### 3. Quantum Machine Learning

### References
> [Refs. for QML...]()

You can check project updates here : [Log 3](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/Project_2/log_project2.md)


---

## Installation
First you need to check if you have git software installed on your machine. You can check by typing the following in your terminal:
```terminal
git --version
```

If no version appears, then you will need to download it. Depending on your operating system, you can install it as follows:

I. **Mac OSX**
- Install the package from [https://git-scm.com/download/mac](https://git-scm.com/download/mac).

II. **Linux** \
Depending on your distribution:
   
- Debian and Ubuntu-based distros:
```terminal
sudo apt-get install git
```
- Red-Hat-based distros:
```terminal
sudo yum install git
```

Once done, from a new terminal create a directory dedicated for this tool with the name `Cepheids_Projects`, and from it, clone this github files and intall the necessary components:
```
git clone https://github.com/GabrielWendell/QML_Flood_Prediction/tree/main
cd Cepheids_Projects
pip install -r requirements.txt
```
This will download the code and instructions.


### Repository Structure
```bash
├── Project_1/                      # Folder for Project 1
│   ├── data/                       # Data files related to Project 1
│   ├── notebooks/                  # Jupyter Notebooks for Project 1
│   ├── src/                        # Python scripts for Project 1
│   ├── Plots/                      # Plots related to Project 1
│   ├── logs/                       # Logs from the analysis
│   ├── README.md                   # Detailed README for Project 1
├── Project_2/                     # Folder for Project 2
│   ├── data/                      # Data files related to Project 2
│   ├── notebooks/                 # Jupyter Notebooks for Project 2
│   ├── Plots/                     # Plots related to Project 2
│   ├── src/                       # Python scripts for Project 2
│   ├── logs/                      # Logs from the analysis
│   ├── README.md                  # Detailed README for Project 2
└── README.md                      # General README (this file)
```

### Contributing
We welcome contributions from the academic and scientific communities. If you are interested in collaborating or have any suggestions for improving the projects, please refer to the individual project folders for specific guidelines or reach out via the contact information provided below.

### License
This repository is distributed under the [GNU v.3.0 License](https://github.com/GabrielWendell/Cepheids_Projects/blob/main/LICENSE). Please refer to the license file for more information.

### Contact
For any inquiries related to this repository or ongoing research, please contact:
- **Project Members :**
> - [Gabriel Wendell Celestino Rocha](http://lattes.cnpq.br/0049111339899544)
> - [Leonardo Almeida de Andrade](http://lattes.cnpq.br/7812463045514059)
- **GitHub :**
> - [GabrielWendell](https://github.com/GabrielWendell)
> - [TitanUFRN](https://github.com/titanufrn)

---

### Have fun 😄
