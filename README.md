# challenge-classification

## What

On this repository, we tried to do some classification model and try to understand how it works. We use [this](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset) dataset.

## Why

Our main objectif in this exercise was to learn the difference between models, to better understand classification and to be able to read a dataset. We did this during our BeCode training.

## When

During BeCode training. The exercise took around 3 days.

## How

We did everything on a jupyter notebook in Vs Code. We use python 3 and we use SKLearn's libraries to be able to train our data. First thing that we've done was cleaning. Before starting to drop somes columns or create one we try to understand what we had on our dataset so for this purpose we use profiling report. You can install it with `pip install pandas-profiling[notebook]` and if you want further information you can visit [this](https://github.com/pandas-profiling/pandas-profiling) github page. This operation take a lot of ressources and time so as we didn't want to loose too much time, we created a html with `profile.to_file(output_file= 'output.html')` code if you download this repository you will have the html in data.
After understanding the data, we decided to add new columns like mean_pay, or rate, etc... After that, we created a list of parameters with a lot of possibility by parameters. We choose to do that to choose the right parameters for each model to have the best accuracy by model type. For that we use Grid Search CV.

Finaly we got ~83% of accuracy with random forest.

## Who 

[Ebubekir Kocadag](https://github.com/EbubekirKocadag), junior AI developer

## Pending things to do

We still can try with other models then what we tried and we can drop or create new columns to our dataset. We can alose do the resampling and also the deployment.
