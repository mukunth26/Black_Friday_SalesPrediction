# Black Friday Sales Prediction

This repository contains code for a sales prediction model on Black Friday data as a part of my internship at Codeclause. The goal of this project is to predict the purchase amount of customers based on various features such as gender, age, city category, etc.

## Table of Contents

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Label Encoding](#label-encoding)
- [Model Training](#model-training)
- [Results](#results)

## Introduction

The Black Friday Sales Prediction project aims to build a model that can predict the purchase amount of customers on Black Friday. The dataset contains various features like gender, age, city category, etc., which will be used as input to the predictive models.

## Data Preprocessing

In this section, the dataset is loaded, and initial data exploration and cleaning are performed. Irrelevant columns are dropped, and missing values in `Product_Category_2` and `Product_Category_3` are filled with their mean values.

## Label Encoding

Categorical features such as `Gender`, `Age`, `City_Category`, and `Stay_In_Current_City_Years` are encoded using label encoding. This step is necessary to convert categorical data into numerical format for training machine learning models.

## Model Training

In this section, four different regression models are trained on the preprocessed data:

1. Linear Regression
2. Decision Tree Regressor
3. XGBoost Regressor
4. Random Forest Regressor

The models are trained on a training set and evaluated on a separate test set.

## Results

The performance metrics of each model are displayed in this section. Metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE) are used to evaluate the models' predictive capabilities.
