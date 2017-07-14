# ft-automl-tpot-example

This is a demo for the usage of Featuretools combined with automl and/or TPOT

We're going to import data and process the features by [Featuretools](http://docs.featuretools.com/index.html). The model(s) will be automatically build by two libraries:

- [auto-sklearn](https://github.com/automl/auto-sklearn/)
- [TPOT](https://rhiever.github.io/tpot/)

The focus of this repo is to show the usage of this libraries in combination with each other on demo data. The results of the modells won't be checked, discussed or tweaked in any way.

## Split up into multiple notebooks

In the first notebook the data will be prepared by Featuretools and stored in a local CSV-file.

After that the modelling notebooks will do some ML-magic to learn a model on the data.

Take care of the Python version of the notebooks! Featuretools (in version 0.1.5) needs Python 2, while the ML-libraries need/support Python 3.

## Demo data

The data used for this example is given in [Featuretools examples](http://docs.featuretools.com/examples/retail_data_demo.html).
