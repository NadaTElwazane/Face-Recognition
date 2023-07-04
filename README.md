# Face Recognition

## Table of Contents
- [Description](#description)
- [Implementation](#implementation)
- [Results](#results)
- [Notebook](#notebook)
- [Collaborators](#collaborators)

## Description
This project is a face recognition system that uses [AT&T Face database](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces) to train a model that can recognize faces. The model is trained using KNN algorithm. It is also a practical introduction to the use of PCA and LDA for dimensionality reduction.
## Implementation
We implemented PCA and LDA from scratch using numpy, as well as KNN algorithm. 

Additionally, we implemented a binary classification model for identifying faces vs non-faces.

As a bonus, we also implemented KPCA, KLDA as well as DLDA. 

## Results
The model was able to recognize faces with an accuracy of 0.958 with PCA and 0.95 with LDA.
For the LDA and PCA variations we got the following results:
| Method | Accuracy |
| ------ | ------ |
| PCA | 0.958 |
| LDA | 0.95 |
| KPCA | 0.975 |
| KLDA | 1.0 |
| DLDA | 0.94 |

As for the binary classification model, we got an accuracy of 0.9925 with LDA and 0.995 with PCA.

## Notebook
The notebook can be found [here](Face-Recognition.ipynb).

## Collaborators
- [Manar Amgad](https://github.com/manaramgadd)
- Ahmed Dusuki