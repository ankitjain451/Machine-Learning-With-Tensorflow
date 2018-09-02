# Generating TV Scripts using LSTMs
This repo consists of an implementation of TV Script Generation code.

### Dataset
Simpson's TV script dataset was used for this. The full dataset can be downloaded from [Kaggle] (https://www.kaggle.com/wcukierski/the-simpsons-by-the-data#simpsons_script_lines.csv)
### Installations
* This code is checked on using native Python 3 with anaconda
* Create a conda virtual environment and install relevant packages using requirements.txt file
```
pip install requirements.txt
```
### Python Code Run Instructions
To run the code just execute
```
python main.py
```
On CPU the code might take few hours to run. However, if you use GPUs it should be much faster

### Code Details
Code is pretty self explanatory. There are mainly four files in implementation:
* main.py  -- It contains three parts:
    * main function:  To call the relevant functions
    * train:   trains the model
* parameters.py -- Contains all the parameter declarations
* Model.py -- Contains the Model Class.
* utils.py -- Helper functions.

Note that the model was not tuned for best hyperparameters. Feel free to play around.
