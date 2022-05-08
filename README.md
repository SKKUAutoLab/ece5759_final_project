<div align="center">

ML Homework: YOLOv5 Object Detection
=============================
</div>


## <div align="center">Overview</div>

<details open>
<summary>Object detection</summary>

Object detection is the task of detecting instances of objects of a certain class 
within an image. Each detected objects are usually marked with a bounding boxes 
along with a confidence score and a class ID.

<img src="data/picture1.png" alt="drawing" style="height:300px;"/>
<br>

Here is a demo:

<img src="data/media1.gif" height="300" />

</details>


<details open>
<summary>YOLOv5</summary>

YOLOv5 🚀 is a family of object detection architectures and models pretrained 
on the COCO dataset, and represents <a href="https://ultralytics.com">Ultralytics</a>
open-source research into future vision AI methods, incorporating lessons learned 
and best practices evolved over thousands of hours of research and development.

<img src="data/picture2.png" alt="drawing" style="height:200px;"/>

</details>


<details open>
<summary>VisDrone</summary>

- Drones, or general UAVs, equipped with cameras have been fast deployed to a 
wide range of applications, including agricultural, aerial photography, fast 
delivery, and surveillance. 
- Automatic understanding of visual data collected from these platforms become 
highly demanding, which brings computer vision to drones more and more closely. 

<img src="data/picture3.jpg" alt="drawing" style="height:300px;"/>

</details>


## <div align="center">Tasks & Goals</div>

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
- At the end, uou must make a simple Word file reporting the following information: 
  - Model variance,
  - GPU device,
  - Training time, 
  - Epochs
  - Test accuracy (mAP@50). 
  - Example:

| Model   |            GPU            | Training time | Epochs | mAP@50 |
|---------|:-------------------------:|--------------:|-------:|-------:|
| YOLOv5s | NVIDIA TITAN Xp, 12193MiB |   0.488 hours |     20 |  0.199 |


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

# Activate the environment (you must activate the conda environment everytime you start the terminal
conda activate mlhomework

# Install Jupyter Notebook and clone the `homework` repo. 
# You only need to call this command once. If you have already install it, just skip this step
conda install git jupyter
git clone https://github.com/phlong3105/mlhomework
cd mlhomework
pip install -qr requirements.txt

# Finally, run Jupyter Notebook and open the `homework.ipynb` file in your web browser:
jupyter-notebook
```
