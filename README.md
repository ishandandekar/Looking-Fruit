# Looking-Fruit

<p align="center">
    <img width=300 height=170 src="assets/meme.jpeg">
</p>

:wave: Hello and welcome to the **:apple: Looking-Fruit** code repository. This is a short and simple computer vision project. In this project, I replicate and try to improve the models used to classify images of fruits. You can see the research paper [here](https://www.researchgate.net/publication/321475443_Fruit_recognition_from_images_using_deep_learning). The original code repository can be found [here](https://github.com/Horea94/Fruit-Images-Dataset). This is my first independant paper replication project :smile:.

<details>
  <summary markdown="span"><strong>See the abstract of the paper</strong></summary>
    In this paper we introduce a new, high-quality, dataset of images
containing fruits. We also present the results of some numerical experiment for training a neural network to detect fruits. We discuss the
reason why we chose to use fruits in this project by proposing a few
applications that could use such classifier.
</details>

## Introduction

Computer Vision domain has always been my curiosity. I thought paper replication was a great start to then replicate state-of-the-art models like ResNets.
The **objective** of the research paper was to classify images various fruits and vegetables correctly. The researchers made a total of 10 models based and documented there results. The main of this project is to beat and/or achieve the highest score on the test set when compared to their best model.

## Data

The original data for the paper was published and created by the researchers themselves. The dataset contains a total of around 90,000 images of **131** fruits and vegetables. The data is then split into two sets: training and testing sets. This test set contains almost 25% of the total dataset.

For my ease-of-use I uploaded the dataset available on Github to Kaggle, and used this for the project. Check out the dataset [here](https://www.kaggle.com/datasets/ishandandekar/fruitimagedataset) and do try making models yourself!

> :bulb: Check out the original dataset: [Github](https://github.com/Horea94/Fruit-Images-Dataset) [Kaggle](https://www.kaggle.com/datasets/moltean/fruits)

## Approach and Models

## Contribution

I appreciate reviews and criticism. If you find any errors (even a typo!) and/or want to improve something in the repository, and/or want to help document the project, feel free to create a pull request! :smile:

## Contents of the repository

- _assets_ : various media materials which were helpful for the project.
- _.gitignore_ : this file was used to make `git` not track certain private files.
- _helper_functions.py_ : python script containing various utility functions which were used during the modelling experiments.
- _Looking_Fruit_nbk_ : jupyter/colab notebook used for this project. The notebook also describes the models and approach.
- _README.md_ : documentation of the project.

#### TODO:

- [ ] Make notebook
- [ ] Beautify notebook
- [ ] Add 'Open in colab' button
- [x] Add dataset to Kaggle
- [x] Beautify Kaggle dataset (desc etc.)
- [ ] Update README
