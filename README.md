# KNN_cars_classifier
# Car Evaluation using K-Nearest Neighbors (KNN) Classifier

This project implements a **K-Nearest Neighbors (KNN)** classifier to evaluate car conditions using the `car.data` dataset. The dataset contains attributes related to car features like buying price, maintenance cost, safety, and more. The KNN algorithm is used to predict the car's evaluation category (unacceptable, acceptable, good, or very good).

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

The project uses the K-Nearest Neighbors (KNN) algorithm to classify car evaluations into one of the following categories:
- **unacc**: Unacceptable
- **acc**: Acceptable
- **good**: Good
- **vgood**: Very Good

The data is preprocessed using `LabelEncoder` to transform categorical features into numerical format. The KNN model is trained and tested using a 70-30 train-test split, and the model's performance is evaluated based on accuracy.

## Project Structure

```bash
.
├── car.data             # The dataset file
├── classsification_k_nearest_car_evaluation.py              # The main Python script that contains the KNN implementation
├── README.md            # This README file

