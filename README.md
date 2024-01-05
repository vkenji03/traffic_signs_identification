# Training a model to detect the U.S traffic signs

In this project different models were trained to detect the U.S traffic signs and traffic lights. The pre-trained model [Ultralytics YOLOv8](https://docs.ultralytics.com/) was used along with transfer learning and the dataset was the [Self-Driving Cars Computer Vision Project](https://universe.roboflow.com/selfdriving-car-qtywx/self-driving-cars-lfjou/dataset/2) provided on the Roboflow website.

## Getting Started

All models have already been trained so if you only want to check the results there is no need to run the notebook, you can just open the main.ipynb file. However, if you want to use the model, train new models or fine-tune them even further feel free to try new things, but before doing this make sure to install the required packages.

### Running localy

After clonning the repository go to its directory, for example doing this

```bash
cd traffic_signs_identification
```

Them you have to install the packages, here I used pip and venv:

Creates the virtual environment
```bash
python3 -m venv .venv
```

Activates the venv
```bash
source .venv/bin/activate
```

Install the packages
```bash
python3 -m pip install -r requirements.txt
```

Deactivate the venv
```bash
deactivate
```

Now just run the notebook

### Running on Colab

After oppening the main.ipynb upload all files and directories to the collab environment

Install the packages before running the notebook. 
```bash
! pip install -r requirements.txt
```

Now just run the notebook
