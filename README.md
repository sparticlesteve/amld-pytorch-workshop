This is a tutorial presented during a [workshop](https://appliedmldays.org/workshops/pytorch-tutorial) at the Applied Machine Learning Days 2020.

We will use jupyter notebooks throughout this tutorial.

We recommend to run them online on **[Google Colaboratory](https://colab.research.google.com)**.  
That way, you don't have to install anything and you have access to a gpu for free !  
As an alternative, you can also use **[Binder](https://mybinder.org)** or run the notebooks locally.

- ### [Notebooks on Google Colab](#google-colab) _(recommended)_
- ### [Notebooks on Binder](#binder)  
- ### [Installing locally](#installing-locally-using-conda)

## Google Colab

The Google Colab notebooks are available under:
1. [Basics](https://colab.research.google.com/github/theevann/amld-pytorch-workshop/blob/master/1-Basics.ipynb)
1. [Autograd](https://colab.research.google.com/github/theevann/amld-pytorch-workshop/blob/master/2-Autograd.ipynb)
1. [Optimization](https://colab.research.google.com/github/theevann/amld-pytorch-workshop/blob/master/3-Optimization.ipynb)
1. [Modules](https://colab.research.google.com/github/theevann/amld-pytorch-workshop/blob/master/4-Modules.ipynb)
1. [CNN](https://colab.research.google.com/github/theevann/amld-pytorch-workshop/blob/master/5-CNN.ipynb)
1. [Transfer Learning](https://colab.research.google.com/github/theevann/amld-pytorch-workshop/blob/master/6-Transfer-Learning.ipynb)

### Using Google Colab

In order to use Google Colab, you have to login using your Google account:
![Google Colab Login](figures/colab-connect.png)

### Changing the runtime type
You can add GPU support on Google Colab by changing the runtime type as depicted below:

![Google Colab Runtime](figures/colab-runtime.png)
<br />


## Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/theevann/amld-pytorch-workshop/master) 
<br />


## Installing locally using conda
If you want to run the notebooks locally, you can use `conda`. The following instructions
should work on Linux/Mac OS, Windows might require slight adaptations.

#### Step 1: Install conda
If you have not installed it yet, you can download it from [Anaconda (Python 3.6 version)](https://www.anaconda.com/download/#linux).

Verify that it is installed by running
```bash
conda -V
```

Make sure your conda installation is up-to-date:
```bash
conda update conda
```

#### Step 2: Download repository and install environment
Now clone the repository:
```bash
git clone https://github.com/theevann/amld-pytorch-workshop.git
cd amld-pytorch-workshop
```

The available `conda` environments can be listed using
```bash
conda env list
```

Let's now create a new environment called _'amld-pytorch'_.
```bash
conda env create -f environments.yml
```


#### Step 3: Activate/Deactivate the environment
After the environment has been created, you can **activate** it by
```bash
source activate amld-pytorch
```

Now start the Jupyter notebook by running
```bash
jupyter notebook
```

The environment can similarly **deactivated** by
```bash
source deactivate
```

## Additionnal resources
Check out these others tutorials and courses:
- Official tutorials: https://pytorch.org/tutorials/
- Step-by-step tutorial: https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e
- PyTorch for DL (.py files): https://github.com/yunjey/pytorch-tutorial
- PyTorch for DL (notebooks): https://github.com/yandexdataschool/Practical_DL

