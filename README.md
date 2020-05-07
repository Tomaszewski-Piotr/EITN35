# EITN35 - ML Object Detector

# This is a project for training a data object detector

Training and testing an algorithm which will be used to detect persons and dogs in a tunnel.

## Prerequisites
- Anaconda

## Installation in an Anaconda Environment

Create an Anaconda environment with the packages listed in requirements.txt

```bash
conda create --name <NAME> --file requirements.txt
```

##Setup
Put frames in two different folders, one for the test set and one for the training set. Change train_dir and test_dir to the desired path where your test and train set is located.

## Usage
baseline.py is the main file which trains a model from scratch given frames of a tunnel with objects: person, bike, dog and empty tunnel

Run the script with:


```bash
baseline.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
