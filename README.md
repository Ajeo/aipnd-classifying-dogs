# classifying-dogs

This is the my classification dogs Lab from my ["Artificial Intelligence With Python" Nano Degree](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089).

#### Principle Objectives

1. Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.
2. Correctly classify the breed of dog, for the images that are of dogs.
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve the objectives _1_ and _2_.
4. Consider the time resources required to best achieve objectives _1_ and _2_, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

#### Dependencies

1. Install [Python 3.6](https://www.python.org/downloads/)
2. Install [Pipenv](https://pipenv.readthedocs.io/en/latest/)

#### Development

1. Clone this project
2. Run `pipenv shell`
3. Run `pipenv install`
4. Edit `classifier.py` or `check_images.py`

#### How To Use

Give execution permission to `run_models_batch.sh` with this command:

```
sudo chmod +x run_models_batch.sh
```

To run that script you need to run './run_models_batch.sh' in your terminal.

This will generate 3 files with the performance detail for each CNN model architectures:

* AlexNet -> alexnet.txt
* ResNet -> resnet.txt
* VGG -> vgg.txt

#### Results

![Screenshot](https://raw.githubusercontent.com/Ajeo/classifying-dogs/master/screenshots/results. png)

VGG has the best performance
