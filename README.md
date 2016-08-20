# SVHN_Capstone_Project
Street View House Number Detection Using Deep Learning

# Street View House Numbers

- svhn_preprocess.ipynb: Pre-process svhn dataset for learning
- svhn_cnn.ipynb: build a convolutional neural network for detecting house number from images

## Install

This project requires **Python 2.7** and the following Python libraries installed:

- [TensorFlow](http://www.tensorflow.org/)
- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [SciPy library](http://www.scipy.org/scipylib/index.html)
- [Six](http://pypi.python.org/pypi/six/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

## Code

Project codes are provided in the following notebook files:
- `svhn_preprocess.ipynb`
- `svhn_cnn.ipynb`

## Run

In a terminal or command window, navigate to the top-level project directory `street_view_house_numbers/` (that contains this README) and run one of the following commands:

```python svhn_preprocess.ipynb```  
```jupyter notebook svhn_preprocess.ipynb```
```python svhn_cnn.ipynb```  
```jupyter notebook svhn_cnn.ipynb```

This will open the iPython Notebook software and project file in your browser.

While running svhn_cnn notebook following code is commented by default:


```saver.restore(session, "CNN_multi.ckpt")```

``` print("Model restored.") ```

Run the code and let it create a CNN_multi file with hyperparameters.
For the next iteration uncomment the above code so that the CNN_multi checkpoint file can be directly used by the model.


## Data

This project uses the [The Street View House Numbers (SVHN) Dataset](http://ufldl.stanford.edu/housenumbers/).

SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting. It can be seen as similar in flavor to MNIST (e.g., the images are of small cropped digits), but incorporates an order of magnitude more labeled data (over 600,000 digit images) and comes from a significantly harder, unsolved, real world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images. 
