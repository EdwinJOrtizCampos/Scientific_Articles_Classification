# Scientific Articles Classification
This repository contains the code for a scientific journal recommender system to submit publications.

## Description

The goal of this project is to build a model capable of recommending the most suitable scientific journal to submit a research article.

Several machine learning models (Random Forest, Naive Bayes, SVM and LSTM neural networks) were trained and evaluated using a dataset with 5000 scientific articles from 4 different journals. 

The models were trained to classify articles into one of the following categories:

- Applied Ergonomics (AE)
- Journal of Visual Communication and Image Representation (JVCIR)  
- Pattern Recognition (PR)
- Robotics and Autonomous Systems (RAS)

## Usage 

The source code is contained in the `main.ipynb` file. To use it:

1. Clone this repository
2. Install the dependencies
3. Open the `main.ipynb` file in Jupyter Notebook
4. Execute the notebook as desired

To use the trained models, you can call the provided functions in the notebook by passing the title, abstract and keywords of the article to classify. However, no inference code is provided.

## Results

The SVM model achieved the best overall accuracy (83%), with a good ability to distinguish between the 4 categories. However, no model was able to perfectly distinguish between all classes, requiring more training data.

## Credits

This project was developed by Edwin Ortiz Campos as part of the Master's Degree in Intelligent Systems and Numerical Applications at the University of Las Palmas de Gran Canaria.

The dataset was obtained from the ScienceDirect platform.