# Simple Keras CNN
I used this simple code to learn building a quick CNN with keras.

## Dependencies
I use Anaconda with Pycharm (MacOS), so it's really easy to install all the needed packages. But you can use virtualenv and pip too.

> Pycharm > Preferences > Project Interpreter > Add Local > Conda Environment > New Environment

Select the location of your new Anaconda environment. In my case:
> /Users/moritzkremb/anaconda3/envs/convnet_keras

Select Python version 2.7 -> Ok

Now add the following packages:
- numpy - v1.12.1
- scipy - v0.19.1
- theano - v1.0.1
- mkl
- keras

For this project we are using Keras with Theano backend (default is tensorflow). So we have to change the setting in the keras.json file. Open Terminal and type:

`nano ~/.keras/keras.json`

Now change the backend to "theano".

**You're all set!**
