# JupyterQ Notebooks

Repo for all jupyterQ notebooks coded in embedded py. This allows intergration of python and kdb q for data science research.

## Getting Started

Simply for viewing and tracking.

### Prerequisites

These are required for the application to run

```
kdb+/q
unix environment
jupyter-notebook
embedpy
jupyterQ
machineLearning libraries (tensorflow,keras,sklearn,numpy,pandas)
visualisation libraries (seaborn,matplotlib)

```

### Overview of scripts

TODO

```
scripts
|_______Craftbeer(Simple exploration of craft beer dataset in kaggle and attempt to use gmaps for geolocation visualisation along with geocode scrapping api)
|_______notMNIST_1(embedpy implementation of notMNIST dataset, upstream to downstream)
|_______notMNIST_2(Neural network implementation of notMNIST dataset)
|_______oneHotEncoding(Preprocessing example for kdb dataset, alternative to python)
|_______timeSeriesWithProphet(Utilisation of kaggle nyse dataset, no preprocessing, simple visualiation and application of prophet api for timeseries forecasting)
|_______word2Vec(Utilisation of gensim's word2vec library for sms dataset, exploration of tough to use data set in natural language processing)
|_______SummaryNotesForQ(Notes taken down while reading up qTips by Nick Psaris)
```

## Built With

* [jupyter-notebook](https://github.com/jupyter/notebook) - Ide+framework for research based programming
* [jupyterQ](https://github.com/KxSystems/jupyterq) - q functionality in jupyter with embedded python
* [kdb+](https://ondemand.kx.com/) - columnar database for historical data
* [embedPy](https://github.com/KxSystems/embedPy) - embed of python kernel to allow q to pass k objects into python libraries


## Authors

* **Guan Yu** - *Initial Contribution* - [glimKx](https://github.com/glimkx)
