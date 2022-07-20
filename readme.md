# Learn-Machine-Learn

[![Contributors](https://img.shields.io/github/contributors/dsckgec/learn-machine-learn.svg)](https://github.com/dsckgec/learn-machine-learn/graphs/contributors) [![Forks](https://img.shields.io/github/forks/dsckgec/learn-machine-learn.svg)](https://github.com/dsckgec/learn-machine-learn/network/members) [![Issues](https://img.shields.io/github/issues/dsckgec/learn-machine-learn.svg)](https://github.com/dsckgec/learn-machine-learn/issues) [![Pull Request](https://img.shields.io/github/issues-pr-closed-raw/dsckgec/learn-machine-learn)](https://github.com/dsckgec/learn-machine-learn/pulls)


A one-stop repository for new-comers in Machine Learning and A.I.

## Contents

1. [Description](#description)
1. [Project structure](#project-structure)
1. [Project roadmap](#project-roadmap)
1. [Getting started](#getting-started)
1. [Preview Notebooks](#preview-notebooks)
1. [Built with](#built-with)
1. [Contributing](#contributing)
1. [Authors](#authors)
1. [License](#license)
1. [Acknowledgments](#acknowledgments)

## Description

### What are the projects?
This repository has two projects -
  * Classification based project on Cancer prediction `Cancer_prediction.ipynb`
  * Regression based project on Stock price prediction `L&T_Stock_Price_prediction.ipynb`

### How can this project help?
 * **Cancer Prediction**
    > Machine learning is not new to cancer research. Artificial neural networks (ANNs) and decision trees (DTs) have been used in cancer detection and diagnosis for nearly 20 years.The fundamental goals of cancer prediction and prognosis are distinct from the goals of cancer detection and diagnosis.
 * **Stock price Prediction**
    > Stock market prediction aims to determine the future movement of the stock value of a financial exchange. The accurate prediction of share price movement will lead to more profit investors can make.
### The idea
 * **Cancer Prediction**
    > The idea is to predict whether a cell is cancerous or non-cancerous based on different features of cell using different Machine learning algorithms or Deep learning techniques
 * **Stock Prediction**
    > The idea is to predict the future stock pricing based on different dependencies of a stock using different Machine learning algorithms or Deep learning techniques 
## Project structure
```
.
├── Classification
│   ├── Cancer_prediction.ipynb                   Jupyter notebook for Cancer prediction
│   ├── Datasets                                  Dataset for Cancer prediction
│   │   ├── cancer_data.csv
│   │   └── dataset.txt
│   └── classification.txt                        Basic information about Classification
├── Regression
│   ├── Datasets                                  Dataset for L&T stock price prediction
│   │   ├── LT.csv
│   │   └── dataset.txt
│   ├── L&T_Stock_Price_prediction.ipynb          Jupyter notebook for Stock price prediction
│   └── regression.txt                            Basic information about Regression
├── LICENSE
├── code_of_conduct.md
├── contributing.md
└── readme.md
```
## Project roadmap

The project currently does the following things-

  * Data cleaning
  * Data preprocessing
  * Already implemented a very few machine learning algorithms or deep learning techniques
  
Following things can be implemented -

  * Data augmentation or manipulation
  * Better data visualization
  * Implementation of different Machine learning algorithms or deep learning techniques to achieve better prediction results
 
## Getting started


### Prerequisites
- Very basic understanding of git and github:

    1.  What are repositories (local - remote - upstream), issues, pull requests
    2.   How to clone a repository, how to fork a repository, how to set upstreams
    3.   Adding, committing, pulling, pushing changes to remote repositories

- For EDA and Visualisation
 
    1. Basic syntax and working of ```python```.(This is a must)
    2. Basic knowledge of ```pandas``` library. [Reading this blog might help.](https://www.dataquest.io/blog/pandas-python-tutorial/)
    3. Basic knowledge of ```matplotlib``` library. [Reading this blog might help.](https://blog.quantinsti.com/python-matplotlib-tutorial/)
    4. Basic knowledge of ```seaborn``` library. [Reading this blog might help.](https://www.mygreatlearning.com/blog/seaborn-tutorial/)
    5. Basic knowledge of ```scikit learn``` library. [Reading this blog might help.](https://www.dataquest.io/blog/sci-kit-learn-tutorial/)
    6. Basic knowledge of ```tensorflow``` library. [Reading this blog might help.](https://www.tensorflow.org/overview)

  However the code is well explained, so anyone knowing the basics of Python can get a idea of what's happenning and contribute to this.

### Installing

A step by step series of examples that tell you how to get a development env running.


There are two ways of running the code.
  1. Running the code on web browser.(Google Colab) [Recommended]
      - Head on to [Google colab](https://colab.research.google.com/)
      - Then click on ```Upload Notebook``` Tab.
      - Upload the notebook that you got from this repo.
        ![Colab-1](https://res.cloudinary.com/codehackerone/image/upload/v1618463907/ML/colab-2_c14swf.png)
      - Connect with the runtime.
        ![Colab-2](https://res.cloudinary.com/codehackerone/image/upload/v1618464955/ML/Colab-3_da822c.png)
      - Upload your dataset.
        ![Colab-3](https://res.cloudinary.com/codehackerone/image/upload/v1618464958/ML/Colab-04_sxfyjx.png)
      - Then Click on ```Run All```.
        ![Colab-4](https://res.cloudinary.com/codehackerone/image/upload/v1618465413/ML/colab-5_i92bzp.png)
      - Start Editing.

  2. You can also run the code locally in your computer by installing Anaconda.
      - Install Anaconda. [Follow these steps to install Anaconda on your computer](https://www.edureka.co/blog/python-anaconda-tutorial/#:~:text=on%20our%20systems.-,Installation%20And%20Setup,the%20instructions%20in%20the%20setup.)
      - Install jupyter notebook using ```conda```. [Follow these steps to install jupyter notebook.](https://test-jupyter.readthedocs.io/en/latest/install.html)
      - Make sure to install ```pandas```,```matplotlib```,```seaborn``` and ```scikit-learn``` to run the notebook.
      - Start Editing.
## Preview Notebooks
  `Notebook will be opened in Google Colab`
- [Head to here for the `Cancer_prediction` preview](https://colab.research.google.com/drive/1_oM3NxjoNlj-yyrvXyu1FtG4-6iv1mEZ?usp=sharing)
- [Head to here for the `L&T_Stock_Price_prediction` preview](https://colab.research.google.com/drive/1HYEpZ8_t4E-zKokbEyi_egvABJaWeL_G?usp=sharing)

## Built with

- [Google Colab](https://colab.research.google.com)

## Contributing

Please read [contributing.md](contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

<a href="https://github.com/DSCKGEC/learn-machine-learn/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DSCKGEC/learn-machine-learn" />
</a>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Anurag Chakraborty](https://github.com/anuragc2001)
- [Krishnendu Dakshi](https://github.com/KrishnenduDakshi2002)
