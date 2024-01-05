# Mask R-CNN Digital Image Processing Project with Detectron2
## Introduction
This project is part of a Digital Image Processing course, focusing on implementing the Mask R-CNN model using the Detectron2 library. Detectron2 is an open-source library created by Facebook AI Research for object detection and instance segmentation in images.

## Clone the Repository

```bash
git clone https://github.com/zhuchi76/Mask-Rcnn.git
cd Mask-Rcnn
```

## Installation and Setup

### Python Virtual Environment

Run the installation script:

```bash
source install_pyenv.sh
```

Set up and activate a Python virtual environment:

```bash
python3.9 -m venv dip
source dip/bin/activate
```

### Install NVIDIA CUDA Toolkit

```bash
sudo apt install -y nvidia-cuda-toolkit
```
### Install Detectron2

Then, run every cell in install.ipynb to install detectron2.

### Configure Detectron2

Rearrange the Detectron2 directory:

```bash
mv detectron2 detectron2_install
cp -r detectron2_install/detectron2 .
cp -r detectron2_install/configs detectron2/
```

The project structure should now look like this:

```bash
Mask-Rcnn/
├── detectron2/
│   ├── configs/
├── detectron2_install/
```

## Running the Project

### Activate the virtual environment:

```bash
source dip/bin/activate
```

### RUN the project

Open and run every cell in maskrcnn.ipynb (still working) to execute the Mask R-CNN model.

### Deactivating the Environment
After you're done, you can deactivate the virtual environment:

```bash
deactivate
```