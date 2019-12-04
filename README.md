This is a tutorial presented during a [workshop](https://appliedmldays.org/workshops/pytorch-tutorial) at the Applied Machine Learning Days 2020.

## Google Colab
We will use [Google Colaboratory](https://colab.research.google.com)

### Using Google Colab
The Google Colab notebooks are available under:
- [1-Basics.ipynb](https://colab.research.google.com/github/ahug/amld-pytorch-workshop/blob/master/1-Basics.ipynb)
- [2-Autograd.ipynb](https://colab.research.google.com/github/ahug/amld-pytorch-workshop/blob/master/2-Autograd.ipynb)
- [3-Optimization.ipynb](https://colab.research.google.com/github/ahug/amld-pytorch-workshop/blob/master/3-Optimization.ipynb)
- [4-Modules.ipynb](https://colab.research.google.com/github/ahug/amld-pytorch-workshop/blob/master/4-Modules.ipynb)
- [5-CNN-LSTM.ipynb](https://colab.research.google.com/github/ahug/amld-pytorch-workshop/blob/master/5-CNN-LSTM.ipynb)
- [6-Transfer-Learning.ipynb](https://colab.research.google.com/github/ahug/amld-pytorch-workshop/blob/master/6-Transfer-Learning.ipynb)


In order to use Google Colab, you have to login using your Google account:
![Google Colab Login](figures/colab-connect.png)

### Changing the runtime type
You can add GPU support on Google Colab by changing the runtime type as depicted below:

![Google Colab Runtime](figures/colab-runtime.png)
<br />

## Other installations

We _highly recommend_ to use **Google Colab**.  
However, it also possible to use **Binder** or to install it locally.

### Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/theevann/amld-pytorch-workshop/master) 
<br />

### Installing locally using conda
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
git clone https://github.com/ahug/amld-pytorch-workshop.git
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

## Additionnal resources:
Check out these others tutorials and courses:
- Official tutorials : https://pytorch.org/tutorials/
- PyTorch for DL (.py files): https://github.com/yunjey/pytorch-tutorial
- PyTorch for DL (notebooks): https://github.com/yandexdataschool/Practical_DL
- PyTorch for Numpy users : https://github.com/wkentaro/pytorch-for-numpy-users
