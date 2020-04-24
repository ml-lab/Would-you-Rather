# Would you Rather?

This repository contains the dataset for our paper - __Would you Rather? A New Benchmark for Learning Machine Alignment with Cultural Values and Social Preferences__

## Dataset

`data/train.csv`, `data/dev.csv` and `data/test.csv` are the training, development and test sets for predicting preferences, respectively. The format of them is as follows:

|Question|Option 1|Option 2|Relative|Filename|Votes|Option 1 Vote %|Option 2 Vote %|
|-|-|-|-|-|-|-|-|

`data/train_aug.csv`, `data/dev_aug.csv` and `data/test_aug.csv` are the training, development and test sets for predicting cultural preferences, respectively. The format of them is as follows:

|Question|Option 1|Option 2|Relative|Filename|Culture|Culture's Choice 1 Vote %|Culture's Option 2 Vote %|
|-|-|-|-|-|-|-|-|
