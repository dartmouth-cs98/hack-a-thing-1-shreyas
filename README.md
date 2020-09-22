# Hack A Thing 1

**Author:** Shreyas Agnihotri

## Background

I am considering working on a Machine Learning related project for the COSC 98 culminating project. My background in Machine Learning, though, has been almost purely theoretical and I wanted to build a practical understanding of the common frameworks and tools. These include Jupyter Notebooks and Python themselves, as well as frameworks such as:
* scipy
* numpy
* matplotlib
* pandas
* sklearn
* SpeechRecognition
* TensorFlow Federated

The goal was to actually load and wrangle with data so that I can start off running with more advanced applications.

## What I built

I produced a Jupyter Notebook with a few different sample ML and data science applications based on multiple tutorials. The first is a classic ML classification of the iris flowers dataset. The next is a use case for speech processing in Python, with an interactive game that takes user input from the microphone.

## What I learned

Popular frameworks such as sklearn make it extremely easy to build complex models to fit data, provided the data is well-labeled and segmented. This makes me optimistic about my ability to build a more complicated ML application and also underscroes the importance of picking proper data sets through Exploratory Data Analysis and cleaning. Speech recognition is similarly easy to implement, but requires thoughtful naalysis of the data to handle noise and extraneous variables in the audio in order to ensure operability with popular NLP frameworks.

## What didn’t work

Python was surprisingly difficult to set up for machine learning, largely because I had last used it extensively when I took CS1 several years ago. My version of python was stuck on the deprecated `2.7` and in the process of upgrading to `3.x` I was unable to migrate some of my existing packages and Jupyter notebooks, causing `module not found` errors. After a lot of Stack Overflow, I was able to sort this out and continue with the tutorials using the latest versions of all packages.

## Resources

* [Basic ML & Data Analysis Tutorial](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)
* [Python for Speech Recognition](https://realpython.com/python-speech-recognition/)
* [Federated Learning for Image Classification](https://www.tensorflow.org/federated/tutorials/federated_learning_for_image_classification)
* [Introduction to Federated Learning](https://federated.withgoogle.com/)

