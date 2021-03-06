# elastic_tensor_ML
## Machine learning models for predicting the bulk modulus of materials

This repository is a collection of notebooks exploring various machine learning (ML) models for predicting the bulk modulus (K) of materials. The dataset comes from the [Materials Project](https://materialsproject.org), where the elastic tensors were calculated from first principles. The goal of the project is to develop an updated ML model because the previous model was trained on ~ 1500 data points, whereas now we have ~ 8500 data points. Additionally, the previous model was difficult to retrain so having a reproducible pipeline is important moving forward.

## To-do

- Find a more statistically robust method for hyperparameter tuning and comparison of different ML models, possibly nested cross validation [[arXiv](https://arxiv.org/pdf/1811.12808.pdf)] 
- Try batch normalization or dropout with the neural networks

## References

- [Matminer](https://github.com/hackingmaterials/matminer_examples)

- [Keras](https://github.com/keras-team/keras/tree/master/examples)

- [TensorFlow](https://github.com/tensorflow/docs/tree/master/site/en/tutorials/eager)

## Dependencies

All dependencies can be pip installed, but be aware that standard tensorflow is not yet compatible with python 3.7 (11/7/18)

- Python (3.6)
- Pymatgen
- Matminer
- scikit-learn
- Pandas
- NumPy
- Tensorflow
- Jupyter