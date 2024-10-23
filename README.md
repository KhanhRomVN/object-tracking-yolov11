# Dataset
[1]. Motorcycle: https://universe.roboflow.com/bollard/smart-bollard-systemv2/dataset


# User Guide for YOLOv11 Tracking Project

## Steps to Set Up the Environment

1. **Create a virtual environment**: 
   ```bash
   python -m venv venv
   ```

2. **Activate the virtual environment**: 
   ```bash
   .\venv\Scripts\activate
   ```

3. **Install the packages**: 
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the file**: 
   ```bash
   train_yolov11.ipynb
   ```

## Project Structure
object-tracking-yolov11/
│
├── data/ # Directory containing data
│ ├── data.yaml # Data configuration file
│ ├── train/ # Directory containing training data
│ └── valid/ # Directory containing validation data
│
├── notebooks/ # Directory containing Jupyter notebooks
│
├── requirements.txt # File containing necessary libraries
│
└── README.md # User guide for the project


## Sample File `data.yaml`:
train: ../train/images
val: ../valid/images
nc: 1
names: ['motorcycle']
roboflow:
workspace: bollard
project: smart-bollard-systemv2
version: 1


## Introduction to the Packages

This project uses the following packages:

- **Ultralytics YOLO**: A powerful library for object detection, allowing you to easily train and deploy YOLOv11 models.
- **Pandas**: A library for data manipulation and analysis.
- **NumPy**: A library for numerical computations and array processing.
- **Matplotlib**: A library for plotting graphs and visualizing data.

## Links

- **Project Repo**: [object-tracking-yolov11](https://github.com/KhanhRomVN/object-tracking-yolov11)
- **Developer**: [KhanhRomVN](https://github.com/KhanhRomVN)

---

Please ensure that you have followed the steps to set up the environment before running the project. If you have any questions, feel free to contact me through the links above!