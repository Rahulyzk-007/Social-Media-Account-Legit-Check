# Social-Media-Account-Legit-Check

This repository contains an Artificial Neural Network (ANN) model designed to classify social media profiles as legitimate or fake. The model is trained on a dataset in CSV format with various features related to social media profiles.
Dataset

The dataset used for training and evaluation includes the following columns:

profile pic: Binary indicator of profile picture presence.
nums/length username: Numeric value or length of the username.
fullname: Full name of the profile.
words: Number of words in the full name.
nums/length fullname: Numeric value or length of the full name.
name==username: Binary indicator of whether the name matches the username.
description length: Length of the profile description.
external URL: Binary indicator of external URL presence.
private: Binary indicator of the profile being private.
#posts: Number of posts.
#followers: Number of followers.
#follows: Number of accounts followed.

The target variable is:

fake: Binary classification label indicating whether the profile is fake (1) or legitimate (0).
Model

The model is an Artificial Neural Network (ANN) implemented using Keras with TensorFlow backend. The ANN architecture consists of:

Input layer: Takes features from the dataset.
Hidden layers: Multiple fully connected layers with ReLU activation.
Output layer: Single neuron with sigmoid activation for binary classification.
