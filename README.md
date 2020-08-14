# Embeddings Analysis for Job Recommendations
Tutorial how to leverage embeddings for job recommendations  by Ellen Schwartau and Doreen Sacker.

In order to prepare for the workshop, you need:
- [Install requirements](#install-requirements)
- [Download dataset](#Download-data)


## Install requirements 
#### Requirements
- pyenv >= 1.2.13
- python >= 3.7.0


#### Clone the workshop repository

```
git clone 
cd recommendations-with-embeddings
```
#### Setup your virtual environment

With *pyenv*
```
pyenv local 3.7.4
pyenv virtualenv 3.7.4 embeddings-env
pyenv activate embeddings-env
pip install -r requirements.txt
```

#### Open Jupyter Lab

Run the following command in your shell: 
```
jupyter notebook
```


## Download data

`US jobs on Monster.com` is a public dataset made available through the Kaggle platform.
You can download it [here](hhttps://www.kaggle.com/PromptCloudHQ/us-jobs-on-monstercom/data#). You will need to create
a free Kaggle account in order to do so.
Once the downloading is completed, you can place the file in the folder `data` (the code we will use assumes that the data files
are located there, you will need to adjust the code accordingly if you don't). 