# wine_quality
In this project we will classify a wine in different quality classes, using its physicochemical properties. 

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
-->

<!-- PROJECT LOGO -->
<br />
<p align="center">

<h3 align="center">Wine quality classification for unbalanced data</h3>

***  <a href="https://github.com/loremendez/wine_quality">
  </a>
</p> ***


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#references">References</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

This dataset is highly unbalanced, for which the main goal will be to compare a Random Forest Classifier performance, when using data augmentation techniques (SMOTE).

### Built With

* [Anaconda 4.10.1](https://www.anaconda.com/)
* [Python 3.9](https://www.python.org/downloads/release/python-380/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

A running installation of Anaconda. If you haven't installed Anaconda yet, you can follow the next tutorial: <br>
[Anaconda Installation](https://docs.anaconda.com/anaconda/install/)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/loremendez/wine_quality.git
   ```
2. Install the environment <br>
    You can do it either by loading the [`YML`](https://github.com/loremendez/wine-quality/blob/main/conda_environment.yml) file
    ```sh
    conda env create -f conda_environment.yml
    ```
    or step by step
    1. Create and activate the environment
        ```sh
        conda create -n wine_env python=3.9
        conda activate wine_env
        ```
    2. Install the needed packages
        ```sh
        pip install --upgrade pip
        pip list  # show packages installed within the virtual environment

        pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
        pip install jupyterlab
        ```

<!-- USAGE EXAMPLES -->
## Usage
Open Jupyter-lab and open the notebook [`Random_Forest.ipynb`](https://github.com/loremendez/wine_quality/blob/main/Random_Forest.ipynb) to see the classifier's performance on the original dataset, or open the notebook [`Random_Forest_SMOTE.ipynb`](https://github.com/loremendez/wine_quality/blob/main/Random_Forest_SMOTE.ipynb) to see the classifier's performance on the augmented dataset.
```sh
jupyter-lab
```

<!-- References -->
## References
<a id="1">[1]</a>
Dataset by Cortez, Paulo (@LSIND) “Wine Quality Data Set”.
Last updated: 2020-04-27.
Link UCI Machine Learning Repository: [https://archive.ics.uci.edu/ml/datasets/wine+quality)
Link Kaggle: https://www.kaggle.com/datasets/yasserh/wine-quality-dataset


<!-- CONTACT -->
## Contact

Lorena Mendez - [LinkedIn](https://www.linkedin.com/in/lorena-mendezg/?originalSubdomain=de) - lorena.mendez@tum.de

Take a look into my [other](https://github.com/loremendez) projects!