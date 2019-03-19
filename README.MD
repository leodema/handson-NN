# Hands-on Neural Network

A collections of resources to understand Neural Network.

## Getting Started

### Prerequisites

Install conda https://docs.anaconda.com/anaconda/install/ for python 3.6.

Make sure you have added theforge channel:

```
conda config --append channels conda-forge
```

Then in the projec directory run:

```
conda create --name dl_env python=3.6 --file enviroment.yaml
```

This will create our conda enviroment.

If conda does not find all the packages please add :

```
conda config --env --add channels conda-forge
```

### Slides

Slides day 1: https://drive.google.com/drive/folders/1d2KK9VzWeueTnDu3x6mddWFZFF8JQrvG?usp=sharing
Slides day 2: https://drive.google.com/drive/u/1/folders/12WLWF5XDUJok5bvQqAXt2ic5e-0wTe-W

### Run
To activate the enviroment you can run in a shell

```
conda activate dl_env
```

To run tensorboard simply type:

```
tensorboard --logdir logs/1
```

## Contributing

Feel free to contribute with a pull request.
