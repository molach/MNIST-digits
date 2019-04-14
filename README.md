Program to use an artificial neural network to recognize the handwritten digits 0-9.

Requires the MNIST trainig set, available at http://yann.lecun.com/exdb/mnist/.

Specifically, it needs the following 2 files: "train-images-idx3-ubyte.gz" and "train-labels-idx1-ubyte.gz".

After downloading the files from the web page, run (on Linux or Cygwin) "gunzip <name-of-file>.gz" to unzip each .gz file.

Then the program "digits_train.pi" can create "digits.train", which will be in the proper FANN format, and which it will then use to train a NN.
