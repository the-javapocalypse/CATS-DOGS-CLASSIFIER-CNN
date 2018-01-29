# CATS-DOGS-CLASSIFIER-CNN
Cats &amp; Dogs Classifier using Conventional Neural Network in Keras. You can get the dataset from [here](https://www.kaggle.com/c/dogs-vs-cats/data). 

## Getting Started

Following should be the directory structure. I've uploaded few images in the dataset folder so that you can understand more better the structure and file naming scheme.

```
project   
│
└───dataset
│   │
│   └───single_prediction
│   │   │   cat_or_dog1.jpg
│   │   │   cat_or_dog2.jpg
│   │
│   │
│   └───test_set
│   │   │
│   │   └───cats
│   │   │   cat.1.jpg
│   │   │   cat.2.jpg
│   │   │   ...
│   │   │
│   │   └───dogs
│   │       dog.1.jpg
│   │       dog.2.jpg
│   │       ...
│   │  
│   └───training_set
│       │
│       └───cats
│       │   cat.1.jpg
│       │   cat.2.jpg
│       │   ...
│       │
│       └───dogs
│           dog.1.jpg
│           dog.2.jpg
│           ...
│     
└───CATS_DOGS_CLASSIFIER.ipynb
```

## Built With

* Python 3.6
* Keras 2.1.3
* Numpy
* Jupyter Notebook

### Dependencies

You'll need (__Keras__)[https://keras.io/] installed to run the script. It can be installed using pip
```
pip install keras
```
We will also need numpy. It can also be installed using pip
```
pip install numpy
```

### Installation

Download or Clone the repo and download the dataset from [here](https://www.kaggle.com/c/dogs-vs-cats/data) and store it in the dataset folder using the structure showed above. After that, run either python script or the jupyter notebook. This CNN is trained using CPU only. If you are using GPU, feel free to add more layers or increase number of neurons.

### Usage

Once the model is trained, you can use any image of dog or cat stored in __single_prediction__ folder to predict either it is a dog or cat in the image.


## Contributing

1. Fork it
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## Authors

Muhammad Ali Zia

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/the-javapocalypse/CATS-DOGS-CLASSIFIER-CNN/blob/master/LICENSE) file for details
