# EEG for BCI

This project is done as a part of course Neural Networks & Fuzzy Logic(BITS F312). 

The project presentation can be found [here](insert link).

#### Team:

- Venkata Sai Kiran Piratla
- Kalimi Venkata Yashwanth Kumar Reddy
- Yaswanth Kumar Rayapati

---

[Deep learning EEG response representation for brain computer interface](https://ieeexplore.ieee.org/document/7260182)

This repository contains code to run experiments which closely simulate those run by Liu Jingwei et al. in the paper linked to above.

The EEG data used in these series of experiments is from [Project BCI - EEG motor activity data set](https://sites.google.com/site/projectbci/), Brain Computer Interface research at NUST Pakistan.

---

## Algorithm:


---

## Observations:

<img src="images/multiscale.png">
<img src="images/singlescale.png">
<img src="images/shallow.png">

---
## Instructions to run:
It is assumed that you have Conda pre-installed.

Open up the terminal and type:

    
    git clone https://github.com/piratlasaikiran/EEG_for_BCI
    cd EEG_for_BCI
    conda env create -f environment.yml
    conda activate nnfl
    cd CNN models
    jupyter notebook
    
    
    
Open up `multi-scale CNN.ipynb`, `shallow CNN.ipynb` and `single-scale CNN.ipynb` to run the respective versions of the implementation.


