# Transfer Learning for Image Classification

This repository contains code for transfer learning on image malaria classification. All three tasks use VGG19 as the base model for transfer learning. The code is implemented in Python and uses TensorFlow Core for training.

## Files

The repository contains the following files:

- `malaria.py`: Python script for training the VGG19 model on a malaria image dataset.
- `malaria_core.ipynb`: Jupyter notebook containing code for training and evaluating the malaria classification model.

## Usage
To install the necessary libraries.
```shell
python -m pip install -r requirements.txt
```
To use this code, you will need to have TensorFlow and tensorflow-dataset installed. You can then run the Python scripts for training the models or open the Jupyter notebooks for a more interactive experience.

```shell
python malaria.py
```
## Acknowledgements

The malaria, bunny  and Stanford Online Products datasets were obtained from [tensorflow offical website](https://www.tensorflow.org/datasets/catalog/).

## If you want train with GPU see my [instruction](https://github.com/Wolfman1219/Nvidia-CUDA-Tensorflow-installation)
