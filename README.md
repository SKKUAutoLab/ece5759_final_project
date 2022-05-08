<div align="center">

ML Homework: YOLOv5 Object Detection
=============================
`onevision` is a foundational library for computer vision research. 
It includes supporting functions, data types, data classes, layers, losses, 
metrics, ..., datasets, and models.

<p align="center">
  <a href="#overview">Overview</a> •  
  <a href="#getting-started">Getting Started</a> •
  <a href="#contact">Contact</a>
</p>
</div>

## <div align="center">Overview</div>

YOLOv5 🚀 is a family of object detection architectures and models pretrained 
on the COCO dataset, and represents <a href="https://ultralytics.com">Ultralytics</a>
open-source research into future vision AI methods, incorporating lessons learned 
and best practices evolved over thousands of hours of research and development.

<details open>
<summary>Tasks</summary>

- In this homework, you will learn how to use YOLO object detection models on real-world surveillance datasets.
- The model, data, training and testing pipelines have been provided.
- Your job is to perform training and testing YOLOv5 models on the given dataset. 
- You can adjust some basic parameters to make the training faster, or to obtain higher accuracy.
- Deadline: (2 weeks)
</details>

<details open>
<summary>Goals</summary>

- Given a limited amount of training time (2 weeks), you must obtain the highest accuracy on the given dataset.
- At the end, you must make a report containing the following information: 
  - Training time (with respect to different GPU devices), 
  - Model's accuracy (mAP@50) .
- **At the end of this homework, the student with the highest accuracy and training time will be rewarded with a special price.**

</details>


## <div align="center">Getting Started</div>

<details open>
<summary>Prerequisite</summary>

- OS: [**Ubuntu 20.04 / 22.04**](https://ubuntu.com/download/desktop).
- Environment: 
  [**Python>=3.9.0**](https://www.python.org/) 
  and [**PyTorch>=1.11.0**](https://pytorch.org/get-started/locally/) 
  with [**anaconda**](https://www.anaconda.com/products/distribution) (Recommend).
- Editor: `Jupyter Notebook`.
</details>

To getting started, you must install [**anaconda**](https://www.anaconda.com/products/distribution) 
before hand. Then open the `terminal` and get started:

```shell
cd <to-wherever-you-want-to-store-the-homework-files>

# Create a new environment named `mlhomework`
conda create --name mlhomework python=3.9

# Activate the environment (you must activate the conda environment everytime you 
# start the terminal
conda activate mlhomework

# Install Jupyter Notebook and clone the `homework` repo. 
# You only need to call this command once. If you have already install it, just skip this step
conda install git jupyter
git clone https://github.com/phlong3105/mlhomework

# Finally, run Jupyter Notebook and open the `homework.ipynb` file in your web browser:
cd mlhomework
jupyter-notebook
```
