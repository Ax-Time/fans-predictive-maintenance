# fans-predictive-maintenance
A machine learning model trained on audio data from industrial fans to perform predictive maintenance.

## To load the data, download the data from the following link and extract it into the data folder:
https://polimi365-my.sharepoint.com/:f:/r/personal/10532347_polimi_it/Documents/MIMII%20dataset/fan?csf=1&web=1&e=RNKy3w

The folder structure should be like this:
```
data
└───id_00
│       X.npy
│       y.npy
└───id_01
│       X.npy
│       y.npy
└───id_02
│       X.npy
│       y.npy
└───id_03
        X.npy
        y.npy
```
And data folder should be in the root directory of the project.

## To install dependencies run:
It is recommended to create a python virtual environment before installing dependencies.
To create a virtual environment run:
```
python -m venv venv
```
To activate the virtual environment run:
```
source venv/bin/activate
```
To install dependencies run:
```
pip install -r requirements.txt
```
