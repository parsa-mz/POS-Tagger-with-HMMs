
# NLP 201 - Hidden Markov Models



## Introduction

The goal of this project is to train a hidden markov model to find the sequence of tags which maximizes the probability P (t|w).


## Requirements

The project uses [Python 3.10](https://www.python.org/downloads) which has some linting defaults which may cause import
errors if using python < 3.10.

The requirements can be installed using the following command:

```bash
    # create a virtual environment
    python3 -m venv venv
    # windows
    venv\Scripts\activate
    # linux / mac
    source venv/bin/activate
    
    # install requirements
    pip install -r requirements.txt
```


## Running the code

The code has been written in jupyter notebook so that each part can be run individually and test different senarios and variables along the way. The notebook can also be imported into colab as well if you prefer working in the cloud GPU.



## Project Structure

The project is structured as follows:

```bash
    .
    ├── data
    │   └── containg data folders (00, 01, ...)
    ├── README.md
    ├── requirements.txt
    ├── Report.pdf
    └── notebook.ipynb
```

The `data` folder contains the data files for the project. The `notebook` is a jupyter notebook which contains the code
for the project. 


## Authors

Parsa Mazaheri, December 2022