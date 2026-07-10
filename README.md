# Software Engineering for Data Scientists: Data Science Pipelines

This repository contains the project associated with "Data Science Pipelines" Udacity course.
It's a fork of Udacity's [Starter Kit](https://github.com/udacity/dsnd-pipelines-project).

This GitHub.com project is located at [cariad-robert-abel/udacity-dsnd-pipelines-project](https://github.com/cariad-robert-abel/udacity-dsnd-pipelines-project).

## Summary

The project consists of a single Jupyter notebook that showcases all the stages
of machine learning pipeline developer.
First, we load the dataset and split it into training and validation data.
Next, we perform exploratory data analysis to get familiar with the dataset.
Then, we define the pre-processing and model training pipeline to establish a
proper baseline for comparison.
Lastly, we fine-tune the pipeline hyper-parameters by performing a random search
over hyper-parameter space with three-fold cross-validation.

## Installation

From the top-level repository directory, install using `pip` and then download
the required pre-trained NLP pipeline for spaCy:

    pip install .
    python -m spacy download en_core_web_sm

## Notebook

Run the Jupyter notebook `project.ipynb` once from the top to the bottom in your
favorite notebook environment, e.g. VS Code or Jupyter itself.

The trained model can be found in `model.joblib` after a complete run.

## License

Original files Copyright 2012–2020 Udacity, Inc.
My additions to documentation and code are [MIT](https://spdx.org/licenses/MIT).
See [LICENSE-Udacity](LICENSE-Udacity) resp. [LICENSE](LICENSE).
