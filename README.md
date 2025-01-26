# Ultralytics Installation and Usage Guide
## 1. Installation
For more detailed installation instructions, visit the [Quickstart Guide](https://docs.ultralytics.com/quickstart/#understanding-settings).
### 1.1 Install the Ultralytics Package from PyPI
To install the Ultralytics package using pip, run the following command:
```bash
pip install ultralytics
```
### 1.2 Install the Ultralytics Package from Conda
For Conda users, install the Ultralytics package with the following command:
```bash
conda install -c conda-forge ultralytics
```
This method ensures compatibility with other packages in your environment.
### 1.3 Installing in CUDA Environments
For CUDA environments, it is recommended to install Ultralytics, PyTorch, and PyTorch-CUDA simultaneously to resolve any potential conflicts. Use the following command:
```bash
conda install -c pytorch -c nvidia -c conda-forge pytorch torchvision pytorch-cuda=11.8 ultralytics
```
## 2. Command Line Interface (CLI)
The Ultralytics CLI allows for simple, single-line commands without requiring a Python environment. All tasks can be executed directly from the terminal using the `yolo` command.
## 3. Usage
### 3.1 Prediction
To run a prediction task using the CLI:
```bash
yolo predict model=yolo11n.pt imgsz=640 conf=0.25
```
### 3.2 Training
To train a detection model with specific parameters:
```bash
yolo train data=coco8.yaml model=yolo11n.pt epochs=10 lr0=0.01
```
## 4. Result of Object Detection
![YoloV11-ezgif com-crop](https://github.com/user-attachments/assets/727a459c-bf30-486c-8f00-57ca651ea13d)


