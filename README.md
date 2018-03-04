# Predictive Maintenance NASA

This project aims to predict NASA's engines failure based on know failures and parameters.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

```
keras library
numpy library
pandas library
```

### Installing

In order to install these libraries, you need to use pip tool.

```
pip install [name_of_the_library]
```

## Running the tests

The process is separated in three different steps.

The first step (i.e. preprocess.ipynb) preprocesses the data. It has to be ran each time a new data set in introduced (train or test).

The second step (i.e. NNtrain.ipynb) builds the neural network for prediction. It has to be ran each time a new train set is introduced. The first step must have been performed in order for the neural network to take into account this new train set.

The third step (i.e. main.ipynb) predicts the RUL values for the test set. It has to be ran in order to predict the results.

## Built With

* [Keras](https://keras.io/) - The neural network library
* [Pandas](https://pandas.pydata.org/) - Easy to use dataframes
* [Numpy](http://www.numpy.org/) - Nice tabs

## Authors

* **Paul Vardon** - [Vardoom](https://github.com/Vardoom)

## References

- [1] Deep Learning for Predictive Maintenance https://github.com/Azure/lstms_for_predictive_maintenance/blob/master/Deep%20Learning%20Basics%20for%20Predictive%20Maintenance.ipynb
